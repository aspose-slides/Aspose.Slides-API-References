---
title: IParagraph
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет абзац текста.
type: docs
weight: 6000
url: /ru/aspose.slides/iparagraph/
---
## IParagraph interface

Представляет абзац текста.

```csharp
public interface IParagraph : ISlideComponent
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AsISlideComponent](../../aspose.slides/iparagraph/asislidecomponent) { get; } | Позволяет получить базовый интерфейс ISlideComponent. Только для чтения[`ISlideComponent`](../islidecomponent). |
| [EndParagraphPortionFormat](../../aspose.slides/iparagraph/endparagraphportionformat) { get; set; } | Определяет свойства части, которые должны использоваться, если другая часть вставляется после последней. |
| [ParagraphFormat](../../aspose.slides/iparagraph/paragraphformat) { get; } | Возвращает объект форматирования для этого абзаца. Только для чтения[`IParagraphFormat`](../iparagraphformat). |
| [Portions](../../aspose.slides/iparagraph/portions) { get; } | Возвращает набор текстовых частей. Только для чтения[`IPortionCollection`](../iportioncollection). |
| [Text](../../aspose.slides/iparagraph/text) { get; set; } | Получает или задает обычный текст абзаца. Чтение/записьString. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetRect](../../aspose.slides/iparagraph/getrect)() | Получить координаты прямоугольника, ограничивающего абзац. Прямоугольник включает в себя все строки текста в абзаце, включая пустые. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/iparagraph/joinportionswithsameformatting)() | Соединения выполняются с одинаковым форматированием. |

### Смотрите также

* interface [ISlideComponent](../islidecomponent)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
