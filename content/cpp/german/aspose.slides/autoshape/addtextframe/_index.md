---
title: AddTextFrame()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt einer Form einen neuen TextFrame hinzu. Wenn die Form bereits einen TextFrame hat, wird ihr Text einfach geändert.
type: docs
weight: 66
url: /de/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) Methode

Fügt einer Form ein neues [TextFrame](../../textframe/) hinzu. Wenn die Form bereits [TextFrame](../../textframe/) hat, ändert sie einfach deren Text.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Standardtext für ein neues [TextFrame](../../textframe/). |
## Anmerkungen

Der folgende Beispielcode zeigt, wie man Wasserzeichen-Text in PowerPoint [Presentation](../../presentation/) hinzufügt.
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
Das folgende Beispiel zeigt, wie man ein Textfeld auf [Slide](../../slide/) erstellt.
```cpp
// Instanziert die Präsentation
auto pres = System::MakeObject<Presentation>();

// Holt die erste Folie der Präsentation
auto slide = pres->get_Slides()->idx_get(0);
// Fügt eine AutoShape mit dem Typ Rectangle hinzu
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Fügt dem Rectangle ein TextFrame hinzu
shape->AddTextFrame(u" ");
// Greift auf das TextFrame zu
auto txtFrame = shape->get_TextFrame();
// Erstellt das Paragraph-Objekt für das TextFrame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Erstellt ein Portion-Objekt für das Paragraph
auto portion = para->get_Portions()->idx_get(0);
// Setzt den Text
portion->set_Text(u"Aspose TextBox");
// Speichert die Präsentation auf dem Datenträger
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
Das folgende Beispiel zeigt, wie man einer Spalte in ein Textfeld hinzufügt.
```cpp
auto presentation = System::MakeObject<Presentation>();

// Holt die erste Folie der Präsentation
auto slide = presentation->get_Slides()->idx_get(0);
// Fügt eine AutoShape mit dem Typ Rectangle hinzu
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Fügt dem Rectangle ein TextFrame hinzu
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Holt das Textformat des TextFrames
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Legt die Anzahl der Spalten im TextFrame fest
format->set_ColumnCount(3);
// Legt den Abstand zwischen den Spalten fest
format->set_ColumnSpacing(10);
// Speichert die Präsentation
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrame](../../itextframe/)
* Klasse [String](../../../system/string/)
* Klasse [AutoShape](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)