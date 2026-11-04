---
title: SummaryZoomSection
second_title: Aspose.Sildes для .NET справка API
description: Представляет объект Summary Zoom Section в кадре Summary Zoom.
type: docs
weight: 10800
url: /ru/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection класс

Представляет объект Summary Zoom Section в кадре Summary Zoom.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Свойства

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задаёт альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задаёт заголовок альтернативного текста, связанный с фигурой. Чтение/запись String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отображаться в режиме черно-белого отображения. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество соединительных точек на фигуре. Только чтение Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только чтение [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Возвращает текстовое описание объекта Summary Zoom Section. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к фигуре. Примечание: может возвращать null для некоторых типов фигур, которые не имеют свойств эффекта. Только чтение [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства заполнения для фигуры. Примечание: может возвращать null для некоторых типов фигур, которые не имеют свойств заполнения. Только чтение [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задаёт свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только чтение [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Получает или задаёт высоту фигуры, измеренную в пунктах. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задаёт гиперссылку, определённую для клика мышью. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только чтение [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задаёт гиперссылку, определённую для наведения мышью. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Получает или задаёт тип изображения объекта зума. Чтение/запись [`ZoomImageType`](../zoomimagetype). Значение по умолчанию: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или задаёт параметр «Mark as decorative». Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, является ли фигура сгруппированной. Только чтение Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только чтение Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры. Примечание: может возвращать null для некоторых типов фигур, которые не имеют свойств линии. Только чтение [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задаёт имя фигуры. Должно быть не null. При необходимости используйте значение пустой строки. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Возвращает уникальный идентификатор в диапазоне слайда, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любой части документа. Только чтение UInt32. См. также [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает объект GroupShape-родитель, если фигура сгруппирована. В противном случае возвращает null. Только чтение [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель (placeholder) для фигуры. Возвращает null, если у фигуры нет заполнителя. Только чтение [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает презентацию-родитель слайда. Только чтение [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задаёт свойства исходной рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Получает или задаёт поведение навигации в слайд-шоу. Чтение/запись Boolean. Значение по умолчанию: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задаёт количество градусов, на которое указанная фигура вращается вокруг оси z. Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только чтение [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 свойства) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Получает или задаёт значение, указывающее, будет ли Zoom использовать фон целевого слайда. Чтение/запись Boolean. Значение по умолчанию: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает слайд-родитель фигуры. Только чтение [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Получает или задаёт объект раздела, к которому привязан объект Section Zoom. Чтение/запись [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффекта для фигуры. Примечание: может возвращать null для некоторых типов фигур, которые не имеют 3D-свойств. Только чтение [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Возвращает текстовый заголовок объекта Summary Zoom Section. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Получает или задаёт продолжительность перехода между Zoom и слайдом. Чтение/запись Single. Значение по умолчанию: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Возвращает внутренний идентификатор в диапазоне презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только чтение UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Получает или задаёт ширину фигуры, измеренную в пунктах. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Получает или задаёт координату x левого верхнего угла фигуры, измеренную в пунктах. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Получает или задаёт координату y левого верхнего угла фигуры, измеренную в пунктах. Чтение/запись Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Получает или задаёт изображение для объекта зума. Чтение/запись [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке слоёв (z-order). Shapes[0] возвращает фигуру, находящуюся сзади в порядке слоёв, а Shapes[Shapes.Count - 1] возвращает фигуру, находящуюся спереди. Только чтение Int32. |

## Методы

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый placeholder, если его нет, и задаёт свойства placeholder указанному. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру placeholder (фигуру из макета и/или мастер-слайда, от которой наследуется текущая фигура). Возвращает null, если текущая фигура не наследуется. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Получает визуальные границы фигуры, вычисленные из её отрисованного содержимого. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры как файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры как файл SVG. |

### См. также

* класс [SectionZoomFrame](../sectionzoomframe)
* интерфейс [ISummaryZoomSection](../isummaryzoomsection)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->