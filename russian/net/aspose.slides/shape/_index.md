---
title: Shape
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет фигуру на слайде.
type: docs
weight: 9060
url: /ru/net/aspose.slides/shape/
---
## Shape class

Представляет фигуру на слайде.

```csharp
public class Shape : IShape
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/записьString. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/записьString. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом режиме отображения.. Чтение/запись[`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество сайтов соединения на фигуре. Только для чтенияInt32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения[`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, примененные к фигуре. Примечание:может возвращать значение null для определенных типов фигур, не имеющих свойств эффекта. Только для чтения[`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры. Примечание:может возвращать значение null для определенных типов фигур, не имеющих свойств заливки. Только для чтения[`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства фрейма фигуры. Чтение/запись[`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/записьSingle. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/записьBoolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для щелчка мыши. Чтение/запись[`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения[`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись[`IHyperlink`](../ihyperlink). |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только чтениеBoolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только чтениеBoolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание:может возвращать значение null для определенных типов фигур, не имеющих свойств линии. Только для чтения[`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя формы. Должно быть не пустым. При необходимости используйте пустое строковое значение. Чтение/записьString. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайдов. Только для чтенияUInt32. См. также[`UniqueId`](./uniqueid)для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает ноль. Только для чтения[`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если в фигуре нет заполнителя. Только для чтения[`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только чтение[`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства необработанного фрейма формы. Чтение/запись[`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает число градусов, на которое указанная фигура поворачивается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/записьSingle. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения[`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения[`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который создает свойства 3D-эффекта для фигуры. Примечание:может возвращать значение null для определенных типов фигур, не имеющих 3D-свойств. Только для чтения[`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области представления. Только для чтенияUInt32. См. также[`OfficeInteropShapeId`](./officeinteropshapeid)для получения уникального идентификатора фигуры в области слайдов. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/записьSingle. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x левого верхнего угла фигуры. Чтение/записьSingle. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y левого верхнего угла фигуры. Чтение/записьSingle. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает положение фигуры в z-порядке. Shapes[0] возвращает форму в конце z-порядка, и Shapes[Shapes.Count - 1] возвращает форму в начале z-порядка . Только для чтенияInt32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанный. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail#getthumbnail)() | Возвращает миниатюру формы. ShapeThumbnailBounds.Тип границ эскиза фигуры Shape используется по умолчанию. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail#getthumbnail_1)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Сохраняет содержимое Shape как файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое Shape как файл SVG. |

### Смотрите также

* interface [IShape](../ishape)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
