# Vanilla RNN from Scratch 🧠

This project is a character-level RNN implemented **entirely from scratch in NumPy**, without using any deep learning libraries like TensorFlow or PyTorch.  
It demonstrates how Recurrent Neural Networks work at the lowest level — including forward propagation, backpropagation through time, sampling, and training on custom text sequences.

---

## Features

- Character-level language modeling
- Manual implementation of:
  - RNN cell forward pass
  - RNN cell backward pass
  - Full RNN forward and backward over sequences
  - Softmax-based prediction
  - Cross-entropy loss
- Support for mini-batch training
- Character sampling/generation with temperature control
- Clean and readable code, fully commented

---

## Loss Curve

Below is the training loss plotted over epochs:

![Loss Curve](loss.png)


## Example Output

Sample starting with 'm':  

manually. it is hard but also rewarding. this model learns to predict next characters. eventually it will generate realistic text samples. scearns to predict next character-level rnn trained from scrat

Sample starting with 't':  

trained from scratch. you are building backprop through time manually. it is hard but also rewarding. this model learns to predict next character-level rnn trained from scratch. you are building backpr

Sample starting with 'r':  

rewarding. this model learns to predict next characters. eventually it will generate realistic text samples. shqodict next. this is a custom characters. eventually it will generate realistic text. this


## TODOs / Extensions
 Add LSTM and GRU variants
 
 Add support for word-level tokenization

 Add gradient clipping

 Integrate CLI for text input and live sampling

 Export trained weights and reload later

## 👨‍💻 Author

**Nabeel Shan**  
Software Engineering Student - NUST Islamabad  
Aspiring AI Researcher | AI/ML Enthusiast  
[LinkedIn](https://www.linkedin.com/in/nabeelshan) • [GitHub](https://github.com/nabeelshan78)  
- Currently focused on mastering RNNs, LSTM, GRUs.
- Mastering Deep Learning architectures through hands-on work
- Looking to collaborate on AI/ML projects or research opportunities

---

## ⭐ Star the Repo

If you found this helpful, please consider **starring** 🌟 the repository - it helps others discover this resource and motivates continued open-source contributions.

---
