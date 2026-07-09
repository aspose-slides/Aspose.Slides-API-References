---
title: TextFrameFormat
second_title: Aspose.Sildes для .NET справочник API
description: Содержит свойства formatTextFrameFormatting TextFrames.
type: docs
weight: 10960
url: /ru/aspose.slides/textframeformat/
---
## TextFrameFormat класс

Содержит свойства formatTextFrameFormatting TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Инициализирует новый экземпляр класса [`TextFrameFormat`](../textframeformat). |

## Свойства

| Имя | Описание |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Возвращает или задает вертикальный якорный текст в TextFrame. Чтение/запись [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Возвращает или задает режим автоподгонки текста. Чтение/запись [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Если NullableBool.True, то текст должен быть центрирован по горизонтали в коробке. Чтение/запись [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Возвращает или задает количество колонок в текстовой области. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Значение 0 означает неопределённое значение. Чтение/запись Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Возвращает или задает пространство между колонками текста в текстовой области (в пунктах). Это применяется только при наличии более чем 1 колонки. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Чтение/запись Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Получает или задает сохранение текста плоским даже при применённом эффекте 3-D Rotation. Чтение/запись Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Возвращает или задает нижний отступ (в пунктах) в TextFrame. Чтение/запись Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Возвращает или задает левый отступ (в пунктах) в TextFrame. Чтение/запись Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Возвращает или задает правый отступ (в пунктах) в TextFrame. Чтение/запись Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Возвращает или задает верхний отступ (в пунктах) в TextFrame. Чтение/запись Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Указывает пользовательский угол вращения, применяемый к тексту внутри ограничивающего прямоугольника. Если не указано, используется вращение сопутствующей формы. Если указано, то оно применяется независимо от формы. То есть форма может иметь вращение, дополнительно к вращению самого текста. Полученное значение визуального вращения текста суммируется из этого свойства и предопределённого вертикального типа в свойстве TextVerticalType. Чтение/запись Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Определяет ориентацию текста. Полученное значение визуального вращения текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Возвращает объект ThreeDFormat, представляющий свойства 3-D эффекта для текста. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Получает или задает форму переноса текста. Чтение/запись [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** если текст переносится на полях TextFrame. Чтение/запись [`NullableBool`](../nullablebool). |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным object. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Получает эффективные данные форматирования текстовой рамки с применённым наследованием. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает код хэша. |

### Смотрите также

* класс [PVIObject](../pviobject)
* интерфейс [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* интерфейс [ITextFrameFormat](../itextframeformat)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->