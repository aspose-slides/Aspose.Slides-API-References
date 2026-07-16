---
title: ReplaceText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.
type: docs
weight: 521
url: /fr/aspose.slides/presentation/replacetext/
---
## Presentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.

```cpp
void Aspose::Slides::Presentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | La chaîne à remplacer. |
| newText | [System::String](../../../system/string/) | La chaîne qui remplace toutes les occurrences de oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Options de recherche de texte [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../ifindresultcallback/). |
## Remarques



Le code d'exemple suivant montre comment remplacer une chaîne spécifiée par une autre chaîne spécifiée. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Remplace toutes les occurrences distinctes de 'the' par '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)