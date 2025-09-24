<div align="center">

# 🛠️ Proyecto 3 – Pruebas de Interfaz y Funcionalidad en Urban Routes  

📌 **Rol:** QA Manual  
📌 **Objetivo:** Validar el diseño, las ventanas emergentes y la lógica del botón **"Reservar"** en la aplicación Urban Routes.  

</div>

---

## 📑 Descripción
Este proyecto se enfocó en **probar la experiencia de usuario y la lógica de negocio** de la app Urban Routes, incluyendo:  
- Comprobaciones de diseño en diferentes resoluciones de navegador.  
- Validación de ventanas emergentes: *Método de pago* y *Agregar tarjeta*.  
- Verificación de la lógica del botón **"Reservar"**.  
- Funciones adicionales como cancelación gratuita y activación de temporizador.  

---

## 🧰 Stack y Herramientas
<p align="center">
  <img src="https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Sheets-34A853?style=for-the-badge&logo=googlesheets&logoColor=white"/>
</p>

---

## ✅ Lista de Comprobaciones de Diseño
- Verificación de estado inicial del formulario.  
- Validación de íconos, títulos, subtítulos y características de cada tarifa.  
- Comprobación en resoluciones **800x600** y **1920x1080**.  

🔗 Algunos errores reportados en Jira:  
- [UR-1: Falta de características en la tarifa de lujo](https://monivascod.atlassian.net/browse/UR-1)  
- [UR-2: Múltiples íconos de automóviles mostrados incorrectamente](https://monivascod.atlassian.net/browse/UR-2)  
- [UR-7: No aparece ventana de confirmación de cancelación](https://monivascod.atlassian.net/browse/UR-7)  

---

## 💳 Ventanas de Pago
Pruebas sobre la ventana **“Agregar tarjeta”**:  
- Validación de formato de número de tarjeta (12 dígitos).  
- Restricciones en campo código (valores 01–99).  
- Comportamiento del botón **Agregar tarjeta** en diferentes entradas.  

🔗 Errores encontrados:  
- [UR-10: Botón activo con 12 dígitos incorrectos](https://monivascod.atlassian.net/browse/UR-10)  
- [UR-14: Código “00” aceptado como válido](https://monivascod.atlassian.net/browse/UR-14)  

---

## 🎛️ Lógica del Botón "Reservar"
Se probaron escenarios con y sin campos obligatorios:  
- Caso con todos los datos correctos → **Aprobado**.  
- Sin licencia de conducir → [UR-17](https://monivascod.atlassian.net/browse/UR-17).  
- Sin método de pago → [UR-18](https://monivascod.atlassian.net/browse/UR-18).  
- Sin direcciones → [UR-21](https://monivascod.atlassian.net/browse/UR-21).  

---

## ⏱️ Funciones de Reserva
- Activación del temporizador tras la reserva (**Aprobado**).  
- Cancelación gratuita durante el tiempo de espera → [UR-25](https://monivascod.atlassian.net/browse/UR-25).  
- Cambio automático al tiempo de uso compartido → [UR-26](https://monivascod.atlassian.net/browse/UR-26).  

---

## 📊 Resultados
- ✅ Se validaron múltiples escenarios de prueba (navegadores, resoluciones, inputs válidos e inválidos).  
- 🚨 Se identificaron varios defectos críticos relacionados con ventanas emergentes, validaciones de campos y la lógica del botón **Reservar**.  
- 📌 Todos los defectos fueron documentados y reportados en **Jira** con la trazabilidad correspondiente.  

---

<div align="center">

✨ Proyecto realizado como parte de mi formación en **QA Manual**.  
🔗 [Ver mi perfil de GitHub](https://github.com/monicavascod)  

</div>
