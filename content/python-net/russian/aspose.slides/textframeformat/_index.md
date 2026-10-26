---
title: TextFrameFormat class
second_title: Aspose.Slides для Python через .NET API справочник
description: 
type: docs
url: /ru/aspose.slides/textframeformat/
---
## TextFrameFormat класс

Содержит свойства форматирования TextFrame.

**Наследование:**[`TextFrameFormat`](/slides/python-net/ru/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)

Тип TextFrameFormat раскрывает следующие члены:

## Конструкторы

| Конструктор | Описание |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ru/aspose.slides/textframeformat/__init__/#) | Инициализирует новый экземпляр класса [`TextFrameFormat`](/slides/python-net/ru/aspose.slides/textframeformat). |

## Свойства

| Свойство | Описание |
| :- | :- |
| [`three_d_format`](/slides/python-net/ru/aspose.slides/textframeformat/three_d_format/) | Возвращает объект ThreeDFormat, представляющий свойства 3D-эффекта для текста.<br/>            Только чтение [`IThreeDFormat`](/slides/python-net/ru/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/ru/aspose.slides/textframeformat/margin_left/) | Возвращает или задает левый отступ (в пунктах) в TextFrame.<br/>            Чтение/запись **float**. |
| [`margin_right`](/slides/python-net/ru/aspose.slides/textframeformat/margin_right/) | Возвращает или задает правый отступ (в пунктах) в TextFrame.<br/>            Чтение/запись **float**. |
| [`margin_top`](/slides/python-net/ru/aspose.slides/textframeformat/margin_top/) | Возвращает или задает верхний отступ (в пунктах) в TextFrame.<br/>            Чтение/запись **float**. |
| [`margin_bottom`](/slides/python-net/ru/aspose.slides/textframeformat/margin_bottom/) | Возвращает или задает нижний отступ (в пунктах) в TextFrame.<br/>            Чтение/запись **float**. |
| [`wrap_text`](/slides/python-net/ru/aspose.slides/textframeformat/wrap_text/) | **True** если текст переносится на полях TextFrame.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/ru/aspose.slides/textframeformat/anchoring_type/) | Возвращает или задает вертикальное привязывание текста в TextFrame.<br/>            Чтение/запись [`TextAnchorType`](/slides/python-net/ru/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/ru/aspose.slides/textframeformat/center_text/) | Если NullableBool.True, то текст должен быть центрирован по горизонтали в рамке.<br/>            Чтение/запись [`NullableBool`](/slides/python-net/ru/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/ru/aspose.slides/textframeformat/text_vertical_type/) | Определяет ориентацию текста.<br/>            Полученное значение визуального вращения текста суммируется из этого свойства и пользовательского угла<br/>            в свойстве RotationAngle.<br/>            Чтение/запись [`TextVerticalType`](/slides/python-net/ru/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/ru/aspose.slides/textframeformat/autofit_type/) | Возвращает или задает режим авторазмещения текста.<br/>            Чтение/запись [`TextAutofitType`](/slides/python-net/ru/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/ru/aspose.slides/textframeformat/column_count/) | Возвращает или задает количество столбцов в текстовой области.<br/>            Это значение должно быть положительным числом. В противном случае будет установлено значение 0.<br/>            Значение 0 означает неопределенное значение.<br/>            Чтение/запись **int**. |
| [`column_spacing`](/slides/python-net/ru/aspose.slides/textframeformat/column_spacing/) | Возвращает или задает расстояние между столбцами текста в текстовой области (в пунктах). Это применимо только<br/>            когда присутствует более 1 столбца.<br/>            Это значение должно быть положительным числом. В противном случае будет установлено значение 0.<br/>            Чтение/запись **float**. |
| [`rotation_angle`](/slides/python-net/ru/aspose.slides/textframeformat/rotation_angle/) | Указывает пользовательское вращение, применяемое к тексту внутри ограничивающего прямоугольника. Если не<br/>            указано, используется вращение соответствующей формы. Если указано, то оно применяется независимо от формы.<br/>            То есть форма может иметь вращение, а текст внутри также может иметь собственное вращение.<br/>            Полученное значение визуального вращения текста суммируется из этого свойства и предопределенного<br/>            вертикального типа в свойстве TextVerticalType.<br/>            Чтение/запись **float**. |
| [`transform`](/slides/python-net/ru/aspose.slides/textframeformat/transform/) | Возвращает или задает форму переноса текста.<br/>            Чтение/запись [`TextShapeType`](/slides/python-net/ru/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/ru/aspose.slides/textframeformat/keep_text_flat/) | Возвращает или задает сохранение плоского текста даже при применении 3-D вращения.<br/>            Чтение/запись **bool**. |
| [`slide`](/slides/python-net/ru/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/ru/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/ru/aspose.slides/textframeformat/text_style/) |  |

## Методы

| Метод | Описание |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/ru/aspose.slides/textframeformat/get_effective/#) | Получает данные эффективного форматирования текстовой рамки с учетом наследования. |

### Смотрите также
* класс [`PVIObject`](/slides/python-net/ru/aspose.slides/pviobject)
* класс [`TextFrameFormat`](/slides/python-net/ru/aspose.slides/textframeformat)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)