---
title: compress_image method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ipicturefillformat/compress_image/
weight: 10
---
## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-asposeslidesexportpicturescompression}
Şeklin boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler.

### Dönüş Değeri

Görüntünün başarıyla sıkıştırılıp sıkıştırılmadığını gösteren bir **bool**. Görüntü yeniden boyutlandırıldıysa veya kırpıldıysa **True**, aksi takdirde **False** döndürülür.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | true ise, yöntem görüntünün kırpılmış alanlarını kaldırır ve bu da boyutunun daha da azalmasına yol açabilir. |
| resolution | [`PicturesCompression`](/slides/python-net/tr/aspose.slides.export/picturescompression) | Sıkıştırma için hedef çözünürlük, [`PicturesCompression`](/slides/python-net/tr/aspose.slides.export/picturescompression) enum değerinden birisi olarak belirtilir. |

### Açıklamalar

Bu yöntem, PowerPoint’ın “Picture Format -> Compress Pictures” özelliğine benzer şekilde görüntünün boyutunu ve çözünürlüğünü değiştirir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Çözünürlük geçerli bir değer değilse fırlatılır. |


## compress_image(self, delete_cropped_areas_of_image, resolution) {#bool-float}
Şeklin boyutuna ve belirtilen çözünürlüğe göre görüntünün boyutunu küçülterek sıkıştırır. İsteğe bağlı olarak kırpılmış alanları da siler.

### Dönüş Değeri

Görüntünün başarıyla sıkıştırılıp sıkıştırılmadığını gösteren bir **bool**. Görüntü yeniden boyutlandırıldıysa veya kırpıldıysa **True**, aksi takdirde **False** döndürülür.



```python
def compress_image(self, delete_cropped_areas_of_image, resolution):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| delete_cropped_areas_of_image | **bool** | true ise, yöntem görüntünün kırpılmış alanlarını kaldırır ve bu da boyutunun daha da azalmasına yol açabilir. |
| resolution | **float** | DPI cinsinden hedef çözünürlük. Bu değer pozitif olmalı ve görüntünün nasıl yeniden boyutlandırılacağını tanımlar. |

### Açıklamalar

Bu yöntem, PowerPoint’ın “Picture Format -> Compress Pictures” özelliğine benzer şekilde görüntünün boyutunu ve çözünürlüğünü değiştirir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Çözünürlük pozitif bir değer olmadığında fırlatılır. |



### İlgili Bağlantılar
* class [`IPictureFillFormat`](/slides/python-net/tr/aspose.slides/ipicturefillformat)
* enumeration [`PicturesCompression`](/slides/python-net/tr/aspose.slides.export/picturescompression)
* module [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)