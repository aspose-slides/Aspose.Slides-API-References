---
title: GroupShape
second_title: Aspose.Sildes для .NET API Reference
description: Представляет собой группу фигур на слайде.
type: docs
weight: 4890
url: /ru/aspose.slides/groupshape/
---

## GroupShape class

Представляет собой группу фигур на слайде.

```csharp
public class GroupShape : Shape, IGroupShape
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/запись String. |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | Позволяет получить базовый интерфейс IShape. Только для чтения [`IShape`](../ishape). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество соединительных точек на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может вернуть null для определенных типов фигур, которые не имеют эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства заполнения для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств заполнения. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGroupShapeLock`](../igroupshapelock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для щелчка мышью. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или задает опцию 'Отметить как декоративную' Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для фигуры. Примечание: возвращает null для объектов GroupShape, так как у них нет свойств линий. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя фигуры. Должно быть не null. Используйте пустую строку, если необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в области слайда. Только для чтения UInt32. Также см. [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора фигуры в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства необработанной рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает количество градусов, на которое заданная фигура вращается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение - на вращение против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGroupShapeLock`](../igroupshapelock). (2 свойства) |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | Возвращает коллекцию фигур внутри группы. Только для чтения [`IShapeCollection`](../ishapecollection). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит 3D эффекты для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют 3D свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в области презентации. Только для чтения UInt32. Также см. [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора фигуры в области слайда. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x верхнего левого угла фигуры. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y верхнего левого угла фигуры. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает положение фигуры в z-порядке. Shapes[0] возвращает фигуру на заднем плане z-порядка, а Shapes[Shapes.Count - 1] возвращает фигуру на переднем плане z-порядка. Только для чтения Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя для указанного. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигура из макета и/или основного слайда, от которой наследуется текущая фигура). Если текущая фигура не унаследована, возвращается null. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. Для миниатюр фигуры используется тип ShapeThumbnailBounds.Shape по умолчанию. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в виде SVG файла. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в виде SVG файла. |

### See Also

* class [Shape](../shape)
* interface [IGroupShape](../igroupshape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->