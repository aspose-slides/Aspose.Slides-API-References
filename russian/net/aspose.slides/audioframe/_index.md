---
title: AudioFrame
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет аудиоклип на слайде.
type: docs
weight: 770
url: /ru/net/aspose.slides/audioframe/
---
## AudioFrame class

Представляет аудиоклип на слайде.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает набор значений настройки фигуры. Только для чтения[`IAdjustValueCollection`](../iadjustvaluecollection) . |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/записьString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/записьString . |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Возвращает или устанавливает индекс последней дорожки Чтение/записьInt32 . |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Возвращает или устанавливает время последней дорожки. Чтение/записьInt32 . |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Возвращает или задает индекс начальной дорожки. Чтение/записьInt32 . |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Возвращает или устанавливает время начала трека. Чтение/записьInt32 . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом режиме отображения.. Чтение/запись[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество сайтов подключения на фигуре. Только для чтенияInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств эффекта. Только для чтения[`IEffectFormat`](../ieffectformat) . |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Определяет, встроен ли звук в презентацию. Только для чтенияBoolean . |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Возвращает или устанавливает встроенный звуковой объект. Чтение/запись[`IAudio`](../iaudio) . |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств заливки. Только для чтения[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства фрейма формы. Чтение/запись[`IShapeFrame`](../ishapeframe) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/записьSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/записьBoolean . |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Определяет, скрыт ли AudioFrame. Чтение/записьBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для щелчка мыши. Чтение/запись[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает диспетчер гиперссылок. Только для чтения[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения курсора. Чтение/запись[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтенияBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтенияBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств линии. Только для чтения[`ILineFormat`](../ilineformat) . |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Возвращает или задает имя аудиофайла, связанного с AudioFrame. Чтение/записьString . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя фигуры. Должно быть не пустым. При необходимости используйте пустое строковое значение. Чтение/записьString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайда. Только для чтенияUInt32 . См. также[`UniqueId`](../shape/uniqueid) для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения[`IGroupShape`](../igroupshape) . |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Возвращает объект PictureFillFormat для рамки изображения. Только для чтения[`IPictureFillFormat`](../ipicturefillformat) . |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Возвращает блокировки формы. Только для чтения[`IPictureFrameLock`](../ipictureframelock) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает значение null, если в фигуре нет заполнителя. Только для чтения[`IPlaceholder`](../iplaceholder) . |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Определяет, воспроизводится ли звук на слайдах. Чтение/записьBoolean . |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Определяет, зациклено ли аудио. Чтение/записьBoolean . |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Возвращает или устанавливает режим воспроизведения аудио. Чтение/запись[`AudioPlayModePreset`](../audioplaymodepreset) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства кадра необработанной формы. Чтение/запись[`IShapeFrame`](../ishapeframe) . |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Возвращает или задает масштаб высоты (относительно исходного размера изображения) рамки изображения. Значение 1.0 соответствует 100%. Чтение/записьSingle . |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Возвращает или задает масштаб ширины (относительно исходного размера изображения) рамки изображения. Значение 1.0 соответствует 100%. Чтение/записьSingle . |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Определяет, будет ли звук автоматически перематываться назад после воспроизведения. Чтение/записьBoolean . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает число градусов, на которое указанная фигура поворачивается вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/записьSingle . |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Возвращает блокировки формы. Только для чтения[`IPictureFrameLock`](../ipictureframelock) . (2 properties) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля формы. Только для чтения[`IShapeStyle`](../ishapestyle) . |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Возвращает или задает тип AutoShape для PictureFrame. Допустимы все элементы набора[`ShapeType`](../shapetype), кроме всяких строк: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения[`IBaseSlide`](../ibaseslide) . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, свойства 3D-эффекта для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих 3D-свойств. Только для чтения[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области представления. Только для чтенияUInt32 . См. также[`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора формы в области слайдов. |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Возвращает или устанавливает громкость звука. Чтение/запись[`AudioVolumeMode`](../audiovolumemode) . |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину фигуры. Чтение/записьSingle . |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x левого верхнего угла фигуры. Чтение/записьSingle . |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y левого верхнего угла фигуры. Чтение/записьSingle . |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в z-порядке. Shapes[0] возвращает фигуру в конце z-порядка, и Shapes[Shapes.Count - 1] возвращает фигуру в начале z-порядка. order. Только для чтенияInt32 . |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанный. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов фигуры. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической формы. Координаты указаны относительно левого верхнего угла фигуры. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)() | Возвращает миниатюру фигуры. ShapeThumbnailBounds. Тип границ миниатюры формы используется по умолчанию. |
| [GetThumbnail](../../aspose.slides/shape/getthumbnail)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Указывает, что эта фигура не является заполнителем. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию формы из[`IGeometryPath`](../igeometrypath) объект. Координаты должны указываться относительно левого верхнего угла фигуры. Изменяет тип фигуры ([`ShapeType`](../geometryshape/shapetype) ) кCustom . |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию формы из массива[`IGeometryPath`](../igeometrypath). Координаты должны указываться относительно левого верхнего угла фигуры. Изменяет тип фигуры ([`ShapeType`](../geometryshape/shapetype) ) кCustom . |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы в виде файла SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы в виде файла SVG. |

### Смотрите также

* class [PictureFrame](../pictureframe)
* interface [IAudioFrame](../iaudioframe)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
