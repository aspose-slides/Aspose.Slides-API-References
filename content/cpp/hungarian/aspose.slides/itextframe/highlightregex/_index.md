---
title: HighlightRegex()
second_title: Aspose.Slides for C++ API referenciája
description: Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.
type: docs
weight: 131
url: /hu/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metódus

Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A reguláris kifejezés [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) a kiemelendő karakterláncok lekéréséhez. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használt szín. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények [IFindResultCallback](../../ifindresultcallback/) fogadásához. |

## Megjegyzés

A következő kódrészlet bemutatja, hogyan lehet kiemelni a szöveget egy [TextFrame](../../textframe/)-ban reguláris kifejezéssel. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metódus

Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | A reguláris kifejezés szövege a kiemelendő szöveg megszerzéséhez. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használt szín. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Kiemelési beállítások. |

Elavult
:   Használja a HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) metódust helyette. A metódus a 24.10-es verzió kiadása után kerül eltávolításra.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Regex](../../../system.text.regularexpressions/regex/)
* Osztály [Color](../../../system.drawing/color/)
* Osztály [IFindResultCallback](../../ifindresultcallback/)
* Osztály [ITextFrame](../)
* Osztály [String](../../../system/string/)
* Osztály [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)