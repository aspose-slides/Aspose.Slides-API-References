---
title: SplitTextByColumns()
second_title: Aspose.Slides voor C++ API-referentie
description: Splits de tekstinhoud van de ITextFrame in een array van strings, waarbij elk element overeenkomt met een aparte tekstkolom binnen het frame.
type: docs
weight: 144
url: /nl/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() methode


Splits de tekstinhoud van de [ITextFrame](../../itextframe/) in een array van strings, 

 waarbij elk element overeenkomt met een aparte tekstkolom binnen het frame.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### Retourwaarde

Een array van strings, waarbij elke string de tekstinhoud van een specifieke kolom in de [ITextFrame](../../itextframe/) weergeeft.

## Opmerkingen



Als het tekstframe geen meerdere kolommen bevat, zal de geretourneerde array één element hebben dat de volledige tekst bevat. 

Lege kolommen zullen in de array worden weergegeven als lege strings. 

Het volgende voorbeeld toont hoe [TextFrame::SplitTextByColumns](./) te gebruiken: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Haal de eerste vorm op de dia op en cast deze naar ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Splits de tekstframe-inhoud in kolommen
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print de tekst van elke kolom naar de console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)