---
title: HighlightRegex()
second_title: Aspose.Slides pro C++ API Reference
description: Zvýrazní všechny shody regulárního výrazu pomocí zadané barvy.
type: docs
weight: 508
url: /cs/aspose.slides/presentation/highlightregex/
---
## Presentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) metoda

Zvýrazní všechny shody regulárního výrazu pomocí zadané barvy.

```cpp
void Aspose::Slides::Presentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Regulární výraz [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pro získání řetězců, které mají být zvýrazněny. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva pro zvýraznění textu. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../ifindresultcallback/). |
## Poznámky

Následující ukázkový kód ukazuje, jak zvýraznit text v PowerPointu [Presentation](../) pomocí regulárního výrazu.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// zvýraznění všech slov s 10 a více znaky
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Regex](../../../system.text.regularexpressions/regex/)
* Třída [Color](../../../system.drawing/color/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Třída [Presentation](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)