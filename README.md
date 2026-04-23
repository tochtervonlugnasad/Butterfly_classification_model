# Butterfly_classification_model
Решение задачи по классификации 50 видов бабочек с использованием свёрточных нейросетей.

Использованные модели:
  **EfficientNet-B0** — лучший результат (93.8% accuracy)
  YOLOv8-cls (70% accuracy)
  YOLOv5 (40% accuracy)

Структура проекта:
butterfly-classification/
  butterfly_classification.ipynb 
  README.md
  requirements.txt 

**Результаты обучения**:
В процессе обучения модель EfficientNet-B0 достигла следующих показателей:
	Loss: 0.23
	Accuracy: 93.8%

Графики обучения:

<img width="1226" height="591" alt="{C243801B-0850-44B5-8FA0-097C9A84419A}" src="https://github.com/user-attachments/assets/5f51f6f7-af74-4c5d-ba9c-f5a7303c6ab6" />


**Использованные технологии**:
	Python 3.11
	PyTorch / Torchvision
	EfficientNet (предобученная на ImageNet)
	YOLOv8 / YOLOv5
	Pandas, NumPy, Matplotlib
	Jupyter Notebook

  **Автор**: tochtervonlugnasad
