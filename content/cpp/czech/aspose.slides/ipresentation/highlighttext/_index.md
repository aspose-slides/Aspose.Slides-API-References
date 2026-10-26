---
title: HighlightText()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Zvýrazní všechny výskyty ukázkového textu zadanou barvou.
type: docs
weight: 456
url: /cs/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) metoda

Zvýrazní všechny výskyty ukázkového textu zadanou barvou.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text, který se má zvýraznit. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva, kterou se má text zvýraznit. |
## Poznámky

Následující ukázkový kód ukazuje, jak zvýraznit text v prezentaci PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// zvýraznění všech samostatných výskytů 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metoda

Zvýrazní všechny výskyty ukázkového textu zadanou barvou.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Text, který se má zvýraznit. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Barva, kterou se má text zvýraznit. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Možnosti vyhledávání textu [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../ifindresultcallback/). |
## Poznámky

Následující ukázkový kód ukazuje, jak zvýraznit text v prezentaci PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// zvýraznění všech samostatných výskytů 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [Color](../../../system.drawing/color/)
* Třída [IPresentation](../)
* Třída [ITextSearchOptions](../../itextsearchoptions/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)