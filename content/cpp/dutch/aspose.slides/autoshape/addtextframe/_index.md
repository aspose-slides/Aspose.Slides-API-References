---
title: AddTextFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuw TextFrame toe aan een vorm. Als de vorm al een TextFrame heeft, wordt de tekst eenvoudig gewijzigd.
type: docs
weight: 66
url: /nl/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) methode


Voegt een nieuwe [TextFrame](../../textframe/) toe aan een vorm. Als de vorm al [TextFrame](../../textframe/) heeft, wordt de tekst eenvoudig gewijzigd.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Standaardtekst voor een nieuwe [TextFrame](../../textframe/). |
## Opmerkingen



De volgende voorbeeldcode laat zien hoe je watermerktekst toevoegt in PowerPoint [Presentation](../../presentation/). 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 Het volgende voorbeeld laat zien hoe je een tekstvak maakt op [Slide](../../slide/). 
```cpp
// Instantieert Presentatie
auto pres = System::MakeObject<Presentation>();

// Haalt de eerste dia op in de presentatie
auto slide = pres->get_Slides()->idx_get(0);
// Voegt een AutoShape toe met als type Rechthoek
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Voegt TextFrame toe aan de Rechthoek
shape->AddTextFrame(u" ");
// Toegang tot het tekstframe
auto txtFrame = shape->get_TextFrame();
// Maakt het Paragraph-object voor het tekstframe
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Maakt een Portion-object voor de alinea
auto portion = para->get_Portions()->idx_get(0);
// Stelt de tekst in
portion->set_Text(u"Aspose TextBox");
// Slaat de presentatie op naar schijf
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 Het volgende voorbeeld laat zien hoe je een kolom toevoegt in een tekstvak. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Haalt de eerste dia op in de presentatie
auto slide = presentation->get_Slides()->idx_get(0);
// Voegt een AutoShape toe met als type Rechthoek
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Voegt TextFrame toe aan de Rechthoek
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Haalt het tekstformaat op van TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Bepaalt het aantal kolommen in TextFrame
format->set_ColumnCount(3);
// Bepaalt de afstand tussen kolommen
format->set_ColumnSpacing(10);
// Slaat de presentatie op
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITextFrame](../../itextframe/)
* Klasse [String](../../../system/string/)
* Klasse [AutoShape](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)