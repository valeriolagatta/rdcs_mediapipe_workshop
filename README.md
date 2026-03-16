# MediaPipe Workshop: AI for Researchers & Practitioners

A hands-on workshop introducing [Google MediaPipe](https://developers.google.com/mediapipe) to researchers and practitioners with little to no machine learning background.

## 🎯 Workshop Overview

This 1-hour workshop covers three core MediaPipe capabilities:

| Module | What You'll Learn |
|--------|----------|-------------------|
| **Introduction** | What MediaPipe is, why it's useful, capabilities overview |
| **Hands-On Examples** | Hand detection, sentiment analysis, audio classification |
| **Conclusion** | Validation strategies, next steps, resources |

## 🎓 Prerequisites

- Basic Python knowledge (variables, functions, loops)
- No machine learning background required
- No deep learning knowledge needed

## 📁 Repository Structure

```
mediapipe-workshop/
├── README.md
├── mediapipe_workshop.ipynb    # Main workshop notebook
├── requirements.txt
├── hands/              # Images for hand detection exercises
│   ├── hand_sample_1.jpg
│   ├── hand_sample_2.jpg
│   └── ...
├── social_data/               # Dataset for sentiment analysis
│   └── df_tweets.csv
├── audio_samples/               # Audio files for classification (optional)
│   └── ...
└── models/                     # Downloaded automatically during workshop
    └── ...
```

## 🚀 Getting Started

### Option 1: Google Colab (Recommended)

No installation required! Click the button below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/mediapipe_workshop.ipynb)


## 📚 Workshop Content

### Part 1: Introduction 

- **What is MediaPipe?** — A plug-and-play AI toolkit from Google
- **Why MediaPipe?** — Free, simple, pretrained models, runs locally
- **Capabilities Overview** — Computer vision, NLP, audio analysis
- **Interactive Demo** — [MediaPipe Studio](https://mediapipe-studio.webapps.google.com/home)

### Part 2: Hands-On Examples 

#### 👋 Hand Detection 
- Detect and track 21 hand landmarks
- Works on images and video
- Applications: gesture recognition, sign language research, HCI

#### 💬 Sentiment Analysis 
- Classify text as positive or negative
- Process single texts or batches
- Applications: social media analysis, survey coding, content analysis

#### 🔊 Audio Classification (Bonus)
- Classify 521 different sound types
- Identify speech, music, environmental sounds
- Applications: interview analysis, media research, accessibility

### Part 3: Conclusion 

- Key takeaways and recap
- Validation strategies for research
- Resources for continued learning


## 🤝 Contributing

Found an issue or want to improve the workshop? Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📝 License

This workshop material is released under the [MIT License](LICENSE).

MediaPipe is licensed under the [Apache 2.0 License](https://github.com/google/mediapipe/blob/master/LICENSE).

## 🙏 Acknowledgments

- [Google MediaPipe Team](https://developers.google.com/mediapipe) for the excellent toolkit
- Workshop participants for feedback and suggestions

---

**Questions?** Open an issue or reach out to valerio.lagatta@northwestern.edu

*Last updated: March 2026*
