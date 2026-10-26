---
title: WriteShapeEnd()
second_title: Справочник API Aspose.Slides для C++
description: Вызывается перед рендерингом формы. Вызывается один раз для каждой формы. Если эта функция записывает что-то в generator, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент будет вставлен и новое изображение будет начато поверх предыдущего.
type: docs
weight: 66
url: /ru/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) метод


Вызывается перед рендерингом формы. Вызывается один раз для каждой формы. Если эта функция что-то записывает в generator, текущая генерация изображения слайда будет завершена, добавленный фрагмент html будет вставлен, и новое изображение будет начато поверх предыдущего.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Объект вывода. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) которая рендерится последней. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IHtmlGenerator](../../ihtmlgenerator/)
* Класс [IShape](../../../aspose.slides/ishape/)
* Класс [IHtmlFormattingController](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)