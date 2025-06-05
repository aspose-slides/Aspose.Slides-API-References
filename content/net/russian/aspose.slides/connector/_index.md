---
title: Connector
second_title: Aspose.Sildes для .NET Справочник API
description: Представляет соединитель.
type: docs
weight: 2580
url: /ru/aspose.slides/connector/
---

## Класс Connector

Представляет соединитель.

```csharp
public class Connector : GeometryShape, IConnector
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает коллекцию значений корректировок формы. Только для чтения [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с формой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с формой. Чтение/запись String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство, которое определяет, как форма будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество соединительных узлов на форме. Только для чтения Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Возвращает замки соединителя. Только для чтения [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные формы. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, применяемые к форме. Примечание: может вернуть null для определенных типов форм, которые не имеют свойств эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Возвращает или устанавливает форму, к которой необходимо присоединить конец соединителя. Чтение/запись [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Возвращает или устанавливает индекс соединительного узла для конечной формы. Чтение/запись UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заливки для формы. Примечание: может вернуть null для определенных типов форм, которые не имеют свойств заливки. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту формы. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли форма. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для щелчка мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает опцию «Отметить как декоративную» Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли форма. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли форма TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для формы. Примечание: может вернуть null для определенных типов форм, которые не имеют свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя формы. Не должно быть null. Используйте пустую строку, если это необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайда. Только для чтения UInt32. Смотрите также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если форма сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнение для формы. Возвращает null, если у формы нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства необработанной рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое указанная форма повернута вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Возвращает замки формы. Только для чтения [`IConnectorLock`](../iconnectorlock). (2 свойства) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля формы. Только для чтения [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Возвращает или устанавливает тип AutoShape. Чтение/запись [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд формы. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Возвращает или устанавливает форму, к которой нужно прикрепить начало соединителя. Чтение/запись [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Возвращает или устанавливает индекс соединительного узла для начальной формы. Чтение/запись UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства эффектов 3D для формы. Примечание: может вернуть null для определенных типов форм, которые не имеют свойств 3D. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области презентации. Только для чтения UInt32. Смотрите также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора формы в области слайда. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину формы. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает координату x верхнего левого угла формы. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает координату y верхнего левого угла формы. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию формы в порядке Z. Shapes[0] возвращает форму на заднем плане, а Shapes[Shapes.Count - 1] возвращает форму на переднем плане. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя для указанного. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов формы. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую форму заполнителя (форму из макета и/или мастер-слайда, от которой наследуется текущая форма). Возвращает null, если текущая форма не наследуется. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической формы. Координаты относительны к верхнему левому углу формы. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру формы. Тип миниатюры ShapeThumbnailBounds.Shape используется по умолчанию. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта форма не является заполнителем. |
| [Reroute](../../aspose.slides/connector/reroute)() | Перенаправляет соединитель, чтобы он проходил по кратчайшему возможному маршруту между соединяемыми формами. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию формы из объекта [`IGeometryPath`](../igeometrypath). Координаты должны быть относительны к верхнему левому углу формы. Меняет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию формы из массива [`IGeometryPath`](../igeometrypath). Координаты должны быть относительны к верхнему левому углу формы. Меняет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы в виде SVG-файла. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы в виде SVG-файла. |

### См. также

* класс [GeometryShape](../geometryshape)
* интерфейс [IConnector](../iconnector)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->