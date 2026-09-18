---
title: get_images method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Sunumun tüm slaytları için Küçük Resim nesneleri döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Render seçenekleri. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Belirtilen slaytlar için Küçük Resim Bitmap nesneleri döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, slides):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Render seçenekleri. |
| slides | **List[int]** | Kaydırma konumlarını içeren dizi, 1'den başlayarak. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Belirtilen boyutta sunumun tüm slaytları için Küçük Resim nesneleri döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Render seçenekleri. |
| image_size | **aspose.slides.Size** | Oluşturulacak görüntünün boyutu. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Özel ölçeklendirme ile sunumun tüm slaytları için Küçük Resim nesneleri döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Render seçenekleri. |
| scale_x | **float** | Bu Küçük Resmi x ekseninde ölçeklendirecek değer. |
| scale_y | **float** | Bu Küçük Resmi y ekseninde ölçeklendirecek değer. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Belirtilen slaytlar için belirtilen boyutta Küçük Resim nesneleri döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Render seçenekleri. |
| slides | **List[int]** | Kaydırma konumlarını içeren dizi, 1'den başlayarak. |
| image_size | **aspose.slides.Size** | Oluşturulacak görüntünün boyutu. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Belirtilen slaytlar için özel ölçeklendirme ile Küçük Resim nesneleri döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Render seçenekleri. |
| slides | **List[int]** | Kaydırma konumlarını içeren dizi, 1'den başlayarak. |
| scale_x | **float** | Bu Küçük Resmi x ekseninde ölçeklendirecek değer. |
| scale_y | **float** | Bu Küçük Resmi y ekseninde ölçeklendirecek değer. |



### Ayrıca Bakınız
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* sınıf [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)