# A-Large-Scale-Fish-Dataset_Ann
# Balık Sınıflandırma Projesi

## Genel Bakış
Bu proje, Fish Dataset'e dayanan bir derin öğrenme modeli kullanarak balık türlerini sınıflandırmayı amaçlamaktadır. Veri seti, farklı balık türlerine ait görüntülerden oluşmaktadır ve model TensorFlow ve Keras kullanılarak eğitilmiştir.

## Kullanılan Teknolojiler
- Python
- TensorFlow
- Keras
- OpenCV
- Pandas

## Veri Seti
Kullanılan veri seti, çeşitli balık türlerine ait görüntülerin yer aldığı Kaggle'dan alınmış Fish Dataset'tir. Görüntüler model girişine uygun olacak şekilde yeniden boyutlandırılmış ve işlenmiştir.

## Model ve Eğitim
Yoğun (Dense), Dropout ve Flatten katmanlarını içeren bir derin sinir ağı, kategorik çapraz entropi kaybı (categorical crossentropy loss) ve Adam optimizasyonu kullanılarak eğitilmiştir.

## Sonuçlar
Model, test veri setinde %95 doğruluk elde etmiştir.

## Kaggle Notebook
Notebook'a Kaggle üzerinden şu https://www.kaggle.com/code/yigitoner/a-large-scale-fish-dataset-ann ulaşabilirsiniz.
