---
title: InsertComment()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen dizinde bir koleksiyona yeni yorum ekler.
type: docs
weight: 40
url: /tr/aspose.slides/icommentcollection/insertcomment/
---
## ICommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) method

Belirtilen dizinde bir koleksiyona yeni yorum ekler.

```cpp
virtual System::SharedPtr<IComment> Aspose::Slides::ICommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yorumun ekleneceği koleksiyondaki öğenin dizini. |
| text | [System::String](../../../system/string/) | Yeni yorumun düz metni. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) bir sunumda yeni yorumun ekleneceği yer. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Yorumun ekleneceği slayt üzerindeki konum. |
| creationTime | [System::DateTime](../../../system/datetime/) | Yorumun oluşturulma zamanı. |

### Dönüş Değeri

Eklenmiş yorum.

## Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IComment](../../icomment/)
* Sınıf [String](../../../system/string/)
* Sınıf [ISlide](../../islide/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [ICommentCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)