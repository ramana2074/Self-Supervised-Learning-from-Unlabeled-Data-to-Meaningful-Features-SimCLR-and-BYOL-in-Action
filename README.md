# Self-Supervised-Learning-from-Unlabeled-Data-to-Meaningful-Features-SimCLR-and-BYOL-in-Action

Large-scale visual recognition commonly depended on on large human
annotated datasets, while picture labeling Consumed time and resources. Self-super
vised learning has emerged as a method of learning representations without manual 
supervision. Two frameworks Bootstrap Your Own Latent (BYOL) and Simple Con
trastive Learning of Representations (SimCLR) Trained the models with self-super
vised learning on unlabeled STL-10 dataset as done in: Visual features can be extracted 
in a label-free manner. BYOL trains proceeded for 200 epochs using a ResNet-18 back
bone. target encoder of momentum, and exponential moving average updates. SimCLR 
training was based on a contrastive objective with NT-Xent loss, projected into a 128
dimensional projection space. STL-10 Linear classification gave meaningful feature 
transfer: SimCLR had a test accuracy of 80.42% by under a frozen encoder setting and 
82.83% after full fine-tuning, and BYOL reached 78.45% under frozen encoder. The 
results were 82.27% after fine-tuning. Principal Component Analysis like PCA and t
SNE plots has shown clearer clustering boundaries after representation learning indi
cates enhanced separability.