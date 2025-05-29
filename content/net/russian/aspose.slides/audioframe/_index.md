---
title: AudioFrame
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет аудиоклип на слайде.
type: docs
weight: 790
url: /ru/aspose.slides/audioframe/
---

## Класс AudioFrame

Представляет аудиоклип на слайде.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает коллекцию значений корректировки фигуры. Только для чтения [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с фигурой. Читаемое/записываемое String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с фигурой. Читаемое/записываемое String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Возвращает или устанавливает индекс последнего трека. Читаемое/записываемое Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Возвращает или устанавливает время последнего трека. Читаемое/записываемое Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Возвращает или устанавливает индекс стартового трека. Читаемое/записываемое Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Возвращает или устанавливает время стартового трека. Читаемое/записываемое Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как фигура будет отображаться в черно-белом режиме. Читаемое/записываемое [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество узлов соединения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Определяет, встроен ли звук в презентацию. Только для чтения Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Возвращает или устанавливает встроенный аудиофайл. Читаемое/записываемое [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Указывает время длительности для начального появления медиа в миллисекундах. Читаемое/записываемое Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Указывает время длительности для конечного исчезновения медиа в миллисекундах. Читаемое/записываемое Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования заливки для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств заливки. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки фигуры. Читаемое/записываемое [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту фигуры. Читаемое/записываемое Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Читаемое/записываемое Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Определяет, скрыт ли AudioFrame. Читаемое/записываемое Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для клика мыши. Читаемое/записываемое [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Читаемое/записываемое [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Определяет, является ли PictureFrame Cameo объектом или нет. Только для чтения Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает опцию «Пометить как декоративную» Читаемое/записываемое Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Возвращает или устанавливает имя аудиофайла, связанного с AudioFrame. Читаемое/записываемое String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя фигуры. Не должно быть null. Используйте пустую строку при необходимости. Читаемое/записываемое String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор фигуры в контексте слайда. Только для чтения UInt32. Смотрите также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора фигуры в контексте презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Возвращает объект PictureFillFormat для рамки изображения. Только для чтения [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнение для фигуры. Возвращает null, если фигура не имеет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Определяет, играет ли аудио между слайдами. Читаемое/записываемое Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Определяет, находится ли аудио в цикле. Читаемое/записываемое Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Возвращает или устанавливает режим воспроизведения аудио. Читаемое/записываемое [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства исходной рамки фигуры. Читаемое/записываемое [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Возвращает или устанавливает масштаб высоты (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100%. Читаемое/записываемое Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Возвращает или устанавливает масштаб ширины (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100%. Читаемое/записываемое Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Определяет, будет ли аудио автоматически перематываться в начало после воспроизведения. Читаемое/записываемое Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которое заданная фигура вращена вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на против часовой стрелки. Читаемое/записываемое Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IPictureFrameLock`](../ipictureframelock). (2 свойства) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля фигуры. Только для чтения [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Возвращает или устанавливает тип AutoShape для PictureFrame. Допускаются все элементы набора [`ShapeType`](../shapetype), кроме всех видов линий: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства 3D эффектов для фигуры. Примечание: может вернуть null для определенных типов фигур, которые не имеют 3D свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Указывает временной интервал, который необходимо удалить с конца медиа во время воспроизведения, в миллисекундах. Читаемое/записываемое Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Указывает временной интервал, который необходимо удалить в начале медиа во время воспроизведения, в миллисекундах. Читаемое/записываемое Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор фигуры в контексте презентации. Только для чтения UInt32. Смотрите также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора фигуры в контексте слайда. |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Возвращает или устанавливает громкость аудио. Читаемое/записываемое [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Возвращает или устанавливает громкость аудио в процентах. Читаемое/записываемое Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину фигуры. Читаемое/записываемое Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает координату x верхнего левого угла фигуры. Читаемое/записываемое Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает координату y верхнего левого угла фигуры. Читаемое/записываемое Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает положение фигуры в порядке z. Shapes[0] возвращает фигуру внизу порядка z, а Shapes[Shapes.Count - 1] возвращает фигуру вверху порядка z. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если не существует, и устанавливает свойства заполнителя на указанный. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов фигуры. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую фигуру-заполнитель (фигура из макета и/или мастер-слайда, от которого унаследована текущая фигура). Если текущая фигура не унаследована, возвращается null. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической фигуры. Координаты относительно верхнего левого угла фигуры. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. Тип фигуры ShapeThumbnailBounds.Shape используется по умолчанию. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта фигура не является заполнителем. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию фигуры из объекта [`IGeometryPath`](../igeometrypath). Координаты должны быть относительно верхнего левого угла фигуры. Изменяет тип фигуры ([`ShapeType`](../geometryshape/shapetype)) на Пользовательский. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию фигуры из массива [`IGeometryPath`](../igeometrypath). Координаты должны быть относительно верхнего левого угла фигуры. Изменяет тип фигуры ([`ShapeType`](../geometryshape/shapetype)) на Пользовательский. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в формате SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в формате SVG. |

### Примеры

Следующие примеры показывают, как изменить параметры воспроизведения аудио.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Получает фигуру AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Устанавливает режим воспроизведения на «воспроизводить по щелчку»
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Устанавливает громкость на «низкая»
    audioFrame.Volume = AudioVolumeMode.Low;
    // Устанавливает воспроизведение аудио между слайдами
    audioFrame.PlayAcrossSlides = true;
    // Отключает повторное воспроизведение аудио
    audioFrame.PlayLoopMode = false;
    // Скрывает AudioFrame во время показа слайда
    audioFrame.HideAtShowing = true;
    // Перематывает аудио в начало после воспроизведения
    audioFrame.RewindAudio = true;
    // Сохраняет файл PowerPoint на диск
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### См. Также

* класс [PictureFrame](../pictureframe)
* интерфейс [IAudioFrame](../iaudioframe)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->