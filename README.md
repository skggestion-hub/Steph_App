# 🏔️ Hotel Las Vicuñas — Centro de Financiamiento CORFO 2026

Panel de trabajo familiar para organizar y postular a los fondos concursables de **CORFO Región de Arica y Parinacota**.

**Sociedad Comercial Ulrich Krause Gronwald y CIA Ltda.** · Putre, 3.550 m.s.n.m. · Desde 1988.

---

## 🚀 Cómo publicar en GitHub Pages

1. Crear un repositorio nuevo en GitHub (por ejemplo `hotel-las-vicunas-fondos`).
2. Subir el archivo `index.html` y este `README.md`.
3. Ir a **Settings → Pages**.
4. En "Source" seleccionar la rama `main` y la carpeta `/ (root)`.
5. Guardar. En unos minutos el panel estará disponible en:
   `https://TU-USUARIO.github.io/hotel-las-vicunas-fondos/`

El panel funciona como un único archivo `index.html`, sin dependencias ni instalación.

---

## 📋 Qué incluye el panel

- **Tarjetas de convocatorias** ordenadas automáticamente por urgencia de cierre.
- **Filtros** por alcance (Regional Arica / Todo Chile) y por estado (cierra pronto / postulable hoy).
- **Cuenta regresiva** automática de días para postular (referencia: 24/06/2026).
- **Tip personalizado** para cada fondo, indicando cómo se conecta con un proyecto concreto del hotel.
- **Estrategia recomendada** paso a paso para la familia.
- **Checklist documental** común a todos los fondos (el progreso se guarda en el navegador).

---

## 🎯 Resumen de fondos vigentes (al 24/06/2026)

| Fondo | Alcance | Cierre | Monto | Afinidad |
|-------|---------|--------|-------|----------|
| **Innova Región (Turismo)** | Regional | 26/06/2026 | Hasta $60M (80%) | ⭐⭐⭐⭐⭐ |
| **Gestión de Innovación en Pymes** | Nacional | 15/07/2026 | Hasta $7,2M (70%) | ⭐⭐⭐⭐ |
| **Red Asociativa Diagnóstico** | Regional | 23/07/2026 | Hasta $8M (70%) | ⭐⭐⭐ |
| **Red Asociativa Desarrollo** | Regional | 22/07/2026 | Cofinanciamiento | ⭐⭐⭐ |
| **Red Mercados Desarrollo** | Regional | 22/07/2026 | Cofinanciamiento | ⭐⭐⭐ |
| **Crea y Valida** | Nacional | 04/08/2026 (Fase 1 cerró 09/06) | Hasta $180M | ⭐⭐ (2027) |

> ⚠️ Los montos, plazos y condiciones están sujetos a las bases oficiales. **Verificar siempre en [corfo.gob.cl/sites/cpp/regiones/aricaparinacota](https://www.corfo.gob.cl/sites/cpp/regiones/aricaparinacota/)** antes de postular.

---

## 🔄 Cómo actualizar la información

Las convocatorias CORFO cambian periódicamente. Para mantener el panel al día:

1. Abrir `index.html` en un editor de texto.
2. Buscar el bloque `const FUNDS = [` (cerca del final, dentro de `<script>`).
3. Cada fondo es un objeto con sus campos (`nombre`, `apertura`, `cierre`, `benefit`, `tip`, `url`, etc.). Editar, agregar o quitar según el portal de CORFO.
4. Actualizar también la constante `const TODAY = new Date(2026, 5, 24);` con la fecha real al revisar (mes en JavaScript va de 0 a 11: junio = 5).
5. Guardar y volver a subir a GitHub.

---

## 📞 Contacto CORFO Arica y Parinacota

- **Dirección:** 21 de Mayo 551, Arica
- **Teléfono:** (+58) 2351650
- **Email:** oficinadepartesarica@corfo.cl
- **Agentes Operadores:** [Listado de intermediarios CORFO](https://www.corfo.gob.cl/sites/cpp/intermediario/)

---

*Hecho con cariño para la Familia Krause Garrido. En honor a Don Ulrich Krause Gronwald.*
