# 💰 FinGuard AI: Consultoria Financeira por Voz com IA Generativa

O **FinGuard AI** é uma solução de inteligência artificial voltada ao relacionamento financeiro e educação financeira. O projeto utiliza modelos de linguagem de última geração para oferecer uma experiência de usuário (UX) fluida, onde o cliente pode consultar sua saúde financeira, simular investimentos e tirar dúvidas através da voz.

Este projeto representa o **Desafio Final** do Bootcamp de IA Generativa da DIO, consolidando conhecimentos em Python, Engenharia de Prompt, Persistência de Contexto e Processamento de Linguagem Natural (NLP).

---

## 🌟 Principais Funcionalidades

- **Interface de Voz Natural:** Captura de áudio diretamente pelo navegador, permitindo acessibilidade e praticidade.
- **Consultoria Especializada:** System Prompt configurado para atuar como um consultor financeiro ético, didático e empático.
- **Cálculos em Tempo Real:** Capacidade de realizar simulações de juros, aportes e rendimentos com explicações passo a passo.
- **Saída de Áudio Personalizada:** Respostas vocalizadas que reforçam a identidade da marca e melhoram a experiência do usuário.

---

## 🏗️ Arquitetura do Sistema

A solução foi construída utilizando uma pipeline multimodal:

1.  **Entrada (Audio Capture):** Interface JavaScript integrada ao Google Colab.
2.  **Processamento de Áudio (Pydub):** Normalização e conversão para o formato WAV (PCM).
3.  **Reconhecimento de Fala (SpeechRecognition):** Conversão de fala em texto (STT) via motor Google.
4.  **Cérebro (Gemini 2.5 Flash):** Modelo de IA de alta velocidade que processa a intenção do usuário sob uma persona financeira.
5.  **Saída (gTTS):** Síntese de voz (TTS) para retorno da consultoria em áudio.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem Principal:** Python 3.12
- **IA Generativa:** Google Gemini API (Modelo 2.5 Flash)
- **Bibliotecas de NLP/Áudio:** `SpeechRecognition`, `gTTS`, `Pydub`
- **Ambiente de Desenvolvimento:** Google Colab

---

## 🚀 Como Utilizar

1.  Clone este repositório.
2.  Abra o arquivo `.ipynb` no Google Colab.
3.  Obtenha sua API Key no [Google AI Studio](https://aistudio.google.com/).
4.  Configure a chave nos **Secrets** do Colab com o nome `GOOGLE_API_KEY`.
5.  Execute as células em sequência: grave sua pergunta financeira e ouça a análise da IA.

---

## ⚖️ Boas Práticas e UX

- **Segurança:** O sistema inclui avisos de que não deve processar dados sensíveis como senhas bancárias.
- **Feedback Visual:** O console exibe o status de cada etapa (Gravando, Analisando, Sintetizando).
- **Tom de Voz:** Persona configurada para ser encorajadora, auxiliando na redução da ansiedade financeira do usuário.

---

## 👨‍💻 Autor
**Walter Salles**
Especialista na área financeira em transição para Ciência de Dados e BI. 
*Desenvolvendo soluções que unem a precisão dos dados financeiros com a empatia da IA.*

---
