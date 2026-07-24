---
title: InsertComment()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen konumdaki bir koleksiyona yeni yorum ekler.
type: docs
weight: 79
url: /tr/aspose.slides/commentcollection/insertcomment/
---
## CommentCollection::InsertComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::Drawing::PointF, System::DateTime) metod

Belirtilen konumdaki bir koleksiyona yeni yorum ekler.

```cpp
System::SharedPtr<IComment> Aspose::Slides::CommentCollection::InsertComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::Drawing::PointF position, System::DateTime creationTime) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yorumun eklenmesi gereken koleksiyondaki öğenin indeksi. |
| text | [System::String](../../../system/string/) | Yeni yorumun düz metni. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) bir sunumda yeni yorumun ekleneceği yer. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Yeni yorumun ekleneceği slayttaki konum. |
| creationTime | [System::DateTime](../../../system/datetime/) | Yorumun oluşturulma zamanı. |

### Dönüş Değeri

Eklenen yorum.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IComment](../../icomment/)
* Sınıf [String](../../../system/string/)
* Sınıf [ISlide](../../islide/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [CommentCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)