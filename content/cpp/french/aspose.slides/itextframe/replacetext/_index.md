---
title: ReplaceText()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.
type: docs
weight: 144
url: /fr/aspose.slides/itextframe/replacetext/
---
## ITextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) méthode


Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.

```cpp
virtual void Aspose::Slides::ITextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Paramètres

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
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Remplace toutes les occurrences séparées de 'the' par '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ITextSearchOptions](../../itextsearchoptions/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [ITextFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)