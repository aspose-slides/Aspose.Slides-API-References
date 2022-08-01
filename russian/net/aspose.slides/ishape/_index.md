---
title: IShape
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет фигуру на слайде.
type: docs
weight: 6370
url: /ru/net/aspose.slides/ishape/
---
## IShape interface

Представляет фигуру на слайде.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/записьString . |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/записьString . |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Позволяет получить базовый интерфейс IHyperlinkContainer. Только для чтения[`IHyperlinkContainer`](../ihyperlinkcontainer) . |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Позволяет получить базовый интерфейс ISlideComponent. Только для чтения[`ISlideComponent`](../islidecomponent) . |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом режиме отображения.. Чтение/запись[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Возвращает количество сайтов подключения на фигуре. Только для чтенияInt32 . |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения[`ICustomData`](../icustomdata) . |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, примененные к фигуре. Только для чтения[`IEffectFormat`](../ieffectformat) . |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры. Только для чтения[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Возвращает или задает свойства фрейма формы. Чтение/запись[`IShapeFrame`](../ishapeframe) . |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/записьSingle . |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/записьBoolean . |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтенияBoolean . |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Определяет, является ли фигура TextHolder. Только для чтенияBoolean . |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Возвращает объект LineFormat, содержащий свойства форматирования линии для фигуры. Только для чтения[`ILineFormat`](../ilineformat) . |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Возвращает или задает имя формы. Чтение/записьString . |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайда. Только для чтенияUInt32 . См. также[`UniqueId`](./uniqueid) для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Возвращает заполнитель для формы. Только для чтения[`IPlaceholder`](../iplaceholder) . |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Возвращает или задает свойства кадра необработанной формы. Чтение/запись[`IShapeFrame`](../ishapeframe) . |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Возвращает или задает число градусов, на которое указанная фигура поворачивается вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/записьSingle . |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Возвращает блокировки формы. Только для чтения[`IBaseShapeLock`](../ibaseshapelock) . |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства форматирования линии для фигуры. Только для чтения[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Получает уникальный идентификатор формы в области представления. Только для чтенияUInt32 . См. также[`OfficeInteropShapeId`](./officeinteropshapeid) для получения уникального идентификатора формы в области слайдов. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/записьSingle . |
| [X](../../aspose.slides/ishape/x) { get; set; } | Возвращает или задает координату x левого верхнего угла фигуры. Чтение/записьSingle . |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Возвращает или задает координату y левого верхнего угла фигуры. Чтение/записьSingle . |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Возвращает позицию фигуры в z-порядке. Shapes[0] возвращает фигуру в конце z-порядка, и Shapes[Shapes.Count - 1] возвращает фигуру в начале z-порядка. order. Только для чтенияInt32 . |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанный. |
| [GetThumbnail](../../aspose.slides/ishape/getthumbnail#getthumbnail)() | Возвращает миниатюру фигуры. ShapeThumbnailBounds. Тип границ миниатюры формы используется по умолчанию. |
| [GetThumbnail](../../aspose.slides/ishape/getthumbnail#getthumbnail_1)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Указывает, что эта фигура не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Сохраняет содержимое формы в виде файла SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое формы в виде файла SVG. |

### Смотрите также

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
