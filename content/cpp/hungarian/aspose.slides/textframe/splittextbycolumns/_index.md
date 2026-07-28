---
title: SplitTextByColumns()
second_title: Aspose.Slides C++ API-referencia
description: Felosztja az ITextFrame szövegtartalmát egy karakterláncok tömbjébe, ahol minden elem egy külön szövegoszlopnak felel meg a kereten belül.
type: docs
weight: 144
url: /hu/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() metódus

Felosztja a(z) [ITextFrame](../../itextframe/) szövegtartalmát egy karakterláncok tömbjébe, 

 ahol minden elem egy külön szövegoszlopnak felel meg a kereten belül.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### Visszatérési érték

Egy karakterláncok tömbje, ahol minden karakterlánc egy adott oszlop szövegtartalmát képviseli 

 a(z) [ITextFrame](../../itextframe/)-ben.

## Megjegyzések

Ha a szövegkeret nem tartalmaz több oszlopot, a visszaadott tömb egyetlen elemet fog tartalmazni 

 amely a teljes szöveget tartalmazza. 

 Üres oszlopok üres karakterláncként lesznek ábrázolva a tömbben. 

A következő példa bemutatja, hogyan használható a(z) [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Get the first shape on the slide and cast it to ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Split the text frame content into columns
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print each column's text to the console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [TextFrame](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)