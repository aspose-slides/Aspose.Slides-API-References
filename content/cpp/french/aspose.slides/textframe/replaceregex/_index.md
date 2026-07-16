---
title: ReplaceRegex()
second_title: Référence de l'API Aspose.Slides pour C++
description: Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée.
type: docs
weight: 183
url: /fr/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) méthode


Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'expression régulière [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pour obtenir les chaînes à remplacer. |
| newText | [System::String](../../../system/string/) | La chaîne pour remplacer toutes les occurrences des chaînes à remplacer. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Objet de rappel pour enregistrer le résultat de l'opération de remplacement [IFindResultCallback](../../ifindresultcallback/). |
## Remarques



Le code d'exemple suivant montre comment remplacer du texte en utilisant une expression régulière avec une chaîne spécifiée.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [String](../../../system/string/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [TextFrame](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)