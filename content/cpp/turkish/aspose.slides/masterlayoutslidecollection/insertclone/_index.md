---
title: InsertClone()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen yerleşim slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler.
type: docs
weight: 14
url: /tr/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) method

Belirtilen yerleşim slaytının bir kopyasını koleksiyonun belirtilen konumuna ekler.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni slayın indeksi. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) kopyalamak için. |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar

Yeni yerleşim, bu yerleşim slaytları koleksiyonu için üst ana slayt ile bağlantılı olacaktır. Bu nedenle, PowerPoint'te \"Use Destination Theme\" seçeneği ile kopyala/yapıştır işleminin bir analoğudur.

## Diğer

* Tip Tanımlaması [SharedPtr](../../../system/sharedptr/)
* Sınıf [ILayoutSlide](../../ilayoutslide/)
* Sınıf [MasterLayoutSlideCollection](../)
* AdAlanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)