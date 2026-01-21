# Stumed-Learning-Analytics
## Análisis de Retención y Comportamiento Estudiantil: Caso Stumed
Por: Pilar Toussaint | Médica Pasante & Data Analyst
🩺 Sobre el Proyecto
Este proyecto analiza el comportamiento de los médicos aspirantes al ENARM (Examen Nacional de Aspirantes a Residencias Médicas) en la plataforma Stumed. El objetivo es identificar patrones de deserción académica y optimizar el compromiso (engagement) de los alumnos mediante el análisis de logs de actividad de Moodle.

## 📊 KPIs Analizados
Stickiness (DAU/MAU): Medición de la recurrencia diaria de los alumnos.

Time to First Activity (TTFA): Análisis del tiempo transcurrido desde la inscripción hasta el inicio del estudio (Onboarding).

Mapa de Calor de Actividad: Identificación de estacionalidad (fines de semana, festivos como Semana Santa) y deserción gradual.

Curva de Retención por Cohorte: Seguimiento de grupos de inscripción (Octubre vs. Julio).

## 💡 Hallazgos Clave
El umbral de las 48 horas: Los alumnos que no inician actividad en las primeras 48 horas tienen un riesgo X% mayor de inactividad prolongada.

Estacionalidad Cultural: Se identificó una caída crítica de actividad durante Semana Santa y Pascua, lo que sugiere la necesidad de estrategias de reactivación post-vacacional.

Patrones Semanales: El pico de actividad ocurre los martes, mientras que los domingos presentan la menor carga, ideal para mantenimientos técnicos.

## 🛠️ Herramientas Utilizadas
Python (Pandas, Numpy)

Visualización: Matplotlib, Seaborn

Plataforma Fuente: Moodle LM

Nota de Confidencialidad: Por razones de seguridad y protección de datos personales, los datasets originales han sido omitidos de este repositorio. Las visualizaciones y métricas presentadas utilizan datos anonimizados que no permiten la identificación de usuarios individuales ni revelan información comercial sensible de la institución.
