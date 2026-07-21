---
title: WriteShapeStart()
second_title: Справочник API Aspose.Slides для C++
description: Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция что-то записывает в генератор, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент вставлен и новое изображение будет начато поверх предыдущего.
type: docs
weight: 53
url: /ru/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) метод

Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция что-то записывает в генератор, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент вставлен и новое изображение будет начато поверх предыдущего.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Объект вывода. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) который собирается рендериться. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IHtmlGenerator](../../ihtmlgenerator/)
* Класс [IShape](../../../aspose.slides/ishape/)
* Класс [IHtmlFormattingController](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)