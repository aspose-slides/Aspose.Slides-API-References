---
title: SplitTextByColumns()
second_title: Aspose.Slides voor C++ API-referentie
description: Splitst de tekstinhoud van de ITextFrame in een array van strings, waarbij elk element overeenkomt met een aparte tekstkolom binnen het frame.
type: docs
weight: 118
url: /nl/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() methode


Splitst de tekstinhoud van de [ITextFrame](../) in een array van strings, 
 waarbij elk element overeenkomt met een aparte tekstkolom binnen het frame.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Retourwaarde

Een array van strings, waarbij elke string de tekstinhoud van een specifieke kolom weergeeft 
 in de [ITextFrame](../).
## Opmerkingen



Als het tekstframe geen meerdere kolommen bevat, zal de geretourneerde array één enkel element hebben 
 die de volledige tekst bevat. 
 Lege kolommen zullen als lege strings in de array worden weergegeven. 
Het volgende voorbeeld toont hoe [ITextFrame::SplitTextByColumns](./) te gebruiken: 
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
* Klasse [String](../../../system/string/)
* Klasse [ITextFrame](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)