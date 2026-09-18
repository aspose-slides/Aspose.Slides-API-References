---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/picturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler.

### Döndürür

Bir **bool** döndürür; sıkıştırma işleminin başarılı olup olmadığını gösterir. Görüntü yeniden boyutlandırıldıysa veya kırpıldıysa **True**, aksi takdirde **False** döner.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Doğru ise, yöntem görüntünün kırpılmış alanlarını kaldıracak ve böylece boyutunu daha da azaltabilir. |
| resolution | [`PicturesCompression`](/slides/python-net/tr/aspose.slides.export/picturescompression) | Sıkıştırma için hedef çözünürlük, [`PicturesCompression`](/slides/python-net/tr/aspose.slides.export/picturescompression) enum değerinden belirtilir. |

### Açıklamalar

Bu yöntem, görüntünün boyutunu ve çözünürlüğünü PowerPoint'in "Picture Format -> Compress Pictures" özelliğine benzer şekilde değiştirir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Çözünürlük geçerli bir değer olmadığında ortaya çıkar. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Şekil boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak, kırpılmış alanları da siler.

### Döndürür

Bir **bool** döndürür; sıkıştırma işleminin başarılı olup olmadığını gösterir. Görüntü yeniden boyutlandırıldıysa veya kırpıldıysa **True**, aksi takdirde **False** döner.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | Doğru ise, yöntem görüntünün kırpılmış alanlarını kaldıracak ve böylece boyutunu daha da azaltabilir. |
| resolution | **float** | Hedef çözünürlük DPI cinsindendir. Bu değer pozitif olmalı ve görüntünün nasıl yeniden boyutlandırılacağını tanımlar. |

### Açıklamalar

Bu yöntem, görüntünün boyutunu ve çözünürlüğünü PowerPoint'in "Picture Format -> Compress Pictures" özelliğine benzer şekilde değiştirir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Çözünürlük pozitif bir değer olmadığında ortaya çıkar. |



### Ayrıca Bakınız
* sınıf [`PictureFillFormat`](/slides/python-net/tr/aspose.slides/picturefillformat)
* enum [`PicturesCompression`](/slides/python-net/tr/aspose.slides.export/picturescompression)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)