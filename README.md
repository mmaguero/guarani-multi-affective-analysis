# guarani-multi-affective-analysis
Multidimensional Affective Analysis for Guarani/Jopara: emotion, humor and offense.

## Corpora
Affect dimensions (tweets primarily written in Guarani):
- Emotion-recognition: https://huggingface.co/datasets/mmaguero/gn-emotion-recognition
- Humor-detection: https://huggingface.co/datasets/mmaguero/gn-humor-detection
- Offensive-language-identifcation: https://huggingface.co/datasets/mmaguero/gn-offensive-language-identifcation

## Base models (LLMs to fine-tune)
- From scratch (trained on Guarani Wiki data):
    - https://huggingface.co/mmaguero/gn-bert-tiny-cased
    - https://huggingface.co/mmaguero/gn-bert-small-cased
    - https://huggingface.co/mmaguero/gn-bert-base-cased
    - https://huggingface.co/mmaguero/gn-bert-large-cased
- Continuously pre-trained (or pre-fine-tuned, also trained on Wiki data):
    - https://huggingface.co/mmaguero/multilingual-bert-gn-base-cased
    - https://huggingface.co/mmaguero/beto-gn-base-cased

## Baselines notebooks

- Bert-based models (fine-tuned with our above base models): https://colab.research.google.com/drive/1cjtykOqGz7B74yX452k5T0MbZmjtdpYc
- NCRFpp-based models (traned with https://github.com/jiesutd/NCRFpp library): https://colab.research.google.com/drive/1kzdxn0cdg7_bp6hSpAx3I8Pw9vul-8IM


## How cite?

```
@article{aguero-et-al2023multi-affect-low-langs-grn,
  title={Multidimensional Affective Analysis for Low-resource Languages: A Use Case with Guarani-Spanish Code-switching Language},
  author={Agüero-Torales, Marvin Matías, López-Herrera, Antonio Gabriel, and Vilares, David},
  journal={Cognitive Computation},
  year={2023},
  publisher={Springer},
  notes={Forthcoming}
}
```

