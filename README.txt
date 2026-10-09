ATMOS PWA READY

1. Copia la cartella "icons" dentro C:\Users\User\Desktop\iOi - Innovative Online Industries\ATMOS\icons
2. Sostituisci C:\Users\User\Desktop\iOi - Innovative Online Industries\ATMOS\manifest.webmanifest con quello incluso.
3. Sostituisci C:\Users\User\Desktop\iOi - Innovative Online Industries\ATMOS\sw.js con quello incluso.
4. Assicurati che le righe di HEAD_PATCH.txt siano presenti dentro <head> in index.html.
5. Assicurati che SERVICE_WORKER_PATCH.txt sia presente una sola volta prima di </body>.
6. Salva, poi:
   git add .
   git commit -m "PWA installabile"
   git push
7. Cloudflare Pages ridistribuisce automaticamente.
