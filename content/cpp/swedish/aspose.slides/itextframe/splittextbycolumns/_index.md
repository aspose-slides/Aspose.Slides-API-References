---
title: SplitTextByColumns()
second_title: Aspose.Slides för C++ API-referens
description: Delar upp textinnehållet i ITextFrame i en array av strängar, där varje element motsvarar en separat textkolumn inom ramen.
type: docs
weight: 118
url: /sv/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() metod


Delar upp textinnehållet i [ITextFrame](../) i en array av strängar, 

 där varje element motsvarar en separat textkolumn inom ramen.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Return Value

En array av strängar, där varje sträng representerar textinnehållet i en specifik kolumn i [ITextFrame](../).
## Remarks



Om textramen inte innehåller flera kolumner, kommer den returnerade arrayen att ha ett enda element som innehåller hela texten. Tomma kolumner kommer att representeras som tomma strängar i arrayen. 

Följande exempel visar hur man använder [ITextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Hämta den första formen på bilden och kasta den till ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Dela upp textramhållandet i kolumner
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Skriv ut varje kolumns text till konsolen
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [ITextFrame](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)