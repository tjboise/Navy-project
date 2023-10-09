# Navy-project
Topic: K1C images (DSLR & Keyence) classification into three classes. DSLR images are easier to get. We are supposed to develop a method to classifiy the DSLR images or Keyence images. If this method performs simialr in these two kinds of images, it means DSLR method is enough and we don't need to take Keyence iamges anymore, which can save time and laybor.

---

- Here are some references about this experiment: [reference1](https://www.wmtr.com/en.jic.html) | [reference2](https://www.testresources.net/applications/test-types/fracture-test/j-integral-fracture-toughness-test-equipment-j1c/) | [reference3](https://trace.tennessee.edu/cgi/viewcontent.cgi?article=3754&context=utk_gradthes).

---

Ideas: 

ML vs. DL: 100 images is a relatively small dataset for deep learning, especially when dealing with complex image classification tasks. Deep learning models tend to perform better with larger datasets. Insufficient data can lead to overfitting, where the model essentially memorizes the training data rather than learning meaningful patterns.

Machine-learning method: 
- [ ] Using Open-cv to select the features from the images: the percentage of the cracks area, shape, ...
- [ ] try different ML methods like K-means, KNN, DBSDAN to find the best way to cluster these features.

Deep learning method: 


---

Interested in which part of the image contributes to the final result.

[Useful repository](https://github.com/jacobgil/pytorch-grad-cam)

---
[schedual](/schedual.md)



