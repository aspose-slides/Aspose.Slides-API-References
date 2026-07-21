---
title: FormatShape()
second_title: Aspose.Slides для C++ Справочник API
description: Эта функция вызывается перед отрисовкой фигуры в SVG, чтобы пользователь мог управлять полученным SVG.
type: docs
weight: 1
url: /ru/aspose.slides.export/isvgshapeformattingcontroller/formatshape/
---
## ISvgShapeFormattingController::FormatShape(System::SharedPtr\<ISvgShape\>, System::SharedPtr\<IShape\>) метод

Эта функция вызывается перед отрисовкой фигуры в SVG, чтобы дать пользователю возможность управлять результирующим SVG.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeFormattingController::FormatShape(System::SharedPtr<ISvgShape> svgShape, System::SharedPtr<IShape> shape)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgShape | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgShape](../../isvgshape/)\> | Объект для управления генерацией SVG-формы. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | Исходная фигура. |

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISvgShape](../../isvgshape/)
* Класс [IShape](../../../aspose.slides/ishape/)
* Класс [ISvgShapeFormattingController](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Библиотека [Aspose.Slides](../../../)