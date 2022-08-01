---
title: Ink
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет рукописный объект на слайде.
type: docs
weight: 6900
url: /ru/net/aspose.slides.ink/ink/
---
## Ink class

Представляет рукописный объект на слайде.

```csharp
public class Ink : GraphicalObject, IInk
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/записьString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/записьString . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом режиме отображения.. Чтение/запись[`BlackWhiteMode`](../../aspose.slides/blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество сайтов подключения на фигуре. Только для чтенияInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения[`ICustomData`](../../aspose.slides/icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств эффекта. Только для чтения[`IEffectFormat`](../../aspose.slides/ieffectformat) . |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств заливки. Только для чтения[`IFillFormat`](../../aspose.slides/ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства фрейма формы. Чтение/запись[`IShapeFrame`](../../aspose.slides/ishapeframe) . |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки формы. Только для чтения[`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/записьSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/записьBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для щелчка мыши. Чтение/запись[`IHyperlink`](../../aspose.slides/ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает диспетчер гиперссылок. Только для чтения[`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения курсора. Чтение/запись[`IHyperlink`](../../aspose.slides/ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтенияBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтенияBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств линии. Только для чтения[`ILineFormat`](../../aspose.slides/ilineformat) . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя фигуры. Должно быть не пустым. При необходимости используйте пустое строковое значение. Чтение/записьString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайда. Только для чтенияUInt32 . См. также[`UniqueId`](../../aspose.slides/shape/uniqueid) для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения[`IGroupShape`](../../aspose.slides/igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает значение null, если в фигуре нет заполнителя. Только для чтения[`IPlaceholder`](../../aspose.slides/iplaceholder) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения[`IPresentation`](../../aspose.slides/ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства кадра необработанной формы. Чтение/запись[`IShapeFrame`](../../aspose.slides/ishapeframe) . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает число градусов, на которое указанная фигура поворачивается вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/записьSingle . |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки формы. Только для чтения[`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock) . (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения[`IBaseSlide`](../../aspose.slides/ibaseslide) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, свойства 3D-эффекта для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих 3D-свойств. Только для чтения[`IThreeDFormat`](../../aspose.slides/ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области представления. Только для чтенияUInt32 . См. также[`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) для получения уникального идентификатора формы в области слайдов. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/записьSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x левого верхнего угла фигуры. Чтение/записьSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y левого верхнего угла фигуры. Чтение/записьSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в z-порядке. Shapes[0] возвращает фигуру в конце z-порядка, и Shapes[Shapes.Count - 1] возвращает фигуру в начале z-порядка. order. Только для чтенияInt32 . |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанный. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Возвращает миниатюру фигуры. ShapeThumbnailBounds. Тип границ миниатюры формы используется по умолчанию. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Указывает, что эта фигура не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы в виде файла SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы в виде файла SVG. |

### Смотрите также

* class [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IInk](../iink)
* пространство имен [Aspose.Slides.Ink](../../aspose.slides.ink)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
