# Ecosistema Comercial HITL con Inteligencia Artificial

Ecosistema integral de automatización para la recepción, análisis, recuperación de conocimiento (RAG) y redacción automática de propuestas comerciales asistidas por Inteligencia Artificial con supervisión humana (Human-in-the-loop).

## 🚀 Arquitectura del Stack
* **Orquestador:** n8n (Integración y control de flujo de extremo a extremo).
* **Base de Datos & RAG:** Airtable (Tablas `Contactos`, `Tickets_venta`, `Knowledge_RAG`).
* **Motor de Razonamiento:** Google Gemini LLM.
* **Canal de Salida & Validación:** Gmail API (Notificación de propuestas para revisión humana).

---

## 📋 Criterios de la Rúbrica Oficial Implementados

1. **Mapa de Arquitectura (20%):** Flujo completo sin datos hardcodeados, variables dinámicas y conectividad multicanal documentada.
2. **Estructuras de Datos (20%):** Modelo relacional documentado con claves foráneas vinculadas y contratos de datos JSON.
3. **Matriz de Optimización de Costos (20%):** Cuadro comparativo justificando la adopción de modelos ligeros con ahorro de hasta 95% en costo operativo.
4. **Seguridad y Resiliencia (20%):** Minimización de datos, políticas de reintento (`Retry on Fail: 3`) ante fallos de API y patrón HITL para evitar el efecto metralleta.
5. **Dashboard de Control (20%):** Shared View pública en formato Kanban para monitoreo de estados y KPIs operativos.

---

## 🔗 Enlaces Obligatorios
* **Dashboard de Control (Airtable Shared View):** [Ver Tablero Kanban Público](PEGAR_AQUI_TU_LINK_DE_AIRTABLE)
* **Documento Técnico Completo:** [Descargar Entrega_Final_Ecosistema_HITL.pdf](./Entrega_Final_Ecosistema_HITL.pdf)
* **Workflow Exportado:** [Descargar workflow.json](./workflow.json)

---

## 📂 Evidencias Gráficas
Las capturas de respaldo individuales se encuentran en la carpeta [`/evidencias`](./evidencias):
* `01_arquitectura_n8n_completa.png`: Flujo integral en n8n con notas de arquitectura.
* `02_ejecucion_nodo_gemini.png`: Inferencia del modelo de IA con clasificación y propuesta.
* `03_actualizacion_db_airtable.png`: Registros de tickets completados en vivo.
* `04_salida_notificacion_gmail.png`: Correo recibido para validación humana HITL.
* `05_dashboard_kanban_airtable.png`: Tablero de control Kanban por estados.
