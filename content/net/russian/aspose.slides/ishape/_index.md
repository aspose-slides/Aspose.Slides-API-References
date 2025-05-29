---
title: IShape
second_title: Aspose.Slides для .NET API Reference
description: Представляет форму на слайде.
type: docs
weight: 6730
url: /ru/aspose.slides/ishape/
---

## Интерфейс IShape

Представляет форму на слайде.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с формой. Чтение/запись Строка. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с формой. Чтение/запись Строка. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Позволяет получить базовый интерфейс IHyperlinkContainer. Только для чтения [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Позволяет получить базовый интерфейс ISlideComponent. Только для чтения [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Свойство определяет, как форма будет отображаться в черно-белом режиме.. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Возвращает количество соединительных точек на форме. Только для чтения Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Возвращает пользовательские данные формы. Только для чтения [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к форме. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заливки для формы. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Возвращает или устанавливает свойства рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Возвращает или устанавливает высоту формы. Чтение/запись Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Определяет, скрыта ли форма. Чтение/запись Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Получает или устанавливает опцию «Отметить как декоративную» Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Определяет, сгруппирована ли форма. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Определяет, является ли форма TextHolder. Только для чтения Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для формы. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Возвращает или устанавливает имя формы. Чтение/запись Строка. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в рамках слайда. Только для чтения UInt32. См. также [`UniqueId`](./uniqueid) для получения уникального идентификатора формы в рамках презентации. |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если форма сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Возвращает заполнитель для формы. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Возвращает или устанавливает свойства сырой рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое указанная форма вращена вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Возвращает замки формы. Только для чтения [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства форматирования линий для формы. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Получает уникальный идентификатор формы в рамках презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](./officeinteropshapeid) для получения уникального идентификатора формы в рамках слайда. |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Возвращает или устанавливает ширину формы. Чтение/запись Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Возвращает или устанавливает координату x верхнего левого угла формы. Чтение/запись Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Возвращает или устанавливает координату y верхнего левого угла формы. Чтение/запись Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Возвращает позицию формы в порядке по z. Shapes[0] возвращает форму на заднем плане, а Shapes[Shapes.Count - 1] возвращает форму на переднем плане. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанные. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Возвращает базовую форму заполнителя (форму из макета и/или шаблона слайда, от которой наследуется текущая форма). Возвращает null, если текущая форма не наследуется. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Возвращает миниатюру формы. Для миниатюры формы по умолчанию используется тип миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Определяет, что эта форма не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Сохраняет содержимое формы как файл SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое формы как файл SVG. |

### См. также

* интерфейс [IHyperlinkContainer](../ihyperlinkcontainer)
* интерфейс [ISlideComponent](../islidecomponent)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->