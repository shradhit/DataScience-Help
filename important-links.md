- PCA Visualization - https://towardsdatascience.com/pca-using-python-scikit-learn-e653f8989e60
- PCA Visualization / Confusion Matrix - https://github.com/shradhit/MNIST-/blob/master/final_SpecialTopics_ShradhitSubudhi.ipynb



`
mat = confusion_matrix(y_train, labels)

plt.figure(figsize=(7, 7))

sns.heatmap(mat.T, xticklabels=np.unique(y_train),
            annot=True,fmt="d",square=True, yticklabels=np.unique(y_train), cmap="Blues")
plt.xlabel('true label')
plt.ylabel('predicted label');


`
