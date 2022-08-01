---
title: TextFrameFormat
second_title: Справочник по API Aspose.Slides для .NET
description: Содержит свойства formatTextFrameFormatting TextFrame.
type: docs
weight: 10150
url: /ru/net/aspose.slides/textframeformat/
---
## TextFrameFormat class

Содержит свойства formatTextFrameFormatting TextFrame.

```csharp
public class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Инициализирует новый экземпляр[`TextFrameFormat`](../textframeformat) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Возвращает или задает текст вертикальной привязки в TextFrameEx. Чтение/запись[`TextAnchorType`](../textanchortype) . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения[`IPresentationComponent`](../ipresentationcomponent) . |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Возвращает или устанавливает режим автоподбора текста. Чтение/запись[`TextAutofitType`](../textautofittype) . |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Если NullableBool.True, то текст должен быть центрирован в поле по горизонтали. Чтение/запись[`NullableBool`](../nullablebool) . |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Возвращает или задает количество столбцов в текстовой области. Это значение должно быть положительным числом. В противном случае значение будет установлено равным нулю. Значение 0 означает неопределенное значение. Чтение/записьInt32 . |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Возвращает или задает расстояние между текстовыми столбцами в текстовой области (в пунктах). Это должно применяться только к , когда присутствует более 1 столбца. Это значение должно быть положительным числом. В противном случае значение будет установлено равным нулю. Чтение/записьDouble . |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Получает или задает, чтобы текст оставался плоским, даже если был применен эффект трехмерного вращения. Чтение/записьBoolean . |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Возвращает или задает нижнее поле (в точках) в TextFrame. Чтение/записьDouble . |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Возвращает или задает левое поле (в точках) в TextFrame. Чтение/записьDouble . |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Возвращает или задает правое поле (в точках) в TextFrame. Чтение/записьDouble . |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Возвращает или задает верхнее поле (в точках) в TextFrame. Чтение/записьDouble . |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Указывает пользовательское вращение, которое применяется к тексту в ограничивающей рамке. Если не указано , используется вращение сопровождающей фигуры. Если он указан, то это is применяется независимо от фигуры. То есть фигура может иметь поворот, примененный in в дополнение к самому тексту, к которому применен поворот. Результирующее значение поворота визуального текста, суммированное из этого свойства и предопределенного вертикального типа в свойстве TextVerticalType. Чтение/записьSingle . |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Определяет ориентацию текста. Результирующее значение поворота визуального текста, суммированное из этого свойства и пользовательского угла в свойстве RotationAngle. Чтение/запись[`TextVerticalType`](../textverticaltype) . |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Возвращает объект ThreeDFormat, представляющий свойства 3D-эффекта для текста. Только для чтения[`IThreeDFormat`](../ithreedformat) . |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Получает или задает форму переноса текста. Чтение/запись[`TextShapeType`](../textshapetype) . |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **Истинный** если текст перенесен на поля TextFrame. Чтение/запись[`NullableBool`](../nullablebool) . |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Получает действующие данные форматирования текстового фрейма с применением наследования. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |

### Смотрите также

* class [PVIObject](../pviobject)
* interface [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interface [ITextFrameFormat](../itextframeformat)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
