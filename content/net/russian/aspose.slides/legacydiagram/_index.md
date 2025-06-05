---
title: LegacyDiagram
second_title: Aspose.Sildes для .NET API Reference
description: Представляет объект устаревшей диаграммы.
type: docs
weight: 7430
url: /ru/aspose.slides/legacydiagram/
---

## LegacyDiagram class

Представляет объект устаревшей диаграммы.

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с фигурой. Читаемая/записываемая строка. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает название альтернативного текста, связанного с фигурой. Читаемая/записываемая строка. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | Позволяет получить базовый интерфейс IGraphicalObject. Только для чтения [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом дисплейном режиме. Читаемая/записываемая [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек соединения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, применяемые к фигуре. Примечание: может возвращать null для определенных типов фигур, у которых нет свойств эффекта. Только для чтения [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства заполнения для фигуры. Примечание: может возвращать null для определенных типов фигур, у которых нет свойств заполнения. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки фигуры. Читаемая/записываемая [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту фигуры. Читаемая/записываемая Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Читаемая/записываемая логическая переменная. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для клика мыши. Читаемая/записываемая [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Читаемая/записываемая [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает опцию "Отметить как декоративную". Читаемая/записываемая логическая переменная. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения логическая переменная. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения логическая переменная. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание: может возвращать null для определенных типов фигур, у которых нет свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя фигуры. Не должно быть null. Используйте пустую строку при необходимости. Читаемая/записываемая строка. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в области слайдов. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора фигуры в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнители для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию для слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства сырой рамки фигуры. Читаемая/записываемая [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое заданная фигура поворачивается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Читаемая/записываемая Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 свойства) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд для фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства 3D эффекта для фигуры. Примечание: может возвращать null для определенных типов фигур, у которых нет свойств 3D. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в области презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора фигуры в области слайдов. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину фигуры. Читаемая/записываемая Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает координату x верхнего левого угла фигуры. Читаемая/записываемая Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает координату y верхнего левого угла фигуры. Читаемая/записываемая Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру на задней части порядка z, а Shapes[Shapes.Count - 1] возвращает фигуру на передней части порядка z. Только для чтения Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанные. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | Преобразует устаревшую диаграмму в редактируемую группу фигуры. Созданный объект GroupShape добавляется в родительскую группу фигуры в том же положении. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | Преобразует устаревшую диаграмму в редактируемый объект SmartArt. Созданный объект SmartArt добавляется в родительскую группу фигуры в том же положении. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигура из макета и/или мастер-слайда, от которой унаследована текущая фигура). Если текущая фигура не унаследована, возвращается null. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в файл SVG. |

### See Also

* class [GraphicalObject](../graphicalobject)
* interface [ILegacyDiagram](../ilegacydiagram)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->