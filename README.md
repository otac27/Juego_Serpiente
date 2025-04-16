
## 🎮 Controles

- Usa las teclas de flecha para mover la serpiente.
- Come la fruta roja para sumar puntos.
- El juego sube de nivel cada 5 frutas 🍓 y se vuelve más rápido.

## 📱 Responsive y Sonido

- Compatible con dispositivos móviles.
- Efectos de sonido al comer y perder.
"""

# Guardar archivos temporales
zip_path = "/mnt/data/Juego_Serpiente.zip"
with ZipFile(zip_path, "w") as zipf:
    zipf.writestr("index.html", index_html)
    zipf.writestr("README.md", readme_md)

zip_path
