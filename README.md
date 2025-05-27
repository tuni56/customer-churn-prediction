# Customer Churn Prediction with SageMaker

Proyecto completo para predecir la fuga de clientes en una empresa de telecomunicaciones usando XGBoost y AWS SageMaker.

## 🔧 Tecnologías
- Python, pandas, scikit-learn, XGBoost
- AWS SageMaker, Lambda, API Gateway

## 📊 Objetivo
- Predecir la probabilidad de churn
- Reducir churn en un 24%
- Ahorro estimado: $2M anuales

## 📂 Estructura
- `notebooks/`: análisis exploratorio y entrenamiento
- `src/`: código limpio y modular
- `lambda/`: función para desplegar predicciones vía API Gateway

## 🚀 Entrenamiento y despliegue
1. Preprocesar datos (`src/preprocessing.py`)
2. Entrenar modelo local o en SageMaker (`src/train.py`)
3. Desplegar endpoint con SageMaker (`src/deploy_sagemaker.py`)
4. Servir predicciones vía Lambda y API Gateway

