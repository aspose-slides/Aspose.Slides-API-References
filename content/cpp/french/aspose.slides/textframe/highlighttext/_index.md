---
title: HighlightText()
second_title: Référence API Aspose.Slides pour C++
description: Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.
type: docs
weight: 131
url: /fr/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) méthode

Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Exemple de texte à mettre en surbrillance. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur à utiliser pour mettre en surbrillance le texte. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) méthode

Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Le texte à mettre en surbrillance. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur à utiliser pour mettre en surbrillance le texte. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Options de mise en surbrillance. |

## Remarques

Obsolète
:   Utilisez la méthode HighlightText(string text, Color highlightColor, ITextSearchOptions options) à la place. La méthode sera supprimée après la sortie de la version 24.10.

Le code d'exemple suivant montre comment Highlight Text dans un [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// mise en surbrillance de tous les mots 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// mise en surbrillance de toutes les occurrences séparées de 'the'
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) méthode

Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Le texte à mettre en surbrillance. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur à utiliser pour mettre en surbrillance le texte. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Options de recherche de texte [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../ifindresultcallback/). |

## Remarques

Le code d'exemple suivant montre comment mettre en surbrillance du texte dans un [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// mise en surbrillance de tous les mots 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// mise en surbrillance de toutes les occurrences séparées de 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Color](../../../system.drawing/color/)
* Classe [TextFrame](../)
* Classe [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Classe [ITextSearchOptions](../../itextsearchoptions/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)