---
title: ReplaceText
second_title: Aspose.Sildes для .NET API Справочник
description: Заменяет все вхождения указанного текста на другой указанный текст.
type: docs
weight: 370
url: /ru/aspose.slides/presentation/replacetext/
---

## Presentation.ReplaceText метод

Заменяет все вхождения указанного текста на другой указанный текст.

```csharp
public void ReplaceText(string oldText, string newText, ITextSearchOptions options, 
    IFindResultCallback callback)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| oldText | String | Строка, которую нужно заменить. |
| newText | String | Строка для замены всех вхождений oldText. |
| options | ITextSearchOptions | Варианты поиска текста [`ITextSearchOptions`](../../itextsearchoptions). |
| callback | IFindResultCallback | Объект обратного вызова для получения результатов поиска [`IFindResultCallback`](../../ifindresultcallback). |

### Примеры

Следующий пример кода демонстрирует, как заменить одну указанную строку на другую указанную строку.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx"))
{
	// Заменить все отдельные вхождения 'the' на '***'
	presentation.ReplaceText("the", "***", new TextSearchOptions() {WholeWordsOnly = true}, null);
	presentation.Save("SomePresentation-out2.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [ITextSearchOptions](../../itextsearchoptions)
* интерфейс [IFindResultCallback](../../ifindresultcallback)
* класс [Presentation](../../presentation)
* пространство имен [Aspose.Slides](../../presentation)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->