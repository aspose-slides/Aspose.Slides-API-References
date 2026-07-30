---
title: HighlightRegex()
second_title: Aspose.Slides pro C++ referenci API
description: Zvýrazní všechny shody regulárního výrazu zadanou barvou.
type: docs
weight: 131
url: /cs/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metoda

Zvýrazňuje všechny shody regulárního výrazu zadanou barvou.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Regulární výraz [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pro získání řetězců ke zvýraznění. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva pro zvýraznění textu. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../ifindresultcallback/). |
## Poznámky

Následující ukázka kódu ukazuje, jak zvýraznit text v [TextFrame](../../textframe/) pomocí regulárního výrazu. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// zvýraznění všech slov s 10 a více znaky
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metoda

Zvýrazňuje všechny shody regulárního výrazu zadanou barvou.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Text regulárního výrazu pro získání textu k zvýraznění. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva pro zvýraznění textu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Možnosti zvýrazňování. |
Zastaralé
:   Použijte místo toho metodu HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback). Metoda bude odstraněna po vydání verze 24.10.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [Color](../../../system.drawing/color/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [ITextFrame](../)
* Class [String](../../../system/string/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)