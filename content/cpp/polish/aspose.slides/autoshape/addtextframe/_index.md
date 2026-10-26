---
title: AddTextFrame()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaje nową TextFrame do kształtu. Jeśli kształt już ma TextFrame, po prostu zmienia jego tekst.
type: docs
weight: 66
url: /pl/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) metoda


Dodaje nowy [TextFrame](../../textframe/) do kształtu. Jeśli kształt już posiada [TextFrame](../../textframe/), po prostu zmienia jego tekst.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Domyślny tekst dla nowego [TextFrame](../../textframe/). |
## Uwagi



Poniższy przykładowy kod pokazuje, jak dodać tekst znaku wodnego w PowerPoint [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 Poniższy przykład pokazuje, jak utworzyć Text Box na [Slide](../../slide/).
```cpp
// Tworzy obiekt Presentation
auto pres = System::MakeObject<Presentation>();

// Pobiera pierwszy slajd w prezentacji
auto slide = pres->get_Slides()->idx_get(0);
// Dodaje AutoShape z typem ustawionym na Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Dodaje TextFrame do prostokąta
shape->AddTextFrame(u" ");
// Uzyskuje dostęp do TextFrame
auto txtFrame = shape->get_TextFrame();
// Tworzy obiekt Paragraph dla TextFrame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Tworzy obiekt Portion dla Paragraph
auto portion = para->get_Portions()->idx_get(0);
// Ustawia tekst
portion->set_Text(u"Aspose TextBox");
// Zapisuje prezentację na dysku
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 Poniższy przykład pokazuje, jak dodać kolumnę w Text Box.
```cpp
auto presentation = System::MakeObject<Presentation>();

// Pobiera pierwszy slajd w prezentacji
auto slide = presentation->get_Slides()->idx_get(0);
// Dodaje AutoShape z typem ustawionym na Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Dodaje TextFrame do prostokąta
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Pobiera format tekstu TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Określa liczbę kolumn w TextFrame
format->set_ColumnCount(3);
// Określa odstęp pomiędzy kolumnami
format->set_ColumnSpacing(10);
// Zapisuje prezentację
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ITextFrame](../../itextframe/)
* Klasa [String](../../../system/string/)
* Klasa [AutoShape](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)