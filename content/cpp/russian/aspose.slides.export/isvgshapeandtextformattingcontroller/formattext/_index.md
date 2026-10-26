---
title: FormatText()
second_title: Справочник API Aspose.Slides для C++
description: Эта функция вызывается перед рендерингом текстовой части в SVG, чтобы пользователь мог управлять полученным SVG.
type: docs
weight: 1
url: /ru/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) метод

Эта функция вызывается перед рендерингом текстовой части в SVG, чтобы пользователь мог управлять полученным SVG.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Объект для управления генерацией SVG tspan. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Исходный фрагмент. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Текстовый кадр исходной части. |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISvgTSpan](../../isvgtspan/)
* Класс [IPortion](../../../aspose.slides/iportion/)
* Класс [ITextFrame](../../../aspose.slides/itextframe/)
* Класс [ISvgShapeAndTextFormattingController](../)
* Пространство имён [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)