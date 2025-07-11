---
title: ReplaceText
second_title: Aspose.Slides pour .NET API Référence
description: Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.
type: docs
weight: 120
url: /fr/aspose.slides/itextframe/replacetext/
---

## ITextFrame.ReplaceText méthode

Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.

```csharp
public void ReplaceText(string oldText, string newText, ITextSearchOptions options, 
    IFindResultCallback callback)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| oldText | String | La chaîne à remplacer. |
| newText | String | La chaîne pour remplacer toutes les occurrences de oldText. |
| options | ITextSearchOptions | Options de recherche de texte [`ITextSearchOptions`](../../itextsearchoptions). |
| callback | IFindResultCallback | L'objet de rappel pour recevoir les résultats de recherche [`IFindResultCallback`](../../ifindresultcallback). |

### Exemples

Le code d'exemple suivant montre comment remplacer une chaîne spécifiée par une autre chaîne spécifiée.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// Remplacer toutes les occurrences séparées de 'the' par '***'
	((AutoShape)presentation.Slides[0].Shapes[0]).TextFrame.ReplaceText("the", "***", new TextSearchOptions()
	{ WholeWordsOnly = true }, null);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### Voir aussi

* interface [ITextSearchOptions](../../itextsearchoptions)
* interface [IFindResultCallback](../../ifindresultcallback)
* interface [ITextFrame](../../itextframe)
* namespace [Aspose.Slides](../../itextframe)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->