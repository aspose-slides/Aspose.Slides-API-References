---
title: ReplaceRegex
second_title: Aspose.Sildes для .NET API Ссылка
description: Заменяет все совпадения регулярного выражения на указанную строку.
type: docs
weight: 120
url: /ru/aspose.slides/textframe/replaceregex/
---

## TextFrame.ReplaceRegex метод

Заменяет все совпадения регулярного выражения на указанную строку.

```csharp
public void ReplaceRegex(Regex regex, string newText, IFindResultCallback callback)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | Regex | Регулярное выражение Regex для получения строк, которые нужно заменить. |
| newText | String | Строка, которая заменяет все вхождения строк, которые нужно заменить. |
| callback | IFindResultCallback | Объект обратного вызова для сохранения результата операции замены [`IFindResultCallback`](../../ifindresultcallback). |

### Примеры

Следующий пример кода показывает, как заменить текст с использованием регулярного выражения на указанную строку.

```csharp
[C#]
using (Presentation presentation = new Presentation("SomePresentation.pptx")){
	Regex regex = new Regex(@"\b[^\s]{10,}\b");
	// Заменяем все слова из 10 и более символов на '***'
	((AutoShape)presentation.Slides[0].Shapes[0]).TextFrame.ReplaceRegex(regex, "***", null);
	presentation.Save("SomePresentation-out.pptx", SaveFormat.Pptx);
}
```

### См. также

* интерфейс [IFindResultCallback](../../ifindresultcallback)
* класс [TextFrame](../../textframe)
* пространство имен [Aspose.Slides](../../textframe)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->