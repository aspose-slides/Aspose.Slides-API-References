---
title: IShape
second_title: Справочник API Aspose.Sildes for .NET
description: Представляет фигуру на слайде.
type: docs
weight: 6970
url: /ru/aspose.slides/ishape/
---
## IShape интерфейс

Представляет фигуру на слайде.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Свойства

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/запись String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Позволяет получить базовый интерфейс IHyperlinkContainer. Только для чтения [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Позволяет получить базовый интерфейс ISlideComponent. Только для чтения [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Возвращает количество точек соединения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, примененные к фигуре. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства заливки для фигуры. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Возвращает или задает свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Возвращает или задает высоту фигуры в пунктах. Чтение/запись Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Возвращает или задает параметр 'Mark as decorative'. Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Определяет, является ли фигура TextHolder. Только для чтения Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Возвращает или задает имя фигуры. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Возвращает уникальный идентификатор в пределах слайда, который остаётся постоянным в течение срока жизни фигуры и позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа. Только для чтения UInt32. См. также [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Возвращает объект родительского GroupShape, если фигура сгруппирована. Иначе возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Возвращает заполнитель для фигуры. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Возвращает или задает свойства сырой рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Возвращает или задает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства форматирования линий для фигуры. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Возвращает или задает ширину фигуры в пунктах. Чтение/запись Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Возвращает или задает координату x левого верхнего угла фигуры в пунктах. Чтение/запись Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Возвращает или задает координату y левого верхнего угла фигуры в пунктах. Чтение/запись Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру в задней части порядка z, а Shapes[Shapes.Count - 1] — фигуру в передней части. Только для чтения Int32. |

## Методы

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя заданным. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Возвращает базовую форму-заполнитель (фигуру из макета и/или мастера, от которой унаследована текущая фигура). Возвращается null, если текущая фигура не унаследована. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Сохраняет содержимое фигуры в файл SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в файл SVG. |

### См. также

* интерфейс [IHyperlinkContainer](../ihyperlinkcontainer)
* интерфейс [ISlideComponent](../islidecomponent)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->