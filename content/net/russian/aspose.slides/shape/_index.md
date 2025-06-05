---
title: Shape
second_title: Aspose.Slidес для .NET API Reference
description: Представляет форму на слайде.
type: docs
weight: 9520
url: /ru/aspose.slides/shape/
---

## Shape class

Представляет форму на слайде.

```csharp
public class Shape : IShape
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с формой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с формой. Чтение/запись String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как форма будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек подключения на форме. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные формы. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к форме. Примечание: может возвращать null для определенных типов форм, у которых нет свойств эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заливки для формы. Примечание: может возвращать null для определенных типов форм, у которых нет свойств заливки. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту формы. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли форма. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для клика мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает параметр "Отметить как декоративный" Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли форма. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли форма TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для формы. Примечание: может возвращать null для определенных типов форм, у которых нет свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя формы. Не должно быть null. Используйте пустую строку, если необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайдов. Только для чтения UInt32. Также смотрите [`UniqueId`](./uniqueid) для получения уникального идентификатора формы в объеме презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если форма сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для формы. Возвращает null, если у формы нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства сырой рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое указанная форма вращается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Возвращает блокировки формы. Только для чтения [`IBaseShapeLock`](../ibaseshapelock). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд формы. Только для чтения [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для формы. Примечание: может возвращать null для определенных типов форм, у которых нет 3D-свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области презентации. Только для чтения UInt32. Также смотрите [`OfficeInteropShapeId`](./officeinteropshapeid) для получения уникального идентификатора формы в области слайдов. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину формы. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает координату x в верхнем левом углу формы. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает координату y в верхнем левом углу формы. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию формы в z-порядке. Shapes[0] возвращает форму в задней части z-порядка, а Shapes[Shapes.Count - 1] возвращает форму в передней части z-порядка. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанный. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую форму-заполнитель (форму из макета и/или мастер-слайда, от которой унаследована текущая форма). Возвращает null, если текущая форма не унаследована. |
| [GetImage](../../aspose.slides/shape/getimage#getimage)() | Возвращает миниатюру формы. По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта форма не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg)(Stream) | Сохраняет содержимое формы как файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Сохраняет содержимое формы как файл SVG. |

### Смотрите также

* интерфейс [IShape](../ishape)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->