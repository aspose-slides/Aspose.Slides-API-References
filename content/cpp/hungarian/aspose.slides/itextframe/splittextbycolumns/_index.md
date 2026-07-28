---
title: SplitTextByColumns()
second_title: Aspose.Slides C++ API Referenciája
description: Felosztja az ITextFrame szövegtartalmát egy karakterláncok tömbjére, ahol minden elem a keretben lévő különálló szövegoszlopnak felel meg.
type: docs
weight: 118
url: /hu/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() metódus


Felosztja a [ITextFrame](../) szövegtartalmát egy karakterláncok tömbjére,

 ahol minden elem a keretben lévő különálló szövegoszlopnak felel meg.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Visszatérési érték

Egy karakterláncok tömbje, ahol minden karakterlánc egy adott oszlop szövegtartalmát képviseli

 a [ITextFrame](../)-ben.

## Megjegyzések



Ha a szövegkeret nem tartalmaz több oszlopot, a visszaadott tömb egyetlen elemet fog tartalmazni

 amely a teljes szöveget tartalmazza.

Az üres oszlopok a tömbben üres karakterláncként jelennek meg.

A következő példában bemutatjuk, hogyan használható a [ITextFrame::SplitTextByColumns](./):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Szerezze meg az első alakzatot a dián, és ITextFrame típusra castolja
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Felosztja a szövegkeret tartalmát oszlopokra
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Kiírja minden oszlop szövegét a konzolra
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)