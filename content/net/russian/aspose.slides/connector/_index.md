---
title: Connector
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет собой соединительный элемент.
type: docs
weight: 2580
url: /ru/aspose.slides/connector/
---

## Класс Коннектор

Представляет собой соединительный элемент.

```csharp
public class Connector : GeometryShape, IConnector
```

## Свойства

| Название | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает коллекцию значений настроек фигуры. Только для чтения [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Читаемое/записываемое String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Читаемое/записываемое String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство задает, как фигура будет отображаться в черно-белом режиме.. Читаемое/записываемое [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек подключения на фигуре. Только для чтения Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Возвращает замки соединителя. Только для чтения [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Возвращает или задает фигуру для привязки конца соединителя. Читаемое/записываемое [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Возвращает или задает индекс точки подключения для конечной фигуры. Читаемое/записываемое UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заполнения для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств заполнения. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства рамки фигуры. Читаемое/записываемое [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Читаемое/записываемое Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Читаемое/записываемое Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для щелчка мыши. Читаемое/записываемое [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения мыши. Читаемое/записываемое [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или задает опцию "Отметить как декоративную". Читаемое/записываемое Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств линий. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя фигуры. Не должно быть null. Используйте пустую строку при необходимости. Читаемое/записываемое String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в области слайда. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора фигуры в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если фигура не имеет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства сырой рамки фигуры. Читаемое/записываемое [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает количество градусов, на которое указанная фигура повернута вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Читаемое/записываемое Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Возвращает замки фигуры. Только для чтения [`IConnectorLock`](../iconnectorlock). (2 свойства) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля фигуры. Только для чтения [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Возвращает или задает тип AutoShape. Читаемое/записываемое [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Возвращает или задает фигуру для привязки начала соединителя. Читаемое/записываемое [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Возвращает или задает индекс точки подключения для начальной фигуры. Читаемое/записываемое UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства 3D эффектов для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет 3D свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в области презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора фигуры в области слайда. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Читаемое/записываемое Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x верхнего левого угла фигуры. Читаемое/записываемое Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y верхнего левого угла фигуры. Читаемое/записываемое Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру, находящуюся на заднем плане порядка z, а Shapes[Shapes.Count - 1] возвращает фигуру, находящуюся на переднем плане порядка z. Только для чтения Int32. |

## Методы

| Название | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанные. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов фигуры. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигура из макета и/или основного слайда, от которого наследуется текущая фигура). Если текущая фигура не наследуется, возвращается null. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической фигуры. Координаты относительно верхнего левого угла фигуры. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. Тип границ миниатюры ShapeThumbnailBounds.Shape используется по умолчанию. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [Reroute](../../aspose.slides/connector/reroute)() | Перенаправляет соединитель так, чтобы он принимал кратчайший возможный путь между фигурами, которые он соединяет. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию фигуры из объекта [`IGeometryPath`](../igeometrypath). Координаты должны быть относительно верхнего левого угла фигуры. Изменяет тип фигуры ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию фигуры из массива [`IGeometryPath`](../igeometrypath). Координаты должны быть относительно верхнего левого угла фигуры. Изменяет тип фигуры ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в виде файла SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в виде файла SVG. |

### См. также

* класс [GeometryShape](../geometryshape)
* интерфейс [IConnector](../iconnector)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->