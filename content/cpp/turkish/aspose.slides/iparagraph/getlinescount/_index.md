---
title: GetLinesCount()
second_title: Aspose.Slides for C++ API Referansı
description: Bir paragraftaki satır sayısını alır.
type: docs
weight: 105
url: /tr/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() yöntemi


Bir paragraftaki satır sayısını alır.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```


### Dönüş Değeri

Lines count in a paragraph
## Açıklamalar


Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## Ayrıca Bakınız

* Sınıf [IParagraph](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)