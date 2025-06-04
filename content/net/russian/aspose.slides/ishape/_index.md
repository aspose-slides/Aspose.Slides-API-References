---
title: IShape
second_title: Aspose.Sildes для .NET API Reference
description: Представляет фигуру на слайде.
type: docs
weight: 6730
url: /ru/aspose.slides/ishape/
---

## Интерфейс IShape

Представляет фигуру на слайде.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Свойства

| Название | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Возвращает или устанавливает название альтернативного текста, связанного с фигурой. Чтение/запись String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Позволяет получить базовый интерфейс IHyperlinkContainer. Только для чтения [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Позволяет получить базовый интерфейс ISlideComponent. Только для чтения [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Возвращает количество точек соединения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заливки для фигуры. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Возвращает или устанавливает свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Возвращает или устанавливает высоту фигуры. Чтение/запись Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Получает или устанавливает опцию "Ометить как декоративную" Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Определяет, является ли фигура текстовым держателем. Только для чтения Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для фигуры. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Возвращает или устанавливает имя фигуры. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в области слайда. Только для чтения UInt32. См. также [`UniqueId`](./uniqueid) для получения уникального идентификатора фигуры в области презентации. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Возвращает заполнител для фигуры. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Возвращает или устанавливает свойства необработанной рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое заданная фигура повернута вокруг оси z. Положительное значение указывает на поворот по часовой стрелке; отрицательное значение указывает на поворот против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства форматирования линий для фигуры. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в области презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](./officeinteropshapeid) для получения уникального идентификатора фигуры в области слайда. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Возвращает или устанавливает ширину фигуры. Чтение/запись Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Возвращает или устанавливает x-координату верхнего левого угла фигуры. Чтение/запись Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Возвращает или устанавливает y-координату верхнего левого угла фигуры. Чтение/запись Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Возвращает позицию фигуры в порядке по оси z. Shapes[0] возвращает фигуру, находящуюся в нижней части порядка по оси z, а Shapes[Shapes.Count - 1] возвращает фигуру на переднем плане порядка по оси z. Только для чтения Int32. |

## Методы

| Название | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Добавляет новый заполнител, если его нет, и устанавливает свойства заполнителя на указанные. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или мастер-слайда, от которой наследуется текущая фигура). Если текущая фигура не наследуется, возвращается null. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Сохраняет содержимое фигуры в виде файла SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в виде файла SVG. |

### Смотрите также

* интерфейс [IHyperlinkContainer](../ihyperlinkcontainer)
* интерфейс [ISlideComponent](../islidecomponent)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->