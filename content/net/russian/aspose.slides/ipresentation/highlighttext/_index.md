---
title: HighlightText
second_title: Aspose.Sildes for .NET API Reference
description: Подсвечивает все совпадения образца текста указанным цветом.
type: docs
weight: 330
url: /ru/aspose.slides/ipresentation/highlighttext/
---

## HighlightText(string, Color) {#highlighttext}

Подсвечивает все совпадения образца текста указанным цветом.

```csharp
public void HighlightText(string text, Color highlightColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст, который нужно подсветить. |
| highlightColor | Color | Цвет, которым будет подсвечен текст. |

### Примеры

Следующий пример кода показывает, как подсветить текст в презентации PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// подсвечивание всех отдельных вхождений 'the'
	presentation.HighlightText("the", Color.Violet);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IPresentation](../../ipresentation)
* пространство имен [Aspose.Slides](../../ipresentation)
* сборка [Aspose.Slides](../../../)

---

## HighlightText(string, Color, ITextSearchOptions, IFindResultCallback) {#highlighttext_1}

Подсвечивает все совпадения образца текста указанным цветом.

```csharp
public void HighlightText(string text, Color highlightColor, ITextSearchOptions options, 
    IFindResultCallback callback)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | String | Текст, который нужно подсветить. |
| highlightColor | Color | Цвет, которым будет подсвечен текст. |
| options | ITextSearchOptions | Параметры поиска текста [`ITextSearchOptions`](../../itextsearchoptions). |
| callback | IFindResultCallback | Объект обратного вызова для получения результатов поиска [`IFindResultCallback`](../../ifindresultcallback). |

### Примеры

Следующий пример кода показывает, как подсветить текст в презентации PowerPoint.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// подсвечивание всех отдельных вхождений 'the'
	presentation.HighlightText("the", Color.Violet, new TextSearchOptions() {WholeWordsOnly = true}, null);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [ITextSearchOptions](../../itextsearchoptions)
* интерфейс [IFindResultCallback](../../ifindresultcallback)
* интерфейс [IPresentation](../../ipresentation)
* пространство имен [Aspose.Slides](../../ipresentation)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->