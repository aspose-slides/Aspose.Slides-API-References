---
title: WriteShapeEnd()
second_title: Aspose.Slides для C++: справочник API
description: Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-нибудь в генератор, текущая генерация изображения слайда будет завершена, добавленный html-фрагмент будет вставлен и новое изображение будет запущено поверх предыдущего.
type: docs
weight: 79
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) метод

Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в генератор, текущая генерация изображения слайда будет завершена, добавленный HTML-фрагмент будет вставлен, и новое изображение будет запущено поверх предыдущего.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Объект вывода. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) которая рендерится последней. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IHtmlGenerator](../../ihtmlgenerator/)
* Класс [IShape](../../../aspose.slides/ishape/)
* Класс [EmbedAllFontsHtmlController](../)
* пространство имён [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)