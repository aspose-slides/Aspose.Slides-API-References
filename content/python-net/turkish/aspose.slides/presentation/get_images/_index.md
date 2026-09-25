---
title: get_images method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Bir sunumun tüm slaytları için Image nesneleri döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff seçenekleri. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Belirtilen slaytlar için Thumbnail Image nesneleri döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, slides):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff seçenekleri. |
| slides | **List[int]** | Slayt konumlarını içeren dizi, 1'den başlayarak. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Belirtilen boyutta bir sunumun tüm slaytları için Thumbnail Image nesneleri döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff seçenekleri. |
| image_size | [`Size`](/slides/python-net/tr/aspose.slides/size) | Oluşturulacak görüntünün boyutu. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Özel ölçeklendirme ile bir sunumun tüm slaytları için Thumbnail Image nesneleri döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff seçenekleri. |
| scale_x | **float** | Bu Thumbnail'i x ekseninde ölçeklendirmek için kullanılan değer. |
| scale_y | **float** | Bu Thumbnail'i y ekseninde ölçeklendirmek için kullanılan değer. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Belirtilen slaytlar için belirtilen boyutta Thumbnail Image nesneleri döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff seçenekleri. |
| slides | **List[int]** | Slayt konumlarını içeren dizi, 1'den başlayarak. |
| image_size | [`Size`](/slides/python-net/tr/aspose.slides/size) | Oluşturulacak görüntünün boyutu. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Belirtilen slaytlar için özel ölçeklendirme ile Thumbnail Image nesneleri döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff seçenekleri. |
| slides | **List[int]** | Slayt konumlarını içeren dizi, 1'den başlayarak. |
| scale_x | **float** | Bu Thumbnail'i x ekseninde ölçeklendirmek için kullanılan değer. |
| scale_y | **float** | Bu Thumbnail'i y ekseninde ölçeklendirmek için kullanılan değer. |



### Ayrıca Bakınız
* sınıf [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions)
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* sınıf [`Size`](/slides/python-net/tr/aspose.slides/size)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)