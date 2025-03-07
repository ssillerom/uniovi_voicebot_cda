<img src="https://web.gcompostela.org/wp-content/uploads/2019/02/University-of-Oviedo.png" alt="Uniovi logo">

# Agente de Voz en Python con capacidad de vision

> Práctica para la Universidad de Oviedo

## Descripción

Este proyecto implementa un agente de voz utilizando LiveKit y Python. Permite la interacción por voz mediante una interfaz que procesa lenguaje natural y responde a comandos de voz.

## Requisitos

- Python 3.8 o superior
- Claves API para:
  - LiveKit
  - OpenAI
  - Elevenlabs
  - Deepgram

## Instalación

Clone el repositorio e instale las dependencias en un entorno virtual:

```console
# Linux/macOS
cd uniovi_voicebot_cda
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 agent.py download-files
```

<details>
  <summary>Instrucciones para Windows</summary>
  
```cmd
# Windows (CMD/PowerShell)
cd uniovi_voicebot_cda
python3 -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python3 agent.py download-files
```
</details>

## Configuración

Copie el archivo `.env.example` a `.env.local` y complete los siguientes valores:

- `LIVEKIT_URL`
- `LIVEKIT_API_KEY`
- `LIVEKIT_API_SECRET`
- `OPENAI_API_KEY`
- `ELEVEN_API_KEY`
- `ELEVENLABS_VOICE_ID`
- `DEEPGRAM_API_KEY`

## Ejecución

Para ejecutar el agente:

```console
python3 agent.py dev
```

## Autores

Desarrollado para la práctica de la Universidad de Oviedo.
