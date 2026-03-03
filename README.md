
> 🔬 ML/DS-инженер | 🐍 Python | 🚀 Production-ready решения

---

### 🚀 Production-проекты

#### 🎙️ [asr_service](https://github.com/pavell3333/asr_service)

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"> <img src="https://img.shields.io/badge/gRPC-000000?style=flat-square&logo=grpc&logoColor=white" alt="gRPC"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Triton-000000?style=flat-square&logo=nvidia&logoColor=green" alt="Triton">

**⚡ Высокопроизводительный streaming ASR-сервис с верификацией спикера**

- 🔄 **API** — Совместим с Yandex SpeechKit STT API v2(gRPC/REST)
- 🧠 **Инференс** — NVIDIA Triton + T-one CTC пайплайн
- 🔍 **VAD** — Silero VAD + KenLM для пост-обработки
- 🗄️ **Верификация:** Поиск эмбеддингов спикеров (ECAPA-TDNN) в Qdrant за <50ms среди 10k+ голосов.
- 📊 **Мониторинг** — Prometheus + Grafana + Loki стек
- 🌐 **Управление** — Web UI для работы с базой спикеров

[📁 Исходный код](https://github.com/pavell3333/asr_service) • [📖 Документация](https://github.com/pavell3333/asr_service#readme)

---

#### 🗣️ [ecapa-tdnn](https://github.com/pavell3333/ecapa-tdnn)

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Librosa-B31B1B?style=flat-square&logo=python&logoColor=white" alt="Librosa">

**🔐 Speaker Verification система на базе ECAPA-TDNN**

- 🎯 Архитектура: ECAPA-TDNN (192-dim эмбеддинги)
- 📞 Оптимизирована под телефонное аудио **8 kHz**
- 📦 Полный цикл: подготовка данных спикеров → обучение → инференс API
- 🧪 Метрики: EER, minDCF, ROC/DET кривые
- 🚀 REST API с поддержкой батчинга

[📁 Исходный код](https://github.com/pavell3333/ecapa-tdnn) • [📖 Документация](https://github.com/pavell3333/ecapa-tdnn#readme)

---

### 🧪 Исследования и прототипы

#### 🚗 [car_num](https://github.com/pavell3333/car_num)

<img src="https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">

**🔍 Детекция и распознавание автомобильных номеров**

- 📊 EDA + предобработка изображений (аугментации, нормализация)
- 🤖 Прототипы детекции (YOLO/SSD) + OCR-пайплайн
- 📈 Оценка метрик: precision, recall, mAP

[📁 Исходный код](https://github.com/pavell3333/car_num)

---

#### 📓 [notebooks](https://github.com/pavell3333/notebooks)

<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"> <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"> <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"> <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white" alt="Matplotlib">

**🧪 Коллекция исследовательских ноутбуков**

- `speaker_embedding.ipynb` — Визуализация эмбеддингов (t-SNE/UMAP), сравнение метрик косинусного сходства
- `zdravservis.ipynb` — EDA и предобработка данных медицинского сервиса

[📁 Исходный код](https://github.com/pavell3333/notebooks)

---

### 🛠️ Технологический стек

**🎙️ Speech & Audio:** ASR • Speaker Verification • VAD • Librosa • Torchaudio

**🤖 ML / DL:** PyTorch • TensorFlow • Transformers • scikit-learn • ONNX

**🔤 NLP:** Transformers • Hugging Face • Tokenization • BERT/RuBERT • Text Classification • NER

**🖼️ CV:** OpenCV • Albumentations • Detection (YOLO/SSD) • OCR • Image Preprocessing

**⚙️ Backend:** FastAPI • gRPC • Docker • Docker Compose • Redis • Qdrant • PostgreSQL

**📊 MLOps:** Prometheus • Grafana • Loki

**🔧 Tools:** Git • Linux • Bash • Jupyter • VS Code


---

> 💬 **Открыт к коллаборациям** в области Speech Tech, NLP, CV, ML-инфраструктуры и production-развёртывания моделей  
> 📫 **Связь:** [GitHub](https://github.com/pavell3333) • [Telegram](https://t.me/pavell32)

<p align="center">
  <sub>✨ Последнее обновление: 2026 • </sub>
</p>
