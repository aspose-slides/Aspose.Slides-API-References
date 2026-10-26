---
title: SplitTextByColumns()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Rozdělí textový obsah ITextFrame na pole řetězců, kde každý prvek odpovídá samostatnému sloupci textu v rámci rámce.
type: docs
weight: 144
url: /cs/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() metoda


Rozděluje textový obsah [ITextFrame](../../itextframe/) na pole řetězců, 
 kde každý prvek odpovídá samostatnému sloupci textu v rámci rámce.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### Návratová hodnota

Pole řetězců, kde každý řetězec představuje textový obsah konkrétního sloupce v [ITextFrame](../../itextframe/).

## Poznámky



Pokud textový rámec neobsahuje více sloupců, vrácené pole bude mít jediný prvek obsahující celý text. 
Prázdné sloupce budou v poli reprezentovány prázdnými řetězci. 
Následující příklad ukazuje, jak použít [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Získá první tvar na snímku a přetypuje jej na ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Rozdělí obsah textového rámce do sloupců
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Vytiskne text každého sloupce do konzole
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [TextFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)