---
title: HighlightText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.
type: docs
weight: 495
url: /fr/aspose.slides/presentation/highlighttext/
---
## Presentation::HighlightText(System::String, System::Drawing::Color) méthode

Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Le texte à mettre en surbrillance. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur utilisée pour mettre en surbrillance le texte. |
## Remarques

L'exemple de code suivant montre comment mettre en évidence du texte dans une présentation PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// mise en surbrillance de toutes les occurrences séparées de 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Presentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) méthode

Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée.

```cpp
void Aspose::Slides::Presentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Le texte à mettre en surbrillance. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | La couleur utilisée pour mettre en surbrillance le texte. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Options de recherche de texte [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../ifindresultcallback/). |
## Remarques

L'exemple de code suivant montre comment mettre en évidence du texte dans une présentation PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// mise en surbrillance de toutes les occurrences séparées de 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [Color](../../../system.drawing/color/)
* Classe [Presentation](../)
* Classe [ITextSearchOptions](../../itextsearchoptions/)
* Classe [IFindResultCallback](../../ifindresultcallback/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)