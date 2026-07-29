---
title: SplitTextByColumns()
second_title: Aspose.Slides för C++ API-referens
description: Delar upp textinnehållet i ITextFrame till en array av strängar, där varje element motsvarar en separat textkolumn i ramen.
type: docs
weight: 144
url: /sv/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() metod

Delar upp textinnehållet i [ITextFrame](../../itextframe/) till en array av strängar, där varje element motsvarar en separat textkolumn i ramen.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### Returvärde

En array av strängar, där varje sträng representerar textinnehållet i en specifik kolumn i [ITextFrame](../../itextframe/).

## Anmärkningar

Om textramen inte innehåller flera kolumner kommer den returnerade arrayen att ha ett enda element som innehåller hela texten. Tomma kolumner kommer att representeras som tomma strängar i arrayen. Följande exempel visar hur man använder [TextFrame::SplitTextByColumns](./):
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Hämta den första formen på bilden och kasta den till ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Dela upp textramens innehåll i kolumner
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Skriv ut varje kolumns text till konsolen
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [TextFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)