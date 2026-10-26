---
title: GetLinesCount()
second_title: Aspose.Slides C++ API referencia
description: A bekezdés sorainak számát adja vissza.
type: docs
weight: 105
url: /hu/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() metódus

Visszaadja a sorok számát egy bekezdésben.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```

### Visszatérési érték

A sorok száma egy bekezdésben

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## Lásd még

* Osztály [IParagraph](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)