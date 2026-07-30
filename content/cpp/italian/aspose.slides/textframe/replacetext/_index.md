---
title: ReplaceText()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato.
type: docs
weight: 170
url: /it/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metodo

Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | La stringa da sostituire. |
| newText | [System::String](../../../system/string/) | La stringa che sostituisce tutte le occorrenze di oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opzioni di ricerca del testo [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Oggetto di callback per salvare il risultato dell'operazione di sostituzione [IFindResultCallback](../../ifindresultcallback/). |

## Note

Il codice di esempio seguente mostra come sostituire una stringa specificata con un'altra stringa specificata.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Sostituisce tutte le occorrenze separate di 'the' con '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)