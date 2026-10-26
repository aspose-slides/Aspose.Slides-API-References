---
title: AddModernComment()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun sonuna yeni modern yorum ekleyin.
type: docs
weight: 27
url: /tr/aspose.slides/icommentcollection/addmoderncomment/
---
## ICommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) yöntemi

Koleksiyonun sonuna yeni modern yorum ekle.

```cpp
virtual System::SharedPtr<IModernComment> Aspose::Slides::ICommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Yeni bir modern yorumun düz metni. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) bir sunumda yeni modern yorumun ekleneceği yerde. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) bir slaytta yeni modern yorumun ilişkilendirildiği. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Yeni modern yorumun ekleneceği slayt üzerindeki konum. |
| creationTime | [System::DateTime](../../../system/datetime/) | Modern yorumun oluşturulma zamanı. |

### Dönüş Değeri

Eklenmiş modern yorum.

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```

## Ayrıca bakınız

* Tip tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IModernComment](../../imoderncomment/)
* Sınıf [String](../../../system/string/)
* Sınıf [ISlide](../../islide/)
* Sınıf [IShape](../../ishape/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [ICommentCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)