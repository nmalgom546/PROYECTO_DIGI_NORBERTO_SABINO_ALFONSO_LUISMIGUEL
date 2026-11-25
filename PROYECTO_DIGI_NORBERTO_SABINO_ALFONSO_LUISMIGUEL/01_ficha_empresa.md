# Ficha de la Empresa

## 🏢 Información General
* **Nombre de la empresa:** Bebidas del Sur S.L.
* **Sector:** Industria alimentaria y de bebidas (Elaboración, embotellado y distribución).
* **Tamaño:** Mediana empresa (85 empleados en plantilla).
  * *Planta / Producción:* 50 operarios y técnicos de mantenimiento.
  * *Oficina / Negocio:* 35 empleados (ventas, logística, administración y dirección).
* **Productos principales:** Zumos naturales prensados en frío, refrescos artesanales sin gas y té frío embotellado en cristal y PET reciclado.
* **Perfil de clientes:** Cadenas de supermercados regionales, distribuidores del canal HORECA (Hoteles, Restaurantes y Cafeterías) y venta directa B2B a minoristas.

---

## 📉 Situación de Partida (Diagnóstico AS-IS)

Actualmente, **Bebidas del Sur S.L.** opera con una desconexión clara entre sus áreas de producción y de negocio:

1. **Planta (OT):**
   * Las líneas de embotellado funcionan con PLCs independientes y un sistema SCADA antiguo que solo muestra alarmas locales.
   * El control de calidad (nivel de llenado, sellado de tapones y etiquetado) se realiza mediante muestreo manual periódico por parte de los operarios.
   * El mantenimiento de la maquinaria es reactivo (se arregla cuando se rompe) o preventivo basado en horas fijas, lo que provoca paradas no planificadas en picos de demanda.

2. **Negocio (IT):**
   * Se utiliza un ERP comercial básico para contabilidad y facturación, pero sin conexión directa con los datos en tiempo real de la fábrica.
   * La estimación de la demanda de ventas se hace en hojas de cálculo basándose en la intuición de los comerciales, lo que provoca desajustes frecuentes de inventario (roturas de stock o exceso de materia prima perecedera).
   * La logística de reparto gestiona las rutas de forma fija por zonas geográficas, sin tener en cuenta el tráfico o urgencias de última hora.
