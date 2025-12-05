# 🌱 Agente Inteligente Reactivo Simple
## Diagnóstico de Deficiencias Nutricionales en Plantas

### 📋 Descripción

Este proyecto implementa un **Agente Inteligente Reactivo Simple** para el diagnóstico de deficiencias nutricionales en plantas. El agente utiliza reglas de condición-acción para mapear síntomas observados directamente a diagnósticos y tratamientos recomendados.

### 🎯 Características del Agente

| Característica | Descripción |
|----------------|-------------|
| **Tipo** | Agente Reactivo Simple |
| **Sin estado interno** | No guarda información entre percepciones |
| **Sin modelo del mundo** | No mantiene representación del ambiente |
| **Reglas condición-acción** | Mapeo directo: SI percepción → ENTONCES acción |

### 🔄 Arquitectura

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  SENSORES   │ ──► │   REGLAS    │ ──► │ ACTUADORES  │
│  (Síntomas) │     │ (Condición- │     │(Diagnóstico)│
│             │     │   Acción)   │     │             │
└─────────────┘     └─────────────┘     └─────────────┘
```

### 🌿 Deficiencias Detectables

- **Nitrógeno (N)**: Hojas verde pálido, clorosis, crecimiento atrofiado
- **Potasio (K)**: Bordes quemados, tallo débil, susceptibilidad a enfermedades
- **Fósforo (P)**: Hojas púrpura/rojizas, maduración tardía, raíces débiles

### 🚀 Demo en Vivo

Accede a la aplicación: [https://TU-USUARIO.github.io/agente-diagnostico-nutricional/](https://TU-USUARIO.github.io/agente-diagnostico-nutricional/)
