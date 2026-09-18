---
title: get_images method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
Sunumun tüm slaytları için Image nesnelerini döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff options. |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
Belirtilen slaytlar için Thumbnail Image nesnelerini döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, slides):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
Belirtilen boyutta bütün slaytlar için Thumbnail Image nesnelerini döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff options. |
| image_size | **aspose.slides.Size** | Size of the image to create. |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Özel ölçeklendirme ile bütün slaytlar için Thumbnail Image nesnelerini döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff options. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
Belirtilen slaytlar ve boyut için Thumbnail Image nesnelerini döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, slides, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| image_size | **aspose.slides.Size** | Size of the image to create. |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
Belirtilen slaytlar ve özel ölçeklendirme ile Thumbnail Image nesnelerini döndürür.

### Döndürür

Image nesneleri.



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Tiff options. |
| slides | **List[int]** | Array with slide positions, starting from 1. |
| scale_x | **float** | The value by which to scale this Thumbnail in the x-axis direction. |
| scale_y | **float** | The value by which to scale this Thumbnail in the y-axis direction. |



### İlgili
* sınıf [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions)
* sınıf [`Presentation`](/slides/python-net/tr/aspose.slides/presentation)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)