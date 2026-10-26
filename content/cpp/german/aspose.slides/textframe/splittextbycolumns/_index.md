---
title: SplitTextByColumns()
second_title: Aspose.Slides für C++ API-Referenz
description: Teilt den Textinhalt des ITextFrame in ein Array von Zeichenfolgen, wobei jedes Element einer separaten Textspalte im Rahmen entspricht.
type: docs
weight: 144
url: /de/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() Methode

Teilt den Textinhalt des [ITextFrame](../../itextframe/) in ein Array von Zeichenfolgen,

 wo jedes Element einer separaten Textspalte im Rahmen entspricht.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### Rückgabewert

Ein Array von Zeichenfolgen, wobei jede Zeichenfolge den Textinhalt einer bestimmten Spalte

 im [ITextFrame](../../itextframe/) darstellt.

## Hinweise



Wenn der Textrahmen nicht mehrere Spalten enthält, hat das zurückgegebene Array ein einziges Element,

 das den gesamten Text enthält. 

Leere Spalten werden im Array als leere Zeichenfolgen dargestellt. 

Das folgende Beispiel zeigt, wie [TextFrame::SplitTextByColumns](./) verwendet wird: 
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

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [TextFrame](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)