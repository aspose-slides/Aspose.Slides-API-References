---
title: ReplaceText()
second_title: Riferimento API di Aspose.Slides per C++
description: Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato.
type: docs
weight: 521
url: /it/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) metodo

Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | La stringa da sostituire. |
| newText | [System::String](../../../system/string/) | La stringa per sostituire tutte le occorrenze di oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Opzioni di ricerca del testo [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../ifindresultcallback/). |
## Note

Il codice di esempio seguente mostra come sostituire una stringa specificata con un'altra stringa specificata.

```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Sostituisce tutte le occorrenze separate di 'the' con '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [String](../../../system/string/)
* classe [ITextSearchOptions](../../itextsearchoptions/)
* classe [IFindResultCallback](../../ifindresultcallback/)
* classe [Presentation](../)
* spazio dei nomi [Aspose::Slides](../../)
* libreria [Aspose.Slides](../../../)