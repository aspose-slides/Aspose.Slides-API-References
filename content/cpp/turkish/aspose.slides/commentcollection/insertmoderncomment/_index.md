---
title: InsertModernComment()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizindeki bir koleksiyona yeni modern yorum ekler.
type: docs
weight: 92
url: /tr/aspose.slides/commentcollection/insertmoderncomment/
---
## CommentCollection::InsertModernComment(int32_t, System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) method


Belirtilen dizindeki bir koleksiyona yeni modern yorum ekler.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::InsertModernComment(int32_t index, System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Modern yorumun eklenmesi gereken koleksiyondaki öğenin indeksi. |
| text | [System::String](../../../system/string/) | Yeni modern yorumun düz metni. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) bir sunumda yeni modern yorumun ekleneceği yer. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) bir slaytta yeni modern yorumun ilişkilendirildiği yer. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Yeni modern yorumun ekleneceği slayttaki konum. |
| creationTime | [System::DateTime](../../../system/datetime/) | Modern yorumun oluşturulma zamanı. |

### Dönüş Değeri

Eklenmiş modern yorum.

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IModernComment](../../imoderncomment/)
* Sınıf [String](../../../system/string/)
* Sınıf [ISlide](../../islide/)
* Sınıf [IShape](../../ishape/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [CommentCollection](../)
* İsim Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)