# Kidney_Cancer_Deep_Learning

:information_source: **Dersin Kodu:** [YAZ20411](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Adı:** [DERİN ÖĞRENME](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ20411/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No  | Adı Soyadı           | Bölüm          		    | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|-------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 1200505022  | Sayithan Usta		 | Yazılım Mühendisliği        | PROJE_5       | [Github](https://github.com/sayithanxus)          |
| 1200505054  | Ömer Tarık Sangın    | Yazılım Mühendisliği     | PROJE_5       | [Github](https://github.com/omersenpai)           |
| 1200505014  | Ceren Gül Durmuş     | Yazılım Mühendisliği     | PROJE_5       | [Github](https://github.com/ceren945)             |
| 1190505802  | Ezgi Durmaz          | Yazılım Mühendisliği     | PROJE_5       | [Github](https://github.com/ezgidurmaz)           |

---

## Proje Açıklaması

Bu proje, böbrek kanseri hastalıklarının tespiti için görüntü analizi üzerine odaklanan bir çalışmadır. Sağlık alanında kullanılan [Veri Seti](https://drive.google.com/drive/folders/1vZVbShUmjZnlPub3SW3C1IK_WZDGoAQ_?usp=drive_link) içerisinde yer alan böbrek kanserine ait görüntüler üzerinde sınıflandırma yapılacaktır. Projenin amacı, farklı modelleme yaklaşımlarını kullanarak en iyi performansı elde etmek ve böbrek kanseri tespitinde etkili bir sınıflandırma gerçekleştirmektir.

---
## Proje Amacı

Görüntü analizi ve derin öğrenme tekniklerini kullanarak böbrek kanseri tespiti konusunda bir adım daha ileri gitmeyi hedeflemektedir. Bu çalışma, sağlık sektöründeki teşhis süreçlerini geliştirmeye yönelik bir örnek olabilir ve gelecekteki benzer projeler için bir kaynak sağlayabilir.

---
## Kullanılan Teknolojiler

Python programlama dili<br>
Derin öğrenme kütüphaneleri: TensorFlow, Keras<br>
Google Colab ortamı

---
## Proje Dosya Yapısı

- **/Derin_Ogrenme_Proje_Odevi**
  - **/ANN**
    - `ARTIFICAL_NEURAL_NETWORK_65_35.ipynb`
    - `ARTIFICAL_NEURAL_NETWORK_80_20.ipynb`
  - **/CNN**
    - `CNN_RANDOM_SEARCH_65_35.ipynb`
    - `CNN_RANDOM_SEARCH_80_20.ipynb`
  - **/Transfer_Learning**
    - `TRANSFER_LEARNING_65_35.ipynb`
    - `TRANSFER_LEARNING_80_20.ipynb`
- `README.md`


---
## Kurulum
**Python yüklü değilse :**
Python'un 3.0 sürümünü resmi web sitesinden Python'u indirin ve yükleyin. => https://www.python.org/downloads/

**TensorFlow ve Keras kütüphanelerini yüklemek için terminal veya komut istemcisine şu komutları yazın: :**
<br>
pip install tensorflow 
<br>
pip install keras

Proje dosyalarını bir klasöre indirin veya kopyalayın.

Jupyter Notebook veya başka bir Python geliştirme ortamında proje dosyalarını açın.

**Veri Seti Link :** [Veri Seti](https://drive.google.com/drive/folders/1vZVbShUmjZnlPub3SW3C1IK_WZDGoAQ_?usp=drive_link)

Her bir modelin performansını değerlendirmek için ilgili test fonksiyonlarını çalıştırın.

---
## Kullanım

Projenin nasıl kullanılacağına dair bilgileri ekleyin. Örneğin, projenizi bir kişi bilgisayarına indirdiğinde sorunsuz bir şekilde çalıştırması için yapması gereken adımları listeleyin.

---
## Sonuç

Böbrek kanseri tespiti konusunda hangi modelin daha etkili olduğunu anlamak için kullanılabilir. Ayrıca, bu çalışma, görüntü analizi ve derin öğrenme alanında ilerleyen projeler için bir temel oluşturabilir.

---
## Proje Sonuç Çıktıları(Colab üzerinden yapıldı)
**Transfer Learning-1 :** [80-20](https://colab.research.google.com/drive/1Al9meqxh6eQhtOSM9gUSWZDqtN5KRBTe?authuser=1)<br>
**Transfer Learning-2 :** [65-35](https://colab.research.google.com/drive/1BWRiDsx-5VJ6KXLBrNif2BtcaFL5yjyP?authuser=1)
<br><br>
**CNN-1 :** [80-20](https://colab.research.google.com/drive/1JikUiCTGJzPPibE9-mnQTKk4s5_yQ21n?authuser=1)<br>
**CNN-2 :** [65-35](https://colab.research.google.com/drive/1XsJwbyU5eVrnVmepY4eP3GL0vRe8S8YX?authuser=1)
<br><br>
**ANN-1 :** [80-20](https://colab.research.google.com/drive/1Nf_j-FGEBjfS9EftOBS2tjezFSj_67S9?authuser=1)<br>
**ANN-2 :** [65-35](https://colab.research.google.com/drive/16v2O67Mvl4gA5Um3eTGJR9o9FFqFYkyv?authuser=1)
---
## Katkılar

[Transfer Öğrenme Nedir ? ](https://medium.com/novaresearchlab/%C3%B6%C4%9Frenme-aktar%C4%B1m%C4%B1-transfer-learning-c0b8126965c4)<br><br>
[Keras](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers/Optimizer)<br><br>
[CNN kullanarak görüntü sınıflandırma](https://esraturkan.medium.com/cnn-kullanarak-g%C3%B6r%C3%BCnt%C3%BC-s%C4%B1n%C4%B1fland%C4%B1rma-141936ef6612)<br><br>
[Yapay Sinir Ağları(ANN)](https://www.codingtxt.com/blog/detail/python-ile-yapay-sinir-aglari-olusturma-ve-egitme-adim-adim-rehber-51bcaa08-29c4-4c#gsc.tab=0)<br><br>
[Keras ve derin öğrenme ile Transfer Öğrenme](https://pyimagesearch.com/2019/05/20/transfer-learning-with-keras-and-deep-learning/)
---

## İletişim

Sayithan Usta     : sayit2828@hotmail.com

Ömer Tarık Sangın : berkomer16@gmail.com

Ceren Gül Durmuş  : cerengul2000945@gmail.com

Ezgi Durmaz       : ezgidurmaaz@gmail.com
