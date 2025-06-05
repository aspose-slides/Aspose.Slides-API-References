---
title: SmartArtShape
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет фигуру SmartArt
type: docs
weight: 10350
url: /ru/aspose.slides.smartart/smartartshape/
---

## Класс SmartArtShape

Представляет фигуру SmartArt

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Свойства

| Название | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает коллекцию значений корректировки фигуры. Только для чтения [`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/запись String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отображаться в черно-белом режиме.. Чтение/запись [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек подключения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, применяемые к фигуре. Примечание: может вернуть null для определенных типов фигур, у которых нет свойств эффектов. Только для чтения [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заливки для фигуры. Примечание: может вернуть null для определенных типов фигур, у которых нет свойств заливки. Только для чтения [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для клика мыши. Чтение/запись [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает параметр «Отметить как декоративный». Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для фигуры. Примечание: может вернуть null для определенных типов фигур, у которых нет свойств линий. Только для чтения [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя фигуры. Не должно быть null. Используйте пустую строку, если необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в рамках слайда. Только для чтения UInt32. См. также [`UniqueId`](../../aspose.slides/shape/uniqueid) для получения уникального идентификатора фигуры в рамках презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнители для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства необработанной рамки фигуры. Чтение/запись [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает угол поворота фигуры вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля фигуры. Только для чтения [`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Возвращает или задает тип геометрического пресета. Примечание: при изменении значения все значения корректировки будут сброшены к своим умолчаниям. Чтение/запись [`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Возвращает текст фигуры SmartArt. Только для чтения [`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который имеет свойства 3D-эффектов для фигуры. Примечание: может вернуть null для определенных типов фигур, у которых нет свойств 3D. Только для чтения [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в рамках презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) для получения уникального идентификатора фигуры в рамках слайда. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x левого верхнего угла фигуры. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y левого верхнего угла фигуры. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в z-порядке. Shapes[0] возвращает фигуру в задней части z-порядка, а Shapes[Shapes.Count - 1] возвращает фигуру в передней части z-порядка. Только для чтения Int32. |

## Методы

| Название | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанные. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов фигуры. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигуру из макета и/или мастер-слайда, от которой наследуется текущая фигура). Если текущая фигура не наследуется, возвращается null. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической фигуры. Координаты относительны к левому верхнему углу фигуры. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию фигуры из объекта [`IGeometryPath`](../../aspose.slides/igeometrypath). Координаты должны быть относительными к левому верхнему углу фигуры. Изменяет тип фигуры ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) на Пользовательский. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию фигуры из массива [`IGeometryPath`](../../aspose.slides/igeometrypath). Координаты должны быть относительными к левому верхнему углу фигуры. Изменяет тип фигуры ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) на Пользовательский. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в файл SVG. |

### Также см.

* класс [GeometryShape](../../aspose.slides/geometryshape)
* интерфейс [ISmartArtShape](../ismartartshape)
* пространство имен [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->