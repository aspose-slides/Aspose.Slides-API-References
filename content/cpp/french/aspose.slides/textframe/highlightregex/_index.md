---
title: HighlightRegex()
second_title: Référence API Aspose.Slides pour C++
description: Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée.
type: docs
weight: 157
url: /fr/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) méthode

Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Texte de l'expression régulière à mettre en évidence. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur utilisée pour mettre en évidence le texte. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Options de mise en évidence. |

## Remarques

Obsolète
:   Utilisez la méthode HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback) à la place. Cette méthode sera supprimée après la publication de la version 24.10.

L'exemple de code suivant montre comment mettre en évidence du texte dans un [TextFrame](../) à l'aide d'une expression régulière. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// mise en évidence de tous les mots de 10 caractères ou plus
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) méthode

Met en évidence toutes les correspondances de l'expression régulière avec la couleur spécifiée.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | L'expression régulière [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) pour obtenir les chaînes à mettre en évidence. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur utilisée pour mettre en évidence le texte. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../ifindresultcallback/). |

## Remarques

L'exemple de code suivant montre comment mettre en évidence du texte dans un [TextFrame](../) à l'aide d'une expression régulière. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// mise en évidence de tous les mots de 10 caractères ou plus
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Color](../../../system.drawing/color/)
* Classe [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Classe [TextFrame](../)
* Classe [Regex](../../../system.text.regularexpressions/regex/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)