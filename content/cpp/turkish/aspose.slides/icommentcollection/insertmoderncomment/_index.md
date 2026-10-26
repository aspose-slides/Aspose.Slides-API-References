---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen indekste bir koleksiyona yeni modern yorum ekler.
type: docs
weight: 53
url: /tr/aspose.slides/icommentcollection/insertmoderncomment/
---
## ICommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) yöntem

Belirtilen indekste bir koleksiyona yeni modern yorum ekler.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Modern yorumun eklenmesi gereken bir koleksiyondaki öğenin indeksi. |
| text | [System::String](../../../system/string/) | Yeni modern yorumun düz metni. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) bir sunumda yeni modern yorumun ekleneceği yer. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) bir slaytta yeni modern yorumun ilişkilendirildiği yer. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Yeni modern yorumun ekleneceği slayttaki konum. |
| creationTime | [System::DateTime](../../../system/datetime/) | Modern yorumun oluşturulma zamanı. |

### Dönüş Değeri

Eklenen modern yorum.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IModernComment](../../imoderncomment/)
* Sınıf [String](../../../system/string/)
* Sınıf [ISlide](../../islide/)
* Sınıf [IShape](../../ishape/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [ICommentCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)