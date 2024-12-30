 # Word Embedding Techniques 

## Overview
This notebook demonstrates various word embedding techniques using the Keras library in TensorFlow. It covers methods for representing text data numerically, including one-hot encoding and embedding layers, to prepare it for machine learning models.

---

## Key Concepts Covered

### 1. Word Embedding Representation
- **One-hot encoding:** Converts words into a sparse binary vector format.
- **Embedding Layer:** Transforms words into dense vectors of fixed size, capturing semantic relationships.

### 2. Implementation
- Pre-padding for sequence length consistency.
- Setting feature dimensions for embeddings.
- Training and predicting with Keras' `Sequential` models.

---

## Requirements

### Libraries Used:
- TensorFlow (v2.x and above)
- Keras
- NumPy

### Additional Dependencies:
Ensure that `tensorflow-gpu` is installed for GPU acceleration.

---

## How to Use
1. Install the required libraries:
   ```bash
   pip install tensorflow-gpu numpy
   ```
2. Open the notebook and follow the cells to:
   - Understand one-hot representation of sentences.
   - Implement embedding techniques using Keras.
   - Experiment with vocabulary sizes and sequence dimensions.
3. Run the pre-defined models and analyze predictions.

---

## Potential Improvements
- Experiment with different sequence padding techniques.
- Use pre-trained embeddings like Word2Vec or GloVe for enhanced representations.
- Compare performance with character-level embeddings.

---

## Example Sentences Used
The notebook uses simple example sentences for testing embedding techniques, such as:
- "The glass of milk."

---

## License
This project is open-source and provided for educational purposes.

---

## Credits
Developed as part of an NLP learning series using Keras and TensorFlow.

