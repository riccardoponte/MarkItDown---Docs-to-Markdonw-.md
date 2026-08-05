# MarkItDown Ultimate - Web Edition

**MarkItDown Ultimate** è una workstation web a file singolo progettata per convertire una vasta gamma di documenti in **Markdown** pulito e strutturato. Ispirata al tool `markitdown` di Microsoft, questa versione è ottimizzata per la preparazione di dataset per modelli linguistici (LLM) e garantisce la massima privacy operando interamente lato client.

## 🚀 Funzionalità Principali

- **Conversione Multi-formato**: Supporto per Word, Excel, PowerPoint, PDF, EPUB, Immagini, CSV e JSON.
- **OCR Locale**: Riconoscimento del testo da immagini (PNG, JPG, WebP) direttamente nel browser tramite WebAssembly.
- **Analisi Intelligente del Layout**: Rilevamento automatico di titoli, sottotitoli e paragrafi nei PDF basato sulla dimensione del font e sulla posizione spaziale.
- **Estrazione Immagini**: Recupero delle immagini dai documenti Word e conversione in formato Base64 per l'analisi con modelli Vision.
- **Supporto EPUB**: Conversione di libri digitali mantenendo la struttura dei capitoli.
- **Metadati YAML**: Generazione automatica di un blocco di metadati (titolo, data, tipo di file) per fornire contesto ai modelli IA.
- **Privacy Totale**: Nessun file viene mai caricato su server esterni. Tutto il processo avviene localmente sul tuo computer.

## 📂 Formati Supportati

| Formato | Descrizione |
| :--- | :--- |
| **.docx** | Converte testi, titoli e tabelle. Estrae le immagini in Base64. |
| **.xlsx / .xls** | Trasforma ogni foglio di lavoro in una tabella Markdown. |
| **.pptx** | Estrae il testo slide per slide con intestazioni dedicate. |
| **.pdf** | Analisi avanzata per distinguere titoli e mantenere i paragrafi. |
| **.epub** | Converte libri digitali in un unico flusso Markdown strutturato. |
| **Immagini** | OCR multilingua (Italiano, Inglese, Francese, Tedesco, Spagnolo). |
| **.json / .csv** | Formattazione di dati strutturati in blocchi di codice o tabelle. |

## 🛠️ Tecnologie Utilizzate

L'applicazione integra le migliori librerie JavaScript open-source:
- **Tesseract.js**: Per l'OCR locale.
- **Mammoth.js**: Per la conversione fedele di file Word.
- **SheetJS (XLSX)**: Per l'elaborazione di fogli di calcolo.
- **PDF.js**: Per il rendering e l'estrazione dati da PDF.
- **Epub.js**: Per il parsing di file EPUB.
- **Turndown**: Per la conversione da HTML a Markdown.
- **Tailwind CSS**: Per un'interfaccia moderna e reattiva.

## 📖 Istruzioni d'Uso

1. Apri il file `markitdown-ultimate.html` in qualsiasi browser moderno (Chrome, Edge, Firefox, Safari).
2. (Opzionale) Seleziona la lingua per l'OCR dal menu a tendina in alto a destra.
3. Trascina i file nell'area di caricamento o clicca per selezionarli.
4. Attendi il completamento dell'elaborazione (monitorabile tramite la barra di progresso).
5. Copia il Markdown risultante o scaricalo come file `.md`.

---
*Creato per semplificare il flusso di lavoro tra documenti fisici/digitali e l'Intelligenza Artificiale.*
