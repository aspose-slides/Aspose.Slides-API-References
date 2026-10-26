---
title: Remove()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyondan bir yerleşimi kaldırır.
type: docs
weight: 66
url: /tr/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) yöntemi

Koleksiyondan bir yerleşimi kaldırır.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Koleksiyondan kaldırılacak yerleşim slaytı. |
## Açıklamalar

1) PptxEditException'ın fırlatılmasını önlemek için önce layout'un HasDependingSlides özelliğini kontrol edin. 2) Kodu basitleştirmek için aynı zamanda [ILayoutSlide::Remove](../../ilayoutslide/remove/) yöntemini de kullanabilirsiniz. 
## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ILayoutSlide](../../ilayoutslide/)
* Sınıf [LayoutSlideCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)