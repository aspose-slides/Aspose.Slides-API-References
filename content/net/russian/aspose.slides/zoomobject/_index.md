---  
title: ZoomObject  
second_title: Aspose.Sildes для .NET API Reference  
description: Представляет объект Zoom в слайде.
type: docs  
weight: 11560  
url: /ru/aspose.slides/zoomobject/
---  

## Класс ZoomObject  

Представляет объект Zoom в слайде.  

```csharp  
public class ZoomObject : GraphicalObject, IZoomObject  
```  

## Свойства  

| Имя | Описание |  
| --- | --- |  
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с фигурой. Чтение/запись Строка. |  
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с фигурой. Чтение/запись Строка. |  
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |  
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество соединительных точек на фигуре. Только для чтения Int32. |  
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |  
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств эффекта. Только для чтения [`IEffectFormat`](../ieffectformat). |  
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заливки для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств заливки. Только для чтения [`IFillFormat`](../ifillformat). |  
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |  
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). |  
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту фигуры. Чтение/запись Единичное число. |  
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Логическое. |  
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для клика мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |  
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |  
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |  
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Получает или устанавливает тип изображения объекта зума. Чтение/запись [`ZoomImageType`](../zoomimagetype). Значение по умолчанию: Preview |  
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает параметр "Отметить как декоративный" Чтение/запись Логическое. |  
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Логическое. |  
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Логическое. |  
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |  
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя фигуры. Не должно быть null. Используйте пустую строку, если необходимо. Чтение/запись Строка. |  
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в области слайда. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора фигуры в области презентации. |  
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |  
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если фигура не имеет заполнитель. Только для чтения [`IPlaceholder`](../iplaceholder). |  
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |  
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает сырые свойства рамки фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |  
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Получает или устанавливает поведение навигации в режиме слайд-шоу. Чтение/запись Логическое. Значение по умолчанию: false |  
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое указанные фигуры повернуты вокруг оси z. Положительное значение указывает на поворот по часовой стрелке; отрицательное значение указывает на против часовой стрелки. Чтение/запись Единичное число. |  
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 свойства) |  
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Получает или устанавливает значение, указывающее, будет ли Zoom использовать фон целевого слайда. Чтение/запись Логическое. Значение по умолчанию: true |  
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |  
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства 3D эффектов для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют 3D свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |  
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Получает или устанавливает продолжительность перехода между Zoom и слайдом. Чтение/запись Единичное число. Значение по умолчанию: 1.0f |  
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в области презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора фигуры в области слайда. |  
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину фигуры. Чтение/запись Единичное число. |  
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает координату x верхнего левого угла фигуры. Чтение/запись Единичное число. |  
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает координату y верхнего левого угла фигуры. Чтение/запись Единичное число. |  
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Получает или устанавливает изображение для объекта зума. Чтение/запись [`IPPImage`](../ippimage). |  
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке z. Shapes[0] возвращает фигуру на заднем плане, а Shapes[Shapes.Count - 1] возвращает фигуру на переднем плане. Только для чтения Int32. |  

## Методы  

| Имя | Описание |  
| --- | --- |  
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанные. |  
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигура из макета и/или главного слайда, от которой наследуется текущая фигура). Если текущая фигура не наследуется, возвращается null. |  
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |  
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |  
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |  
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в виде SVG-файла. |  
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в виде SVG-файла. |  

### См. также  

* класс [GraphicalObject](../graphicalobject)  
* интерфейс [IZoomObject](../izoomobject)  
* пространство имен [Aspose.Slides](../../aspose.slides)  
* сборка [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  