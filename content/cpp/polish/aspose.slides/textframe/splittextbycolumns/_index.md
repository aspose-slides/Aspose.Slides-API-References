---
title: SplitTextByColumns()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dzieli treść tekstową ITextFrame na tablicę łańcuchów znaków, gdzie każdy element odpowiada osobnej kolumnie tekstowej w ramce.
type: docs
weight: 144
url: /pl/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() metoda


Dzieli treść tekstową [ITextFrame](../../itextframe/) na tablicę łańcuchów znaków, 

 gdzie każdy element odpowiada osobnej kolumnie tekstowej w ramach ramki.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### Wartość zwracana

Tablica łańcuchów znaków, gdzie każdy łańcuch reprezentuje treść tekstową określonej kolumny 

 w [ITextFrame](../../itextframe/).
## Uwagi



Jeśli ramka tekstowa nie zawiera wielu kolumn, zwrócona tablica będzie miała pojedynczy element 

 zawierający cały tekst. 

 Puste kolumny będą reprezentowane jako puste łańcuchy znaków w tablicy. 

Poniższy przykład pokazuje, jak używać [TextFrame::SplitTextByColumns](./): 
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
* Klasa [String](../../../system/string/)
* Klasa [TextFrame](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)