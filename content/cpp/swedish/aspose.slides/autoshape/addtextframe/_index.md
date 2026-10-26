---
title: AddTextFrame()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en ny TextFrame i en shape. Om shape redan har TextFrame ändras bara dess text.
type: docs
weight: 66
url: /sv/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) method


Lägger till en ny [TextFrame](../../textframe/) till en shape. Om shape redan har [TextFrame](../../textframe/) ändras bara dess text.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Standardtext för en ny [TextFrame](../../textframe/). |
## Anmärkningar



Följande exempel visar hur man lägger till vattenstämpeltext i PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 Följande exempel visar hur man skapar en Textruta på [Slide](../../slide/). 
```cpp
// Instanserar Presentation
auto pres = System::MakeObject<Presentation>();

// Hämtar den första bilden i presentationen
auto slide = pres->get_Slides()->idx_get(0);
// Lägger till en AutoShape med typ satt till Rektangel
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Lägger till TextFrame till Rektangeln
shape->AddTextFrame(u" ");
// Åtkommer textramen
auto txtFrame = shape->get_TextFrame();
// Skapar Paragraph-objektet för textramen
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Skapar ett Portion-objekt för stycket
auto portion = para->get_Portions()->idx_get(0);
// Sätter texten
portion->set_Text(u"Aspose TextBox");
// Sparar presentationen till disk
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 Följande exempel visar hur man lägger till en kolumn i en textruta. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Hämtar den första bilden i presentationen
auto slide = presentation->get_Slides()->idx_get(0);
// Lägger till en AutoShape med typ satt till Rektangel
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Lägger till TextFrame till Rektangeln
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Hämtar textformatet för TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Anger antalet kolumner i TextFrame
format->set_ColumnCount(3);
// Anger avståndet mellan kolumnerna
format->set_ColumnSpacing(10);
// Sparar presentationen
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ITextFrame](../../itextframe/)
* Klass [String](../../../system/string/)
* Klass [AutoShape](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)