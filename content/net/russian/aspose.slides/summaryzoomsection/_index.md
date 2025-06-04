---
title: SummaryZoomSection
second_title: Aspose.Slides для .NET API Справочник
description: Представляет объект раздела Сводного Увеличения в рамке Сводного Увеличения.
type: docs
weight: 10470
url: /ru/aspose.slides/summaryzoomsection/
---

## Класс SummaryZoomSection

Представляет объект раздела Сводного Увеличения в рамке Сводного Увеличения.

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## Свойства

| Название | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с фигурой. Читаемый/записываемый String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с фигурой. Читаемый/записываемый String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство, указывающее, как фигура будет отображаться в черно-белом режиме. Читаемый/записываемый [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество соединительных точек на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | Возвращает текстовое описание объекта раздела Сводного Увеличения. |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, примененные к фигуре. Примечание: может вернуть null для определенных типов фигур, не имеющих эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства заполнения фигуры. Примечание: может вернуть null для определенных типов фигур, не имеющих свойств заполнения. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки фигуры. Читаемый/записываемый [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту фигуры. Читаемый/записываемый Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Читаемый/записываемый Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для клика мышью. Читаемый/записываемый [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Читаемый/записываемый [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Получает или устанавливает тип изображения объекта увеличения. Читаемый/записываемый [`ZoomImageType`](../zoomimagetype). Значение по умолчанию: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает опцию 'Отметить как декоративный' Читаемый/записываемый Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание: может вернуть null для определенных типов фигур, не имеющих линий. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя фигуры. Не должно быть равно null. Используйте пустую строку, если необходимо. Читаемый/записываемый String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в рамках слайда. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора фигуры в рамках презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнители для фигуры. Возвращает null, если у фигуры нет заполнителей. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства исходной рамки фигуры. Читаемый/записываемый [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Получает или устанавливает поведение навигации в режиме слайд-шоу. Читаемый/записываемый Boolean. Значение по умолчанию: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое заданная фигура вращается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на против часовой стрелки. Читаемый/записываемый Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 свойства) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Получает или устанавливает значение, которое указывает, будет ли Зум использовать фон целевого слайда. Читаемый/записываемый Boolean. Значение по умолчанию: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Получает или устанавливает объект раздела, к которому Сводный Увеличенный объект ссылается. Читаемый/записываемый [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства 3D-эффектов для фигуры. Примечание: может вернуть null для определенных типов фигур, не имеющих 3D-свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | Возвращает текстовый заголовок объекта раздела Сводного Увеличения. |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Получает или устанавливает продолжительность перехода между Зумом и слайдом. Читаемый/записываемый Single. Значение по умолчанию: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в рамках презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора фигуры в рамках слайда. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину фигуры. Читаемый/записываемый Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает x-координату верхнего левого угла фигуры. Читаемый/записываемый Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает y-координату верхнего левого угла фигуры. Читаемый/записываемый Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Получает или устанавливает изображение для объекта увеличения. Читаемый/записываемый [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру на заднем плане z-упорядочивания, а Shapes[Shapes.Count - 1] возвращает фигуру на переднем плане z-упорядочивания. Только для чтения Int32. |

## Методы

| Название | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанные. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую форму заполнителя (фигура из макета и/или основного слайда, от которой наследуется текущая фигура). Возвращает null, если текущая фигура не является производной. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в формате SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в формате SVG. |

### См. также

* класс [SectionZoomFrame](../sectionzoomframe)
* интерфейс [ISummaryZoomSection](../isummaryzoomsection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->