# Monitoreo Ambiental IoT para Centro de Cómputo

Proyecto del curso de Desarrollo de IA (Building AI)

## Resumen
Sistema inteligente para la supervisión y predicción de condiciones ambientales (temperatura, humedad y calidad del aire) en salas de servidores y centros de cómputo utilizando sensores IoT y modelos de regresión/clasificación para prevenir fallas térmicas y de hardware.

## Antecedentes
¿Qué problema resuelve tu idea?
- Falta de monitoreo continuo de temperatura y humedad en salas de servidores.
- Riesgo de sobrecalentamiento y fallas inesperadas en equipos de cómputo críticos.
- Ausencia de alertas tempranas y análisis predictivo del entorno ambiental.

Motivación personal: Optimizar la infraestructura tecnológica educativa y prevenir interrupciones operativas mediante soluciones IoT y algoritmos sencillos de Machine Learning.

## Datos y técnicas de IA
- **Fuentes de datos:** Lecturas en tiempo real provenientes de un microcontrolador ESP32 equipado con sensores ambientales (DHT22, MQ-135, etc.).
- **Técnicas de IA:** Regresión lineal / Ridge para proyección de tendencias de temperatura, y Clasificación Bayesiana para detección de anomalías o estados de riesgo.

## ¿Cómo se utiliza?
El sistema toma lecturas contínuas en el centro de datos y procesa las métricas. Un tablero web muestra el estado en tiempo real y emite alertas automáticas cuando los modelos detectan variaciones de temperatura fuera de los rangos seguros.

## Desafíos
- Dependencia de la conectividad de red local para el envío de métricas.
- Requisito de calibración continua en los sensores de gas y temperatura para mantener la precisión de las predicciones.

## ¿Qué sigue?
Integrar modelos más avanzados de detección de series temporales (como redes LSTM) para anticipar fallas con horas de anticipación y automatizar el control directo sobre los sistemas de climatización.

## Agradecimientos
- Inspirado en el proyecto de residencia profesional para el Instituto Tecnológico del Istmo.
- Curso *Building AI* de Reaktor Innovations y la Universidad de Helsinki.
