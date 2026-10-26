---
title: HighlightRegex()
second_title: Référence API Aspose.Slides pour C++
description: Met en surbrillance toutes les correspondances de l'expression régulière avec la couleur spécifiée.
type: docs
weight: 131
url: /fr/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) method


Met en surbrillance toutes les correspondances de l'expression régulière avec la couleur spécifiée.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'expression régulière [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pour obtenir les chaînes à mettre en surbrillance. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur pour mettre en surbrillance le texte. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../ifindresultcallback/). |
## Remarques



L'exemple de code suivant montre comment mettre en surbrillance du texte dans un [TextFrame](../../textframe/) à l'aide d'une expression régulière. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) method


Met en surbrillance toutes les correspondances de l'expression régulière avec la couleur spécifiée.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Texte de l'expression régulière pour obtenir le texte à mettre en surbrillance. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur pour mettre en surbrillance le texte. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Options de mise en surbrillance. |

Obsolète
:   Utilisez la méthode HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) à la place. La méthode sera supprimée après la sortie de la version 24.10.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [Color](../../../system.drawing/color/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Classe [ITextFrame](../)
* Classe [String](../../../system/string/)
* Classe [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)