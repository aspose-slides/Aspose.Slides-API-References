---
title: VideoFrame
second_title: Aspose.Sildes для .NET API Reference
description: Представляет видеоклип на слайде.
type: docs
weight: 11410
url: /ru/aspose.slides/videoframe/
---

## VideoFrame class

Представляет видеоклип на слайде.

```csharp
public class VideoFrame : PictureFrame, IVideoFrame
```

## Properties

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает коллекцию значений корректировок формы. Только для чтения [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с формой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с формой. Чтение/запись String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как форма будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [CaptionTracks](../../aspose.slides/videoframe/captiontracks) { get; } | Возвращает коллекцию субтитров видео. Только для чтения [`ICaptionsCollection`](../icaptionscollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек подключения на форме. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные формы. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к форме. Примечание: может возвращать null для некоторых типов форм, которые не имеют свойств эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [EmbeddedVideo](../../aspose.slides/videoframe/embeddedvideo) { get; set; } | Возвращает или устанавливает встроенный объект видео. Чтение/запись [`IVideo`](../ivideo). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства форматирования заливки для формы. Примечание: может возвращать null для некоторых типов форм, которые не имеют свойств заливки. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [FullScreenMode](../../aspose.slides/videoframe/fullscreenmode) { get; set; } | Определяет, показывается ли видео в полноэкранном режиме. Чтение/запись Boolean. |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту формы. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли форма. Чтение/запись Boolean. |
| [HideAtShowing](../../aspose.slides/videoframe/hideatshowing) { get; set; } | Определяет, скрыт ли VideoFrame. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для клика мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Определяет, является ли PictureFrame объектом Cameo или нет. Только для чтения Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает опцию 'Отметить как декоративный' Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли форма. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли форма TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, содержащий свойства форматирования линии для формы. Примечание: может возвращать null для некоторых типов форм, которые не имеют свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/videoframe/linkpathlong) { get; set; } | Возвращает или устанавливает имя файла видео, связанного с VideoFrame. Чтение/запись String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя формы. Не должен быть null. Используйте пустую строку, если необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайда. Только для чтения UInt32. Также смотрите [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если форма сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Возвращает объект PictureFillFormat для рамки изображения. Только для чтения [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Возвращает блокировки формы. Только для чтения [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для формы. Возвращает null, если у формы нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [PlayLoopMode](../../aspose.slides/videoframe/playloopmode) { get; set; } | Определяет, зациклено ли видео. Чтение/запись Boolean. |
| [PlayMode](../../aspose.slides/videoframe/playmode) { get; set; } | Возвращает или устанавливает режим воспроизведения видео. Чтение/запись [`VideoPlayModePreset`](../videoplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства сырой рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Возвращает или устанавливает масштаб высоты (по отношению к оригинальному размеру изображения) рамки изображения. Значение 1.0 соответствует 100%. Чтение/запись Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Возвращает или устанавливает масштаб ширины (по отношению к оригинальному размеру изображения) рамки изображения. Значение 1.0 соответствует 100%. Чтение/запись Single. |
| [RewindVideo](../../aspose.slides/videoframe/rewindvideo) { get; set; } | Определяет, перематывается ли видео автоматически в начало, как только фильм закончился. Чтение/запись Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое заданная форма повёрнута вокруг оси z. Положительное значение указывает на поворот по часовой стрелке; отрицательное значение указывает на поворот против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Возвращает блокировки формы. Только для чтения [`IPictureFrameLock`](../ipictureframelock). (2 свойства) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля формы. Только для чтения [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Возвращает или устанавливает тип AutoShape для PictureFrame. Все элементы набора [`ShapeType`](../shapetype) допустимы, кроме всех видов линий: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд формы. Только для чтения [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства 3d эффектов для формы. Примечание: может возвращать null для некоторых типов форм, которые не имеют свойств 3d. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/videoframe/trimfromend) { get; set; } | Удалить конец [мс] |
| [TrimFromStart](../../aspose.slides/videoframe/trimfromstart) { get; set; } | Удалить начало [мс] |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области презентации. Только для чтения UInt32. Также смотрите [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора формы в области слайда. |
| [Volume](../../aspose.slides/videoframe/volume) { get; set; } | Возвращает или устанавливает громкость звука. Чтение/запись [`AudioVolumeMode`](../audiovolumemode). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину формы. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает x-координату верхнего левого угла формы. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает y-координату верхнего левого угла формы. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию формы в порядке z. Shapes[0] возвращает форму в задней части порядка z, а Shapes[Shapes.Count - 1] возвращает форму в передней части порядка z. Только для чтения Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя для заданного. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов формы. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую форму-заполнитель (форму из компоновки и/или шаблона слайда, от которой наследуется текущая форма). Возвращается null, если текущая форма не наследуется. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической формы. Координаты относительно верхнего левого угла формы. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру формы. Тип границ миниатюры ShapeThumbnailBounds.Shape используется по умолчанию. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта форма не является заполнителем. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию формы из объекта [`IGeometryPath`](../igeometrypath). Координаты должны быть относительно верхнего левого угла формы. Меняет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию формы из массива [`IGeometryPath`](../igeometrypath). Координаты должны быть относительно верхнего левого угла формы. Меняет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы в SVG файл. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы в SVG файл. |

### See Also

* class [PictureFrame](../pictureframe)
* interface [IVideoFrame](../ivideoframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->