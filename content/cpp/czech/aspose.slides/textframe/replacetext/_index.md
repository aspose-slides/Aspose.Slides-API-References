---
title: ReplaceText()
second_title: Aspose.Slides pro C++ referenci API
description: Nahrazuje všechny výskyty zadaného textu jiným zadaným textem.
type: docs
weight: 170
url: /cs/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metoda


Nahrazuje všechny výskyty zadaného textu jiným zadaným textem.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Řetězec, který má být nahrazen. |
| newText | [System::String](../../../system/string/) | Řetězec, který nahradí všechny výskyty oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Možnosti vyhledávání textu [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objekt callback pro uložení výsledku operace nahrazení [IFindResultCallback](../../ifindresultcallback/). |
## Poznámky



Následující ukázkový kód ukazuje, jak nahradit jeden specifikovaný řetězec jiným specifikovaným řetězcem. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Nahradí všechny samostatné výskyty 'the' řetězcem '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [String](../../../system/string/)
* Třída [ITextSearchOptions](../../itextsearchoptions/)
* Třída [IFindResultCallback](../../ifindresultcallback/)
* Třída [TextFrame](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)