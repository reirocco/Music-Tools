# 🎵 MP3 Tools

Una raccolta di strumenti utili per gestire, convertire e ottimizzare file MP3 (e non solo).  
Questa repository crescerà nel tempo includendo script per:

- Conversione audio/video in MP3
- Normalizzazione del volume
- Rimozione silenzi
- Gestione tag ID3
- Pulizia batch di librerie audio
- Analisi qualità e bitrate

---

## 🚀 mp3-converter.sh

Questo script permette di convertire qualsiasi file audio o video in formato **MP3** usando FFmpeg.  
Supporta sia la conversione di **un singolo file**, sia la conversione **batch** della directory corrente.

### ✨ Funzionalità

- Converte automaticamente formati comuni (wav, flac, m4a, mp4, mov, ogg, webm, avi, wma, aac…)
- Mantiene la qualità con codifica **VBR (libmp3lame)**
- Evita di riconvertire file già `.mp3`
- Elimina il file originale **solo dopo** una conversione riuscita
- Mostra un riepilogo finale
- Non richiede dipendenze extra oltre a `ffmpeg`

---

## 🔧 Requisiti

- `bash`
- `ffmpeg` installato  
  *Debian/Ubuntu:*  
  ```bash
  sudo apt install ffmpeg
