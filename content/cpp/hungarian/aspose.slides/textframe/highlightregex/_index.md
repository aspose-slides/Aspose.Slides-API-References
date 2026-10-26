---
title: HighlightRegex()
second_title: Aspose.Slides C++ API Referencia
description: Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.
type: docs
weight: 157
url: /hu/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metódus


Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | A reguláris kifejezés szövege a kiemelni kívánt szöveghez. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használandó szín. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Kiemelési beállítások. |
## Megjegyzések


Elavult
:   Használja helyette a HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) metódust. A metódus eltávolításra kerül a 24.10-es verzió kiadása után.


A következő kódminta bemutatja, hogyan lehet kiemelni a szöveget egy [TextFrame](../)-ban reguláris kifejezéssel. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// az összes 10 vagy több karakterből álló szó kiemelése
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metódus


Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | A reguláris kifejezés [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) a kiemelendő karakterláncokhoz. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | A szöveg kiemeléséhez használandó szín. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | A visszahívási objektum a keresési eredmények [IFindResultCallback](../../ifindresultcallback/) fogadásához. |
## Megjegyzések



A következő kódminta bemutatja, hogyan lehet kiemelni a szöveget egy [TextFrame](../)-ban reguláris kifejezéssel. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// az összes 10 vagy több karakterből álló szó kiemelése
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [TextFrame](../)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)