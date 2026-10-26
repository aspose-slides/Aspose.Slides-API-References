---
title: HighlightRegex()
second_title: Aspose.Slides pro C++ referenci API
description: Zvýrazní všechny výskyty regulárního výrazu zadanou barvou.
type: docs
weight: 157
url: /cs/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) metoda

Zvýrazní všechny výskyty regulárního výrazu zadanou barvou.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Text regulárního výrazu pro získání textu k zvýraznění. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva pro zvýraznění textu. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Možnosti zvýrazňování. |

## Poznámky

Zastaralé:   Použijte místo toho metodu HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback). Metoda bude odstraněna po vydání verze 24.10.

Následující ukázka kódu ukazuje, jak zvýraznit text v [TextFrame](../) pomocí regulárního výrazu. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// zvýrazňuje všechna slova, která mají 10 a více znaků
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metoda

Zvýrazní všechny výskyty regulárního výrazu zadanou barvou.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Regulární výraz [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pro získání řetězců k zvýraznění. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva pro zvýraznění textu. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../ifindresultcallback/). |

## Poznámky


Následující ukázka kódu ukazuje, jak zvýraznit text v [TextFrame](../) pomocí regulárního výrazu. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// zvýrazňuje všechna slova, která mají 10 a více znaků
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Color](../../../system.drawing/color/)
* Třída [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Třída [TextFrame](../)
* Třída [Regex](../../../system.text.regularexpressions/regex/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)