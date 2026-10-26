---
title: AddTextFrame()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá nový TextFrame do tvaru. Pokud tvar již obsahuje TextFrame, pak jednoduše změní jeho text.
type: docs
weight: 66
url: /cs/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) metoda

Přidá nový [TextFrame](../../textframe/) do tvaru. Pokud tvar již obsahuje [TextFrame](../../textframe/), pak jednoduše změní jeho text.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Výchozí text pro nový [TextFrame](../../textframe/). |

## Poznámky

Následující ukázkový kód ukazuje, jak přidat vodoznakový text v PowerPointu [Presentation](../../presentation/).
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
Následující příklad ukazuje, jak vytvořit Text Box na [Slide](../../slide/).
```cpp
// Vytvoří instanci Presentation
auto pres = System::MakeObject<Presentation>();

// Získá první snímek v prezentaci
auto slide = pres->get_Slides()->idx_get(0);
// Přidá AutoShape s typem nastaveným na Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Přidá TextFrame do Rectangle
shape->AddTextFrame(u" ");
// Přistupuje k TextFrame
auto txtFrame = shape->get_TextFrame();
// Vytvoří objekt Paragraph pro TextFrame
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Vytvoří objekt Portion pro Paragraph
auto portion = para->get_Portions()->idx_get(0);
// Nastaví text
portion->set_Text(u"Aspose TextBox");
// Uloží prezentaci na disk
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
Následující příklad ukazuje, jak přidat sloupec v Text Boxu.
```cpp
auto presentation = System::MakeObject<Presentation>();

// Získá první snímek v prezentaci
auto slide = presentation->get_Slides()->idx_get(0);
// Přidá AutoShape s typem nastaveným na Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Přidá TextFrame do Rectangle
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Získá formát textu TextFrame
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Určuje počet sloupců v TextFrame
format->set_ColumnCount(3);
// Určuje mezery mezi sloupci
format->set_ColumnSpacing(10);
// Uloží prezentaci
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ITextFrame](../../itextframe/)
* Třída [String](../../../system/string/)
* Třída [AutoShape](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)