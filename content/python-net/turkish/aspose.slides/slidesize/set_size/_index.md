---
title: set_size method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Tipine göre slayt boyutunu ayarlar ve mevcut içeriği ölçekler.

```python
def set_size(self, type, scale_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/tr/aspose.slides/slidesizetype) | Uygulanacak önceden tanımlanmış slayt boyutu. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/tr/aspose.slides/slidesizescaletype) | Kullanılacak içerik ölçekleme modu. |

### Açıklamalar

[`SlideSizeType.CUSTOM`](/slides/python-net/tr/aspose.slides/slidesizetype/CUSTOM) dışındaki herhangi bir değerin atanması, seçilen türe göre [`SlideSize.size`](/slides/python-net/tr/aspose.slides/slidesize/size)'yi ayarlar ve [`SlideSize.orientation`](/slides/python-net/tr/aspose.slides/slidesize/orientation)'yi korur.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Slayt boyutlarını açıkça ayarlar ve mevcut içeriği ölçekler.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | **float** | Yeni slayt genişliği, puan cinsinden. |
| height | **float** | Yeni slayt yüksekliği, puan cinsinden. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/tr/aspose.slides/slidesizescaletype) | Kullanılacak içerik ölçekleme modu. |

### Açıklamalar

Bu, [`SlideSize.type`](/slides/python-net/tr/aspose.slides/slidesize/type) özelliğini [`SlideSizeType.CUSTOM`](/slides/python-net/tr/aspose.slides/slidesizetype/CUSTOM)'ye sıfırlar ve [`SlideSize.orientation`](/slides/python-net/tr/aspose.slides/slidesize/orientation)'yi ayarlar.

### İlgili
* sınıf [`SlideSize`](/slides/python-net/tr/aspose.slides/slidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/tr/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/tr/aspose.slides/slidesizetype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)