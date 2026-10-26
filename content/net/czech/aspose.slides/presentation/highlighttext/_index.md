---
title: HighlightText
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Zvýrazní všechny výskyty vzorkového textu pomocí určené barvy.
type: docs
weight: 350
url: /cs/aspose.slides/presentation/highlighttext/
---
## HighlightText(string, Color) {#highlighttext}

Zvýrazní všechny výskyty vzorkového textu pomocí určené barvy.

```csharp
public void HighlightText(string text, Color highlightColor)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | String | Text, který se má zvýraznit. |
| highlightColor | Color | Barva, kterou se má text zvýraznit. |

### Příklady

Následující ukázkový kód demonstruje, jak zvýraznit text v prezentaci PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// zvýraznění všech samostatných výskytů 'the'
	presentation.HighlightText("the", Color.Violet);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### Viz také

* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

---

## HighlightText(string, Color, ITextSearchOptions, IFindResultCallback) {#highlighttext_1}

Zvýrazní všechny výskyty vzorkového textu pomocí určené barvy.

```csharp
public void HighlightText(string text, Color highlightColor, ITextSearchOptions options, 
    IFindResultCallback callback)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| text | String | Text, který se má zvýraznit. |
| highlightColor | Color | Barva, kterou se má text zvýraznit. |
| options | ITextSearchOptions | Možnosti vyhledávání textu [`ITextSearchOptions`](../../itextsearchoptions). |
| callback | IFindResultCallback | Objekt zpětného volání pro přijímání výsledků vyhledávání [`IFindResultCallback`](../../ifindresultcallback). |

### Příklady

Následující ukázkový kód demonstruje, jak zvýraznit text v prezentaci PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// zvýraznění všech samostatných výskytů 'the'
	presentation.HighlightText("the", Color.Violet, new TextSearchOptions() {WholeWordsOnly = true}, null);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [ITextSearchOptions](../../itextsearchoptions)
* rozhraní [IFindResultCallback](../../ifindresultcallback)
* třída [Presentation](../../presentation)
* jmenný prostor [Aspose.Slides](../../presentation)
* sestavení [Aspose.Slides](../../../)

<!-- NEUPRAVUJTE: vygenerováno pomocí xmldocmd pro Aspose.Slides.dll -->