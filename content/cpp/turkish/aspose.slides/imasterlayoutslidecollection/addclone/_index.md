---
title: AddClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen bir düzen slaydının bir kopyasını koleksiyonun sonuna ekler.
type: docs
weight: 1
url: /tr/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metodu

Belirtilen bir düzen slaydının bir kopyasını koleksiyonun sonuna ekler.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) kopyalamak için. |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar

1) Yeni düzen, bu düzen slaytları koleksiyonu için üst ana master slayt ile ilişkili olacaktır. Bu nedenle PowerPoint'te "Use Destination Theme" seçeneğiyle yapılan kopyala/yapıştır işleminin bir benzeridir. 2) Bu yöntemin benzeri, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) yöntemi, [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) özelliği ile erişilir. 

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ILayoutSlide](../../ilayoutslide/)
* Sınıf [IMasterLayoutSlideCollection](../)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)