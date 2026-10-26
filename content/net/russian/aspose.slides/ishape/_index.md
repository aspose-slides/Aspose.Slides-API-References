---
title: IShape
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет форму на слайде.
type: docs
weight: 6950
url: /ru/aspose.slides/ishape/
---
## IShape интерфейс

Represents a shape on a slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанный с фигурой. Чтение/запись String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Позволяет получить базовый интерфейс IHyperlinkContainer. Только чтение [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Позволяет получить базовый интерфейс ISlideComponent. Только чтение [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отрисовываться в режиме черно-белого отображения. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Возвращает количество точек соединения на фигуре. Только чтение Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только чтение [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, применённые к фигуре. Только чтение [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры. Только чтение [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Возвращает или задает свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Получает или задает высоту фигуры в пунктах. Чтение/запись Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Получает или задает параметр 'Mark as decorative'. Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только чтение Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Определяет, является ли фигура TextHolder. Только чтение Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры. Только чтение [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Возвращает или задает имя фигуры. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Возвращает уникальный идентификатор в пределах слайда, который остаётся неизменным в течение жизни фигуры и позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа. Только чтение UInt32. См. также [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только чтение [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Возвращает заполнитель для фигуры. Только чтение [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Возвращает или задает свойства необработанной рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Возвращает или задает количество градусов, на которое указанная фигура повернута вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Возвращает блокировки фигуры. Только чтение [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства форматирования линий для фигуры. Только чтение [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Возвращает внутренний идентификатор в пределах презентации, предназначенный для использования ад-инами или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только чтение UInt32. См. также [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Получает или задает ширину фигуры в пунктах. Чтение/запись Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Получает или задает координату x верхнего левого угла фигуры в пунктах. Чтение/запись Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Получает или задает координату y верхнего левого угла фигуры в пунктах. Чтение/запись Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Возвращает позицию фигуры в z-порядке. Shapes[0] возвращает фигуру в задней части z-порядка, а Shapes[Shapes.Count - 1] — фигуру в передней части z-порядка. Только чтение Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Добавляет новый placeholder, если его нет, и задает свойства placeholder указанному. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Возвращает базовую форму placeholder (фигуру из макета и/или образца слайда, от которой наследуется текущая фигура). Если текущая фигура не наследуется, возвращается null. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип ShapeThumbnailBounds.Shape для границ миниатюры. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Определяет, что эта фигура не является placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Сохраняет содержимое Shape в файл SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое Shape в файл SVG. |

### См. также

* интерфейс [IHyperlinkContainer](../ihyperlinkcontainer)
* интерфейс [ISlideComponent](../islidecomponent)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->