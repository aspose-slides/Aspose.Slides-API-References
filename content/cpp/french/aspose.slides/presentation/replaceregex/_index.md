---
title: ReplaceRegex()
second_title: Référence API Aspose.Slides pour C++
description: Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée.
type: docs
weight: 534
url: /fr/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) méthode


Remplace toutes les correspondances de l’expression régulière par la chaîne spécifiée.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L’expression régulière [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pour obtenir les chaînes à remplacer. |
| newText | [System::String](../../../system/string/) | La chaîne pour remplacer toutes les occurrences des chaînes à remplacer. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L’objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../ifindresultcallback/). |
## Remarques



L’exemple de code suivant montre comment remplacer du texte en utilisant une expression régulière avec la chaîne spécifiée. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [String](../../../system/string/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [Presentation](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)