---
title: TextFrameFormat
second_title: Aspose.Sildes для .NET API Справочник
description: Содержит свойства форматирования TextFrames.
type: docs
weight: 10650
url: /ru/aspose.slides/textframeformat/
---

## TextFrameFormat класс

Содержит свойства форматирования TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Конструкторы

| Название | Описание |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Инициализирует новый экземпляр класса [`TextFrameFormat`](../textframeformat). |

## Свойства

| Название | Описание |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Возвращает или задает вертикальную якорную точку текста в TextFrame. Чтение/запись [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Возвращает или задает режим авторазмера текста. Чтение/запись [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Если NullableBool.True, то текст должен быть выровнен по центру горизонтально. Чтение/запись [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Возвращает или задает количество колонок в текстовой области. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Значение 0 означает неопределенное значение. Чтение/запись Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Возвращает или задает пространство между текстовыми колонками в текстовой области (в пунктах). Это должно применяться только при наличии более одной колонки. Это значение должно быть положительным числом. В противном случае значение будет установлено в ноль. Чтение/запись Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Получает или задает сохранение текста плоским, даже если применяется эффект 3D-вращения. Чтение/запись Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Возвращает или задает нижний отступ (пункты) в TextFrame. Чтение/запись Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Возвращает или задает левый отступ (пункты) в TextFrame. Чтение/запись Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Возвращает или задает правый отступ (пункты) в TextFrame. Чтение/запись Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Возвращает или задает верхний отступ (пункты) в TextFrame. Чтение/запись Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Указывает произвольный угол вращения, который применяется к тексту внутри ограничивающего прямоугольника. Если не указано, используется вращение сопутствующей фигуры. Если указано, то применяется независимо от фигуры. То есть может быть применено вращение фигуры, помимо вращения текста. Результирующее значение визуального вращения текста суммируется из этого свойства и предопределенного вертикального типа в свойстве TextVerticalType. Чтение/запись Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Определяет ориентацию текста. Результирующее значение визуального вращения текста суммируется из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Возвращает объект ThreeDFormat, представляющий свойства 3D-эффекта для текста. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Получает или задает форму обтягивания текста. Чтение/запись [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True**, если текст обтекается по краям TextFrame. Чтение/запись [`NullableBool`](../nullablebool). |

## Методы

| Название | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Получает эффективные данные форматирования текстового фрейма с применением наследования. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хеш-код. |

### См. Также

* класс [PVIObject](../pviobject)
* интерфейс [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* интерфейс [ITextFrameFormat](../itextframeformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->