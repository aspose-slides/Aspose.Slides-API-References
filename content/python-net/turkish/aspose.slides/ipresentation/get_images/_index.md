---
title: get_images method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Renderleme seçenekleri. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Belirtilen slaytlar için Thumbnail Bitmap nesnelerini döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, slides):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Renderleme seçenekleri. |
| slides | **List[int]** | 1'den başlayan slayt konumlarını içeren Array. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Belirtilen boyutta bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Renderleme seçenekleri. |
| image_size | [`Size`](/slides/python-net/tr/aspose.slides/size) | Oluşturulacak görüntünün boyutu. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Özel ölçekleme ile bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Renderleme seçenekleri. |
| scale_x | **float** | Bu Thumbnail'i x ekseni yönünde ölçeklendiren değer. |
| scale_y | **float** | Bu Thumbnail'i y ekseni yönünde ölçeklendiren değer. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
Belirtilen slaytlar için belirtilen boyutta Thumbnail Image nesnelerini döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Renderleme seçenekleri. |
| slides | **List[int]** | 1'den başlayan slayt konumlarını içeren Array. |
| image_size | [`Size`](/slides/python-net/tr/aspose.slides/size) | Oluşturulacak görüntünün boyutu. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Belirtilen slaytlar için özel ölçekleme ile Thumbnail Image nesnelerini döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Renderleme seçenekleri. |
| slides | **List[int]** | 1'den başlayan slayt konumlarını içeren Array. |
| scale_x | **float** | Bu Thumbnail'i x ekseni yönünde ölçeklendiren değer. |
| scale_y | **float** | Bu Thumbnail'i y ekseni yönünde ölçeklendiren değer. |



### Diğer Bağlantılar
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* sınıf [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions)
* sınıf [`Size`](/slides/python-net/tr/aspose.slides/size)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)