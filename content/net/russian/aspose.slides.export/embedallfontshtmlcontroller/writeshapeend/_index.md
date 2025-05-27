---
title: WriteShapeEnd
second_title: Aspose.Slides для .NET Справочник API
description: Вызывается перед отрисовкой фигур. Вызывается для каждой фигуры один раз. Если эта функция записывает что-либо в генератор, текущее создание изображения слайда будет завершено, добавленный html-фрагмент будет вставлен, и новое изображение начнется поверх предыдущего.
type: docs
weight: 60
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---

## EmbedAllFontsHtmlController.WriteShapeEnd метод

Вызывается перед отрисовкой фигуры. Вызывается для каждой фигуры один раз. Если эта функция записывает что-либо в генератор, текущее создание изображения слайда будет завершено, добавленный html-фрагмент будет вставлен, и новое изображение начнется поверх предыдущего.

```csharp
public virtual void WriteShapeEnd(IHtmlGenerator generator, IShape shape)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | IHtmlGenerator | Объект вывода. |
| shape | IShape | Фигура, которая отрисована последней. |

### См. также

* интерфейс [IHtmlGenerator](../../ihtmlgenerator)
* интерфейс [IShape](../../../aspose.slides/ishape)
* класс [EmbedAllFontsHtmlController](../../embedallfontshtmlcontroller)
* пространство имен [Aspose.Slides.Export](../../embedallfontshtmlcontroller)
* сборка [Aspose.Slides](../../../)