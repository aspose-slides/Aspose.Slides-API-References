---
title: AutoShape
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет AutoShape.
type: docs
weight: 820
url: /ru/aspose.slides/autoshape/
---

## AutoShape class

Представляет AutoShape.

```csharp
public sealed class AutoShape : GeometryShape, IAutoShape
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает коллекцию значений корректировок формы. Только для чтения [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с формой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с формой. Чтение/запись String. |
| [AutoShapeLock](../../aspose.slides/autoshape/autoshapelock) { get; } | Возвращает блокировки автопечати. Только для чтения [`IAutoShapeLock`](../iautoshapelock). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как форма будет отображаться в черно-белом режиме отображения. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек подключения на форме. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные формы. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к форме. Примечание: может вернуть null для определенных типов форм, которые не имеют свойств эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства заполнения для формы. Примечание: может вернуть null для определенных типов форм, которые не имеют свойств заполнения. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту формы. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли форма. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для щелчка мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или задает опцию 'Пометить как декоративный' Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли форма. Только для чтения Boolean. |
| [IsTextBox](../../aspose.slides/autoshape/istextbox) { get; } | Указывает, является ли форма текстовым полем. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли форма TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для формы. Примечание: может вернуть null для определенных типов форм, которые не имеют свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя формы. Не должно быть пустым. Используйте пустую строку при необходимости. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайда. Только для чтения UInt32. Смотрите также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает объект GroupShape родительской группы, если форма сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнител для формы. Возвращает null, если у формы нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства сырой рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает количество градусов, на которое заданная форма поворачивается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/autoshape/shapelock) { get; } | Возвращает блокировки формы. Только для чтения [`IAutoShapeLock`](../iautoshapelock). (2 свойства) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля формы. Только для чтения [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Возвращает или задает тип геометрического пресета. Примечание: при изменении значения все значения коррекции будут сброшены на значения по умолчанию. Чтение/запись [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд формы. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [TextFrame](../../aspose.slides/autoshape/textframe) { get; } | Возвращает объект TextFrame для AutoShape. Только для чтения [`ITextFrame`](../itextframe). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства эффектов 3D для формы. Примечание: может вернуть null для определенных типов форм, которые не имеют 3D свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области презентации. Только для чтения UInt32. Смотрите также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора формы в области слайда. |
| [UseBackgroundFill](../../aspose.slides/autoshape/usebackgroundfill) { get; set; } | Определяет, должна ли эта автопечать заполняться фоном слайда вместо указанного в стиле или формате заливки. Чтение/запись Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину формы. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x верхнего левого угла формы. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y верхнего левого угла формы. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию формы в порядке Z. Shapes[0] возвращает форму в задней части порядка Z, а Shapes[Shapes.Count - 1] возвращает форму в передней части порядка Z. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и задает свойства заполнителя на указанные. |
| [AddTextFrame](../../aspose.slides/autoshape/addtextframe)(string) | Добавляет новый TextFrame к форме. Если у формы уже есть TextFrame, то просто изменяет его текст. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов формы. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую заполнителя формы (форма из макета и/или мастер-слайда, от которой наследуется текущая форма). Возвращает null, если текущая форма не наследуется. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической формы. Координаты относительны к левому верхнему углу формы. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру формы. Тип границ ShapeThumbnailBounds.Shape по умолчанию используется. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта форма не является заполнителем. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию формы из объекта [`IGeometryPath`](../igeometrypath). Координаты должны быть относительны к левому верхнему углу формы. Меняет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию формы из массива [`IGeometryPath`](../igeometrypath). Координаты должны быть относительны к левому верхнему углу формы. Меняет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы как файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы как файл SVG. |

### См. также

* класс [GeometryShape](../geometryshape)
* интерфейс [IAutoShape](../iautoshape)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->