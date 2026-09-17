---
title: ITextFrameFormat class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/itextframeformat/
---
## ITextFrameFormat класс

Содержит свойства форматирования TextFrame.

Тип ITextFrameFormat представляет следующие члены:

## Свойства

| Property | Description |
| :- | :- |
| [`text_style`](/slides/python-net/ru/aspose.slides/itextframeformat/text_style/) | Returns text's style.<br/>            Только чтение [`ITextStyle`](/slides/python-net/ru/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/ru/aspose.slides/itextframeformat/margin_left/) | Returns or sets the left margin (points) in a TextFrame.<br/>            Чтение/запись **float**. |
| [`margin_right`](/slides/python-net/ru/aspose.slides/itextframeformat/margin_right/) | Returns or sets the right margin (points) in a TextFrame.<br/>            Чтение/запись **float**. |
| [`margin_top`](/slides/python-net/ru/aspose.slides/itextframeformat/margin_top/) | Returns or sets the top margin (points) in a TextFrame.<br/>            Чтение/запись **float**. |
| [`margin_bottom`](/slides/python-net/ru/aspose.slides/itextframeformat/margin_bottom/) | Returns or sets the bottom margin (points) in a TextFrame.<br/>            Чтение/запись **float**. |
| [`wrap_text`](/slides/python-net/ru/aspose.slides/itextframeformat/wrap_text/) | **True**  если текст переносится по границам TextFrame.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/ru/aspose.slides/itextframeformat/anchoring_type/) | Returns or sets vertical anchor text in a TextFrame.<br/>            Чтение/запись [`TextAnchorType`](/slides/python-net/ru/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/ru/aspose.slides/itextframeformat/center_text/) | Если NullableBool.True, то текст должен быть выровнен по центру горизонтально в коробке.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/ru/aspose.slides/itextframeformat/text_vertical_type/) | Determines text orientation.<br/>            The resulted value of visual text rotation summarized from this property and custom angle<br/>            in property RotationAngle.<br/>            Чтение/запись [`TextVerticalType`](/slides/python-net/ru/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/ru/aspose.slides/itextframeformat/autofit_type/) | Returns or sets text's autofit mode.<br/>            Чтение/запись [`TextAutofitType`](/slides/python-net/ru/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/ru/aspose.slides/itextframeformat/column_count/) | Returns or sets number of columns in the text area.<br/>            This value must be a positive number. Otherwise, the value will be set to zero. <br/>            Value 0 means undefined value.<br/>            Чтение/запись **int**. |
| [`column_spacing`](/slides/python-net/ru/aspose.slides/itextframeformat/column_spacing/) | Returns or sets the space between text columns in the text area (in points). This should only apply <br/>            when there is more than 1 column present.<br/>            This value must be a positive number. Otherwise, the value will be set to zero. <br/>            Чтение/запись **float**. |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/itextframeformat/three_d_format/) | Returns the ThreeDFormat object that represents 3d effect properties for a text.<br/>            Только чтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/ru/aspose.slides/itextframeformat/keep_text_flat/) | Returns or set keeping text out of 3D scene entirely.<br/>            Чтение/запись **bool**. |
| [`rotation_angle`](/slides/python-net/ru/aspose.slides/itextframeformat/rotation_angle/) | Specifies the custom rotation that is being applied to the text within the bounding box. If it not<br/>            specified, the rotation of the accompanying shape is used. If it is specified, then this is<br/>            applied independently from the shape. That is the shape can have a rotation applied in<br/>            addition to the text itself having a rotation applied to it.<br/>            The resulted value of visual text rotation summarized from this property and predefined<br/>            vertical type in property TextVerticalType.<br/>            Чтение/запись **float**. |
| [`transform`](/slides/python-net/ru/aspose.slides/itextframeformat/transform/) | Gets or sets text wrapping shape.<br/>            Чтение/запись [`TextShapeType`](/slides/python-net/ru/aspose.slides/textshapetype). |

## Методы

| Method | Description |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ru/aspose.slides/itextframeformat/get_effective/#) | Gets effective text frame formatting data with the inheritance applied. |

### Смотрите также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)