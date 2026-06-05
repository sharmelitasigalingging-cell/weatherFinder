# WeatherFinder — Pertemuan 10 Praktikum

Aplikasi cuaca real-time React Native + Expo yang
mendemonstrasikan useEffect, debounce, dan integrasi API.

## Fitur
- Cari cuaca berdasarkan nama kota
- Debounce 500ms (hemat request)
- 4 kondisi UI: kosong / loading / error / sukses
- Data dari Open-Meteo (gratis, tanpa API key)

## Konsep yang Dipakai
- useState (4 state), useEffect (dependency array)
- Debounce dengan setTimeout + clearTimeout
- AbortController untuk cleanup & anti race-condition
- Conditional rendering dengan operator &&

## Cara Menjalankan
1. npm install
2. npx expo start
3. Scan QR dengan Expo Go

## Link
- Expo Snack: [https://snack.expo.dev/@arin_its06/weather-finder]

## Screenshot
![Kondisi Awal] <img width="1080" height="2340" alt="tampilan awal" src="https://github.com/user-attachments/assets/1af62414-277b-46ce-ad63-8fbf6808ab30" />
)
![Loading](<img width="1080" height="2340" alt="surabaya loading" src="https://github.com/user-attachments/assets/37cee62d-21cd-4fcd-aa67-5edbb5863109" />
)
![Hasil](<img width="738" height="1600" alt="hasil jakarta" src="https://github.com/user-attachments/assets/5c8d1b8f-1b92-4e9a-a4c9-2d0d42f6ad70" />
)
EROR (<img width="1080" height="2340" alt="eror" src="https://github.com/user-attachments/assets/24645452-16ce-4f65-ab4a-ddc17ddcc0c0" />
)
## Author
[SHARMELITA ARNI TERESIA SIGALINGING] - [243303621242] - Universitas Prima Indonesia
