---
title: AddModernComment()
second_title: Aspose.Slides for C++ API Referansı
description: Bir koleksiyonun sonuna yeni modern yorum ekler.
type: docs
weight: 66
url: /tr/aspose.slides/commentcollection/addmoderncomment/
---
## CommentCollection::AddModernComment(System::String, System::SharedPtr\<ISlide\>, System::SharedPtr\<IShape\>, System::Drawing::PointF, System::DateTime) metod

Bir koleksiyonun sonuna yeni modern yorum ekler.

```cpp
System::SharedPtr<IModernComment> Aspose::Slides::CommentCollection::AddModernComment(System::String text, System::SharedPtr<ISlide> slide, System::SharedPtr<IShape> shape, System::Drawing::PointF position, System::DateTime creationTime) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Yeni modern yorumun düz metni. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) bir sunumda yeni modern yorum eklemek için. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | [Shape](../../shape/) bir slaytta yeni modern yorumun ilişkilendirildiği. |
| position | [System::Drawing::PointF](../../../system.drawing/pointf/) | Yeni modern yorumun ekleneceği slayttaki konum. |
| creationTime | [System::DateTime](../../../system/datetime/) | Modern yorumun oluşturulma zamanı. |

### Dönüş Değeri

Eklenen modern yorum.

## Açıklamalar




```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slides()->idx_get(0);

auto newAuthor = pres->get_CommentAuthors()->AddAuthor(u"Some Author", u"SA");
newAuthor->get_Comments()->AddModernComment(u"This is modern comment", slide, nullptr, PointF(100.0f, 100.0f), DateTime::get_Now());

pres->Save(u"output.pptx", SaveFormat::Pptx);
```




## Diğer

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IModernComment](../../imoderncomment/)
* Sınıf [String](../../../system/string/)
* Sınıf [ISlide](../../islide/)
* Sınıf [IShape](../../ishape/)
* Sınıf [PointF](../../../system.drawing/pointf/)
* Sınıf [DateTime](../../../system/datetime/)
* Sınıf [CommentCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)