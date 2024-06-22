### Breast Cancer Detection Using Ultrasound Images

#### A. Objectives
The primary objective of this project is to enhance the accuracy and efficiency of breast cancer detection using ultrasound images by leveraging both weakly supervised and fully supervised learning models. To achieve this, we utilized pre-trained CNN models such as VGG19, MobileNet, and ResNet50. This approach aims to address the data annotation challenges by exploring alternative supervised learning techniques.

#### B. Methodology
1. **Data Collection and Preprocessing:**
   - We collected a comprehensive dataset of ultrasound images, ensuring a diverse representation of breast cancer cases.
   - The images were preprocessed to ensure uniformity and optimal input quality for the DL models.

2. **Model Selection:**
   - Three pre-trained CNN models were employed:
   - Fully supervised learning models
      - VGG19
        ![fsl_vgg19](https://github.com/ChristianthomasBADOLO/Enhanced_and_Full_Supervision_in_Breast_Cancer_Detection/assets/167626485/8d916217-dc1a-4321-bf99-c2339365cf94)
      - MobileNet
        ![fsl_mobilenet](https://github.com/ChristianthomasBADOLO/Enhanced_and_Full_Supervision_in_Breast_Cancer_Detection/assets/167626485/3ff28d8b-b48a-43bd-b1bf-90029dd2daf0)
      - ResNet50.
        ![fsl_resnet50](https://github.com/ChristianthomasBADOLO/Enhanced_and_Full_Supervision_in_Breast_Cancer_Detection/assets/167626485/b014928c-7546-464e-af14-be92ebfcff5b)
   - These models were selected for their effectiveness in image recognition and classification tasks.

3. **Weakly Supervised Learning:**
   - Weakly supervised learning techniques were applied to leverage partially labeled data.
   - This involved using image-level labels rather than requiring detailed pixel-level annotations, reducing dependency on extensive manual annotations by radiologists.

4. **Fully Supervised Learning:**
   - Fully supervised learning models were trained using meticulously annotated datasets.
   - This approach ensures high accuracy by utilizing detailed, expert-provided annotations.

5. **Training and Validation:**
   - Models were trained on preprocessed ultrasound images, with separate datasets for weakly and fully supervised learning.
   - Performance was validated using a hold-out validation set to assess model accuracy and reliability.

6. **Evaluation and Comparison:**
   - Performance of weakly supervised models was compared with fully supervised models.
   - Metrics such as accuracy, sensitivity, specificity, and F1-score were used to evaluate model performance.

#### C. Results
- Fully supervised models outperformed weakly supervised models, demonstrating superior accuracy and robustness in breast cancer detection.
  ![resnet_train](https://github.com/ChristianthomasBADOLO/Enhanced_and_Full_Supervision_in_Breast_Cancer_Detection/assets/167626485/1353db59-42f6-4017-b285-1134017f8bc9)
  ![restnet_test](https://github.com/ChristianthomasBADOLO/Enhanced_and_Full_Supervision_in_Breast_Cancer_Detection/assets/167626485/c1c99395-44c2-4bcd-b81c-7977ed5d7ab2)
- Among tested models, fully supervised ResNet50 showed the highest performance, significantly surpassing VGG19 and MobileNet.

#### D. Conclusion
This project showcases the effectiveness of fully supervised learning for breast cancer detection using ultrasound images. Integration of pre-trained CNN models like VGG19, MobileNet, and ResNet50 provides a robust solution, with fully supervised ResNet50 delivering the best diagnostic accuracy. Future work will focus on optimizing these models further and exploring semi-supervised and unsupervised learning techniques to reduce dependency on annotated datasets.

---

Feel free to adapt and expand upon this README template for your GitHub repository.
