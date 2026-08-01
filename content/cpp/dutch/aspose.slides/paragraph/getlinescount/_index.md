---
title: GetLinesCount()
second_title: Aspose.Slides voor C++ API-referentie
description: Het aantal regels in een alinea ophalen.
type: docs
weight: 118
url: /nl/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() methode


Het aantal regels in een alinea ophalen.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```


### Retourwaarde

Aantal regels in een alinea
## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## Zie ook

* Klasse [Paragraph](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)