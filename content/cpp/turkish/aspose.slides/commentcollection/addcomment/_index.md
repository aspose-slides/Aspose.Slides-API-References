---
title: AddComment()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun sonuna yeni bir yorum ekler.
type: docs
weight: 53
url: /tr/aspose.slides/commentcollection/addcomment/
---
## CommentCollection::AddComment(System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metot

Koleksiyonun sonuna yeni bir yorum ekler.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::AddComment(System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Yeni bir yorumun düz metni. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) bir sunumda yeni yorumun ekleneceği yer. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Yeni bir yorumun ekleneceği slayttaki konum. |
| creationTime | [System::DateTime](../../../system/datetime/) | Yorumun oluşturulma zamanı. |

### Dönüş Değeri

Eklenen yorum.

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IComment](../../icomment/)
* Sınıf [String](../../../system/string/)
* Sınıf [ISlide](../../islide/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [CommentCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)