---
title: WriteShapeStart()
second_title: Aspose.Slides для C++ справочник API
description: Вызывается перед отрисовкой фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в генератор, создание текущего изображения слайда будет завершено, добавленный HTML-фрагмент будет вставлен, и новое изображение будет запущено поверх предыдущего.
type: docs
weight: 66
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) метод

Вызывается перед отрисовкой фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в генератор, создание текущего изображения слайда будет завершено, вставлен добавленный HTML-фрагмент, и новое изображение будет запущено поверх предыдущего.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Объект вывода. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) который собирается отрисовываться. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IHtmlGenerator](../../ihtmlgenerator/)
* Класс [IShape](../../../aspose.slides/ishape/)
* Класс [EmbedAllFontsHtmlController](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)