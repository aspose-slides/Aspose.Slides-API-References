---
title: GetLinesCount()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá počet řádků v odstavci.
type: docs
weight: 118
url: /cs/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() metoda

Získá počet řádků v odstavci.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```

### Návratová hodnota

Počet řádků v odstavci
## Poznámky

Příklad:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## Viz také

* Třída [Paragraph](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)