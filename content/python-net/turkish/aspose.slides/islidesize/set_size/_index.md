---
title: set_size method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Slayt boyutunu tipe göre ayarlar ve mevcut içeriği ölçeklendirir.


```python
def set_size(self, type, scale_type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/tr/aspose.slides/slidesizetype) | Uygulanacak önceden tanımlanmış slayt boyutu. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/tr/aspose.slides/slidesizescaletype) | Kullanılacak içerik ölçekleme modu. |

### Açıklamalar
[`SlideSizeType.CUSTOM`](/slides/python-net/tr/aspose.slides/slidesizetype/CUSTOM) dışındaki herhangi bir değer atamak, seçilen tipe göre [`ISlideSize.size`](/slides/python-net/tr/aspose.slides/islidesize/size)'ı ayarlar
            ve [`ISlideSize.orientation`](/slides/python-net/tr/aspose.slides/islidesize/orientation)'ı korur.


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçeklendirir.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | **float** | Yeni slayt genişliği, nokta cinsinden. |
| height | **float** | Yeni slayt yüksekliği, nokta cinsinden. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/tr/aspose.slides/slidesizescaletype) | Kullanılacak içerik ölçekleme modu. |

### Açıklamalar
Bu, [`ISlideSize.type`](/slides/python-net/tr/aspose.slides/islidesize/type) özelliğini [`SlideSizeType.CUSTOM`](/slides/python-net/tr/aspose.slides/slidesizetype/CUSTOM)
            ve [`ISlideSize.orientation`](/slides/python-net/tr/aspose.slides/islidesize/orientation)'i ayarlar.



### Ayrıca Bakınız
* sınıf [`ISlideSize`](/slides/python-net/tr/aspose.slides/islidesize)
* enum [`SlideSizeScaleType`](/slides/python-net/tr/aspose.slides/slidesizescaletype)
* enum [`SlideSizeType`](/slides/python-net/tr/aspose.slides/slidesizetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)