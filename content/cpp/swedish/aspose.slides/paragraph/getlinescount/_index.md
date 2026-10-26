---
title: GetLinesCount()
second_title: Aspose.Slides för C++ API-referens
description: Hämta antalet linjer i ett stycke.
type: docs
weight: 118
url: /sv/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() metod


Hämta antalet linjer i ett stycke.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```


### Returvärde

Antal linjer i ett stycke
## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## Se även

* Klass [Paragraph](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)