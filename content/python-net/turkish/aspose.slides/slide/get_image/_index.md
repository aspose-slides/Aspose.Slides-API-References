---
title: get_image method
second_title: Aspose.Slides Python için, .NET aracılığıyla API Referansı
description: 
type: docs
url: /tr/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
Gerçek boyutun %20'si kadar bir Thumbnail Image nesnesi döndürür.


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
Belirtilen boyutta bir Thumbnail Image nesnesi döndürür.

### Döndürür

Image nesnesi.



```python
def get_image(self, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/tr/aspose.slides/size) | Oluşturulacak görüntünün boyutu. |


## get_image(self, options) {#asposeslidesexportitiffoptions}
Belirtilen parametrelerle bir Thumbnail tiff image nesnesi döndürür.

### Döndürür

Image nesnesi.



```python
def get_image(self, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/tr/aspose.slides.export/itiffoptions) | Tiff seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption, NotesCommentsLayoutingOptions olduğu ve NotesPosition özelliği NotesPositions.BottomFull değerini aldığında fırlatılır. |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
Bir Thumbnail Image nesnesi döndürür.

### Döndürür

Image nesnesi.



```python
def get_image(self, options):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Rendering seçenekleri. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition, NotesPositions.BottomFull değerini aldığında fırlatılır. |


## get_image(self, scale_x, scale_y) {#float-float}
Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür.

### Döndürür

IImage nesnesi.



```python
def get_image(self, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scale_x | **float** | Bu Thumbnail'i x ekseni yönünde ölçeklendirecek değer. |
| scale_y | **float** | Bu Thumbnail'i y ekseni yönünde ölçeklendirecek değer. |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
Belirtilen boyutta bir Thumbnail Image nesnesi döndürür.

### Döndürür

Image nesnesi.



```python
def get_image(self, options, image_size):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Rendering seçenekleri. |
| image_size | [`Size`](/slides/python-net/tr/aspose.slides/size) | Oluşturulacak görüntünün boyutu. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption, NotesCommentsLayoutingOptions olduğu ve NotesPosition özelliği NotesPositions.BottomFull değerini aldığında fırlatılır. |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
Özel ölçekleme ile bir Thumbnail Image nesnesi döndürür.

### Döndürür

Bitmap nesneleri.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions) | Rendering seçenekleri. |
| scale_x | **float** | Bu Thumbnail'i x ekseni yönünde ölçeklendirecek değer. |
| scale_y | **float** | Bu Thumbnail'i y ekseni yönünde ölçeklendirecek değer. |

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition, NotesPositions.BottomFull değerini aldığında fırlatılır. |



### Ayrıca Bakınız
* sınıf [`IImage`](/slides/python-net/tr/aspose.slides/iimage)
* sınıf [`IRenderingOptions`](/slides/python-net/tr/aspose.slides.export/irenderingoptions)
* sınıf [`ITiffOptions`](/slides/python-net/tr/aspose.slides.export/itiffoptions)
* sınıf [`Slide`](/slides/python-net/tr/aspose.slides/slide)
* sınıf [`Size`](/slides/python-net/tr/aspose.slides/size)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)