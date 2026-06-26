# 📸 Arch Screenshot Share

---

## 🚀 ¿Qué es esto?

Este es un script simple para Arch Linux que permite hacer capturas de pantalla y enviarlas directo a una carpeta compartida con Windows.

La idea es simple:

📸 capturas una parte de la pantalla  
📂 se guarda en una carpeta compartida  
🪟 Windows la ve al instante  
⏳ se mantiene 45 segundos  
🧹 luego se borra sola  

Es básicamente un “clipboard visual” entre Arch y Windows.

---

## ⚙️ Requisitos

- :contentReference[oaicite:0]{index=0} instalado  
- Carpeta compartida montada en ```text /mnt/shared ```

---

## 🧠 Cómo funciona

1. ejecutas el script  
2. seleccionas el área de pantalla  
3. se guarda en `/mnt/shared`  
4. Windows lo ve al instante  
5. espera 45 segundos  
6. se borra solo  

---

## 🪟 En Windows

Abres el explorador y escribes:

```text \\192.168.1.49\shared ```

Ahí aparecen todas las capturas en tiempo real.

---

## ⌨️ Ctrl + C

Si cancelas el script:

→ se detiene el proceso  
→ se elimina la captura  
→ no deja archivos basura  

---

## 💡 Nota importante

Si no ves los archivos en Windows:

👉 revisa que `/mnt/shared` esté bien montado  
👉 revisa que Samba esté activo  
👉 revisa permisos de escritura  

---

## 🔥 Idea del proyecto

Un sistema simple tipo:

🐧 Arch Linux → 🪟 Windows  
📸 capturas → sync instantáneo → limpieza automática  

Como un “AirDrop casero” entre PCs.
