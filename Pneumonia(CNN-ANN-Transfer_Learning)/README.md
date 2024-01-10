# Proje Başlığı

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          		   | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 1200505056 | Yeşim Demir			| Yazılım Mühendisliği     | PROJE_4       | [Github](https://github.com/yesimdemir)     |
| 1200505026 | Musa Berk İşkal      | Yazılım Mühendisliği     | PROJE_4       | [Github](https://github.com/mberkiskal)     |
| 1200505002 | Muhsin Öztüfekçi     | Yazılım Mühendisliği     | PROJE_4       | [Github](https://github.com/MuhsinOztufekci)     |

---

## Proje Açıklaması

Bu proje, özel bir sınıflandırma görevini gerçekleştirmek için Convolutional Neural Network (CNN), Transfer Learning ve Yapay Sinir Ağı modellerini içerir. 
Projenin amacı, belirli bir veri kümesindeki nesneleri doğru bir şekilde sınıflandırmaktır.
Proje, üç farklı yaklaşımı içermektedir:

CNN Modeli Tasarımı:

CNN modeli tasarlanmış ve eğitilmiştir.
Eğitim, test ve doğruluk oranları aşağıda verilmiştir:

Test verisi için ayrıca şu metrikler hesaplanmıştır:
Accuracy
Precision
Recall
F1 Skoru
Karmaşıklık Matrisi
Classification Report

Transfer Learning:

Transfer Learning algoritmaları kullanılarak sınıflandırma yapılmıştır.
Eğitim, test ve doğruluk oranları aşağıda verilmiştir:

Test verisi için şu metrikler hesaplanmıştır:
Accuracy
Precision
Recall
F1 Skoru
Karmaşıklık Matrisi
Classification Report

Yapay Sinir Ağı Tasarımı:

Kendi özel Yapay Sinir Ağı tasarlanmış ve eğitilmiştir.
Test verisi için şu metrikler hesaplanmıştır:
Accuracy
Precision
Recall
F1 Skoru
Karmaşıklık Matrisi
Classification Report

Projede kullanılan teknolojiler: 
Python
TensorFlow
Keras


---

## Proje Dosya Yapısı

- */Pneumonia(CNN-ANN-Transfer_Learning)*
  - CNN__Transfer_Learning__Test_0_20.ipynb 
  - CNN__Transfer_Learning__Test_0_35.ipynb
  - Artificial_Neural_Network_0_20.ipynb
  - Artificial_Neural_Network_0_35.ipynb
- README.md


---

## Kurulum

Kurulum Adımları

Projeyi Klonlayın:

bash
Copy code
git clone https://github.com/yesimdemir/Pneumonia(CNN-ANN-Transfer_Learning).git
cd Pneumonia(CNN-ANN-Transfer_Learning)

Sanal Ortamı Oluşturun:

bash
Copy code
python -m venv venv
source venv/bin/activate   # Windows'ta: venv\Scripts\activate

Gerekli Bağımlılıkları Yükleyin:

bash
Copy code
pip install -r requirements.txt

Veri Setini İndirin:

bash
Copy code

# Proje veri seti indirme komutu (örnek olarak verilmiştir)
wget https://drive.google.com/file/d/1QlnV6PUZ3ic8M1_22cC5bAjJocYZKn1P/view
unzip Pneumonia.zip

CNN - Transfer Learning Modelini Eğitin:

bash
Copy code
cd CNN__Transfer_Learning__Test_0_20.ipynb
python train.py

Yapay Sinir Ağı Modelini Eğitin:

bash
Copy code
cd Artificial_Neural_Network_0_35.ipynb
python train.py

Modelleri Değerlendirin:

bash
Copy code
cd evaluation
python evaluate.py

Projeyi Sonlandırın:

Sanal ortamı sonlandırmak için:

bash
Copy code
deactivate   # Sanal ortamı kullandıysanız

Notlar

Projenin çalışabilmesi için gereken konfigürasyon dosyalarını (örneğin, model hyperparameters) kontrol edin ve gerekirse özelleştirin.
Kullanılan kütüphanelerin sürümlerini belirtmek için requirements.txt dosyasını güncelleyin.

---

## Kullanım

Kurulum başlığı altındaki adımlar takip edilir. Ayrıca aşağıdaki adımlar kontrol edilir.

Konfigürasyon Dosyaları:
Projenin çeşitli özelliklerini yapılandırmak için config veya benzeri bir klasör içerisindeki dosyaları inceleyin.

Veri Seti Düzeni:
Proje, özel bir veri seti üzerinde çalışıyorsa, veri seti düzenini ve dosya yollarını projenizin ihtiyaçlarına göre özelleştirin.

Model Hyperparameters:
CNN veya Transfer Learning modellerinin hyperparameter'larını değiştirmek için train.py dosyalarındaki ilgili bölümleri inceleyin.

Gelişmiş Kullanım:
Projenizi daha fazla özelleştirmek veya geliştirmek istiyorsanız, belgeleri ve kaynak kodları inceleyerek daha derin bir anlayış elde edebilirsiniz.
---

## Katkılar

https://github.com/balfatih
https://www.tensorflow.org/tutorials/images/transfer_learning?hl=tr
https://medium.com/@batincangurbuz/konvol%C3%BCsyonel-sinir-a%C4%9Flar%C4%B1-evri%C5%9Fimli-sinir-a%C4%9Flar%C4%B1-olarak-da-bilinir-convolutional-neural-4ecd2c5ad842
https://medium.com/@draj0718/convolutional-neural-networks-cnn-architectures-explained-716fb197b243
https://www.tensorflow.org/tutorials/images/cnn?hl=tr
https://www.geeksforgeeks.org/introduction-to-ann-set-4-network-architectures/

---

## İletişim

m.berkiskal@gmail.com
yesimdmr000@gmail.com 
muhsinoztufek@gmail.com 

