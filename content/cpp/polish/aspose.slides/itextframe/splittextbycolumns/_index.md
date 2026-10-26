---
title: SplitTextByColumns()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Dzieli zawartość tekstową ITextFrame na tablicę łańcuchów znaków, gdzie każdy element odpowiada oddzielnej kolumnie tekstowej w ramce.
type: docs
weight: 118
url: /pl/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() metoda


Dzieli zawartość tekstową [ITextFrame](../) na tablicę łańcuchów znaków, 

 gdzie każdy element odpowiada oddzielnej kolumnie tekstowej w ramce.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Wartość zwracana

Tablica łańcuchów znaków, gdzie każdy łańcuch reprezentuje zawartość tekstową konkretnej kolumny 

 w [ITextFrame](../).
## Uwagi



Jeśli ramka tekstowa nie zawiera wielu kolumn, zwrócona tablica będzie miała pojedynczy element 

 zawierający pełny tekst. 

 Puste kolumny będą reprezentowane jako puste łańcuchy znaków w tablicy. 

Poniższy przykład pokazuje, jak używać [ITextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Pobierz pierwszy kształt na slajdzie i rzutuj go na ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Podziel zawartość ramki tekstowej na kolumny
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Wypisz tekst każdej kolumny na konsolę
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)