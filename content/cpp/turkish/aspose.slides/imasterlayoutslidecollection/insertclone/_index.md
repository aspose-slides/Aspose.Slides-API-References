---
title: InsertClone()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bir yerleşim slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler.
type: docs
weight: 14
url: /tr/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metot


Belirtilen bir yerleşim slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni slaytın indeksi. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klonlamak için. |

### Dönüş Değeri

Ekleme yapılan slayt.

## Açıklamalar



Yeni yerleşim, bu yerleşim slaytları koleksiyonu için ana master slaytla bağlantılı olacaktır. Bu, PowerPoint'te \"Use Destination Theme\" seçeneğiyle yapılan kopyala/yapıştırın bir benzeri gibidir. 

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ILayoutSlide](../../ilayoutslide/)
* Sınıf [IMasterLayoutSlideCollection](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)