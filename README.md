# 🎮 GBA Web Emulator AI

<img width="556" height="786" alt="image" src="https://github.com/user-attachments/assets/1045bf83-55aa-4f05-8b1b-6f8b7979b67c" />

![React](https://img.shields.io/badge/React-v19.2.0-61DAFB?logo=react)
![Gemini](https://img.shields.io/badge/Google%20Gemini-1.5%20Pro-8E75B2?logo=google-gemini)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-38B2AC?logo=tailwind-css)

**GBA Web Emulator AI** è un'applicazione web progressiva che permette di giocare ai titoli Game Boy Advance direttamente dal browser.

## ✨ Funzionalità

* **Emulazione Client-Side**: Esecuzione fluida delle ROM `.gba` utilizzando il core `gbajs`.
* **Supporto BIOS**: Possibilità di caricare il firmware originale GBA (`.bin`) per la massima accuratezza.
* **Controlli Multipli**:
    * Supporto tastiera completo.
    * Controlli touch a schermo per dispositivi mobili.
    * Supporto nativo per Gamepad (API browser).
* **Design Moderno**: Interfaccia "Pixel-Perfect" scura, stilizzata con Tailwind CSS e font retro (Press Start 2P).

## 🛠️ Librerie e Tecnologie Utilizzate

Il progetto è un esempio di applicazione moderna senza build-step complessi (caricamento via ESM/Import Maps), utilizzando:

* **[React 19](https://react.dev/)**: Utilizza le ultimissime feature come il nuovo runtime JSX e gli hook standard (`useState`, `useEffect`, `useRef`).
* **[gbajs](https://github.com/endrift/gbajs)**: Il motore di emulazione sottostante, caricato dinamicamente via CDN per gestire CPU ARM, video e audio.
* **[Tailwind CSS](https://tailwindcss.com/)**: Gestione dello stile via CDN con configurazione personalizzata per colori e font.

## 🎮 Mappatura Controlli (Tastiera)

| Tasto GBA | Tasto Tastiera |
| :--- | :--- |
| **D-Pad** | Frecce Direzionali |
| **A** | `Z` |
| **B** | `X` |
| **L** | `A` |
| **R** | `S` |
| **Start** | `Invio` |
| **Select** | `Shift` |

## ⚠️ Disclaimer Legale
Questo emulatore è un software creato per scopi educativi e di preservazione. **Non include alcun file ROM di gioco né file BIOS.** L'utente è tenuto a fornire i propri file dumpati legalmente dalle cartucce fisiche in suo possesso.
