---
title: SmartArtShape
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет форму SmartArt
type: docs
weight: 9850
url: /ru/aspose.slides.smartart/smartartshape/
---
## SmartArtShape class

Представляет форму SmartArt

```csharp
public class SmartArtShape : GeometryShape, ISmartArtShape
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает набор значений настройки формы. Только для чтения[`IAdjustValueCollection`](../../aspose.slides/iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/записьString. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/записьString. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом режиме отображения.. Чтение/запись[`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество сайтов соединения на фигуре. Только для чтенияInt32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения[`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, примененные к фигуре. Примечание:может возвращать значение null для определенных типов фигур, не имеющих свойств эффекта. Только для чтения[`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры. Примечание:может возвращать значение null для определенных типов фигур, не имеющих свойств заливки. Только для чтения[`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства фрейма фигуры. Чтение/запись[`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/записьSingle. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/записьBoolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для щелчка мыши. Чтение/запись[`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения[`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись[`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только чтениеBoolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только чтениеBoolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание:может возвращать значение null для определенных типов фигур, не имеющих свойств линии. Только для чтения[`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя формы. Должно быть не пустым. При необходимости используйте пустое строковое значение. Чтение/записьString. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайдов. Только для чтенияUInt32. См. также[`UniqueId`](../../aspose.slides/shape/uniqueid)для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает ноль. Только для чтения[`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если в фигуре нет заполнителя. Только для чтения[`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только чтение[`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства необработанного фрейма формы. Чтение/запись[`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает число градусов, на которое указанная фигура поворачивается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/записьSingle. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения[`IBaseShapeLock`](../../aspose.slides/ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля фигуры. Только для чтения[`IShapeStyle`](../../aspose.slides/ishapestyle). |
| override [ShapeType](../../aspose.slides.smartart/smartartshape/shapetype) { get; set; } | Возвращает или задает тип предустановки геометрии. Примечание:при изменении значения все значения регулировки будут возвращены к значениям по умолчанию. Чтение/запись[`ShapeType`](../../aspose.slides/shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения[`IBaseSlide`](../../aspose.slides/ibaseslide). |
| [TextFrame](../../aspose.slides.smartart/smartartshape/textframe) { get; } | Возвращает текст фигуры SmartArt. Только для чтения[`ITextFrame`](../../aspose.slides/itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который создает свойства 3D-эффекта для фигуры. Примечание:может возвращать значение null для определенных типов фигур, не имеющих 3D-свойств. Только для чтения[`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области представления. Только для чтенияUInt32. См. также[`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)для получения уникального идентификатора фигуры в области слайдов. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/записьSingle. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x левого верхнего угла фигуры. Чтение/записьSingle. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y левого верхнего угла фигуры. Чтение/записьSingle. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает положение фигуры в z-порядке. Shapes[0] возвращает форму в конце z-порядка, и Shapes[Shapes.Count - 1] возвращает форму в начале z-порядка . Только для чтенияInt32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанный. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов формы. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической фигуры. Координаты относятся к левому верхнему углу фигуры. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Возвращает миниатюру формы. ShapeThumbnailBounds.Тип границ эскиза фигуры Shape используется по умолчанию. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию формы из объекта[`IGeometryPath`](../../aspose.slides/igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры. Изменяет тип фигуры ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) наCustom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию формы из массива[`IGeometryPath`](../../aspose.slides/igeometrypath). Координаты должны быть относительно левого верхнего угла фигуры. Изменяет тип фигуры ([`ShapeType`](../../aspose.slides/geometryshape/shapetype)) наCustom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое Shape как файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое Shape как файл SVG. |

### Смотрите также

* class [GeometryShape](../../aspose.slides/geometryshape)
* interface [ISmartArtShape](../ismartartshape)
* пространство имен [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
