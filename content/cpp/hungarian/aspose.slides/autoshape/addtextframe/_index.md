---
title: AddTextFrame()
second_title: Aspose.Slides C++ API referencia
description: Új TextFrame-et ad egy alakzathoz. Ha az alakzat már rendelkezik TextFrame-mel, akkor egyszerűen megváltoztatja a szövegét.
type: docs
weight: 66
url: /hu/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) metódus


Új [TextFrame](../../textframe/) hozzáadása egy alakzathoz. Ha az alakzat már rendelkezik [TextFrame](../../textframe/)-val, akkor egyszerűen megváltoztatja a szövegét.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Alapértelmezett szöveg egy új [TextFrame](../../textframe/) számára. |
## Megjegyzések



Az alábbi példakód bemutatja, hogyan lehet vízjel szöveget hozzáadni a PowerPoint [Presentation](../../presentation/)-ben. 
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
 Az alábbi példa bemutatja, hogyan lehet szövegdobozt létrehozni a [Slide](../../slide/)-on. 
```cpp
// Példányosítja a Presentation objektumot
auto pres = System::MakeObject<Presentation>();

// Lekéri az első diát a prezentációból
auto slide = pres->get_Slides()->idx_get(0);
// Hozzáad egy AutoShape-et, amelynek típusa Téglalap
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// Szövegkeretet (TextFrame) ad a téglalaphoz
shape->AddTextFrame(u" ");
// Hozzáfér a szövegkerethez
auto txtFrame = shape->get_TextFrame();
// Létrehozza a Paragraph objektumot a szövegkerethez
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// Létrehozza a Portion objektumot a bekezdéshez
auto portion = para->get_Portions()->idx_get(0);
// Beállítja a szöveget
portion->set_Text(u"Aspose TextBox");
// Mentse a prezentációt a lemezen
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
 Az alábbi példa bemutatja, hogyan lehet oszlopot hozzáadni a szövegdobozba. 
```cpp
auto presentation = System::MakeObject<Presentation>();

// Lekéri az első diát a prezentációból
auto slide = presentation->get_Slides()->idx_get(0);
// Hozzáad egy AutoShape-et, amelynek típusa Rectangle
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// Szövegkeretet ad a Rectangle-hez
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// Lekéri a TextFrame szövegformátumát
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// Megadja a TextFrame oszlopainak számát
format->set_ColumnCount(3);
// Megadja az oszlopok közötti távolságot
format->set_ColumnSpacing(10);
// Mentse a prezentációt
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ITextFrame](../../itextframe/)
* Osztály [String](../../../system/string/)
* Osztály [AutoShape](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)