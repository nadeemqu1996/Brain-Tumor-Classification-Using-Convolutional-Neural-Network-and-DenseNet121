**Brain Tumor Classification Using Convolutional Neural Network and
DenseNet121**__

Brain tumors pose a significant healthcare
challenge, affecting individuals across age
groups. With the majority of primary Central Nervous System (CNS) tumors being
brain tumors, the annual diagnosis rate
exceeds 11,700 cases. Survival rates for
cancerous brain or CNS tumors remain at
around 34 percent for men and 36percent
for women. Accurate diagnostics and treatment planning are imperative to improve
patient outcomes and quality of life.This
project addresses the pressing need for
precise and efficient brain tumor diagnosis, leveraging advanced technology. Magnetic Resonance Imaging (MRI) is the gold
standard for brain tumor detection, yet it
generates intricate and voluminous image
data necessitating meticulous manual examination by radiologists, introducing potential errors.To mitigate these challenges,
our system employs cutting-edge deep learning techniques, specifically Convolutional
Neural Networks (CNN) and DenseNet121.
These models accurately differentiate between glioma, meningioma, and pituitary tumors, providing invaluable support to medical professionals. By harnessing artificial
intelligence, our system alleviates the cognitive load on healthcare practitioners, yielding highly accurate tumor type predictions
based on MRI scans, thus enhancing the
timeliness and precision of treatment decisions.

Approach 1 Results
Both metrics are plotted over a number of epochs
on the x-axis. The training accuracy appears relatively stable and consistently higher than the validation accuracy, which is typical as a model tends
to perform better on data it has seen (trained on)
versus new data. However, the validation accuracy
shows greater volatility with significant ups and
downs, which could indicate that the model is sensitive to the specifics of the validation data or that
the validation data is not entirely representative of
the problem space
"Training loss" in red and "Validation loss" in
blue, over a sequence of epochs along the x-axis.
The red line shows a steady and low level of training loss, which suggests that the model is learning
effectively from the training data. In contrast, the
validation loss exhibits high variability, including
several spikes which suggest that the model’s performance on the validation set is inconsistent and
potentially overfitting to the training data. The
most significant spike in validation loss suggests an epoch where the model performed particularly
poorly on the validation data. 

Approach 2 Results
DenseNet121 outperforms traditional CNNs in
image classification and object detection, as evident
from Figure 9’s confusion matrix. Our Approach2, using DenseNet121, excels over conventional
CNNs due to its densely connected layers, enhancing feature propagation and reuse. This results
in superior accuracy and reliability, showcasing
DenseNet121’s robustness and efficiency for complex image tasks. This highlights the significance
of advanced deep learning architectures, positioning DenseNet121 as an ideal choice for intricate
image challenges.

Addendum: Detailed observations and relevant illustrations are available in the report.pdf file
