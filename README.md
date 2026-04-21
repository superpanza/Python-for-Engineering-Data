# Python-for-Engineering-Data
Working with Measurements, Signals, and Data Analysis

### Lezione 1 — Dal C al Python

Ambiente Jupyter · variabili e tipi dinamici · stringhe/f-string · liste, tuple, dizionari · control flow · funzioni con default e ritorno multiplo · import · list comprehension · try/except

**Esercizio:** convertitore di unità EE (dBm↔W, dBV↔V, report amplificatore)

---

### Lezione 2 — Pensare in vettori

NumPy: array, slicing, broadcasting, operazioni vettoriali, maschere booleane · FFT con `np.fft`, spettro monolatero, finestratura, zero-padding

**Esercizio:** generatore di segnali + analizzatore di spettro (3 sinusoidi + rumore)

---

### Lezione 3 — Filtrare, fittare, correlare

SciPy: filtro Butterworth/FIR, `filtfilt` vs `lfilter`, risposta in frequenza · Welch PSD · `find_peaks`, `curve_fit`, interpolazione, correlazione

**Esercizio:** caratterizzazione circuito RC (filtraggio → peak → fit esponenziale → stima τ)

---

### Lezione 4 — I dati dal mondo reale

File I/O: CSV, XLSX, TXT tab-separated, formato LabVIEW con header custom, `.npy`/`.npz` · Pandas base: DataFrame, selezione, filtering, colonne calcolate, statistiche

**Esercizio:** caricatore universale (4 file in formati diversi → DataFrame uniformi)

---

### Lezione 5 — Manipolare e combinare dati

Pandas avanzato: groupby, merge/join, concat, pivot/melt, rolling, apply, correlazioni · Esportazione: CSV, Excel multi-sheet con formattazione, LaTeX, pickle

**Esercizio:** quaderno di laboratorio digitale (5 run amplificatore → analisi → report Excel)

---

### Lezione 6 — Grafici, seriale e integrazione

Matplotlib OOP: subplot, spettrogramma, scatter+colormap, Bode plot, stili, export PDF · PySerial: lettura/scrittura, protocolli ASCII e binario, acquisizione continua

**Esercizio:** figura 2×2 per paper + oscilloscopio Python con simulatore seriale

---
