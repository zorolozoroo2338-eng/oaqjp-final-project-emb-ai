# Final Project

Projeto final do curso: **Emotion Detector**, uma aplicação web de detecção de
emoções desenvolvida em Python com a biblioteca Watson NLP e o framework Flask.

A aplicação recebe um texto, detecta as emoções (raiva, desgosto, medo, alegria
e tristeza) e informa qual é a emoção dominante.

## Estrutura

- `EmotionDetection/` - pacote com a função `emotion_detector`
- `server.py` - aplicação Flask (porta 5000)
- `test_emotion_detection.py` - testes unitários
- `templates/` e `static/` - interface web

## Como executar

    python3.11 server.py

Depois abra `http://localhost:5000`.

## Testes

    python3.11 -m unittest test_emotion_detection.py
