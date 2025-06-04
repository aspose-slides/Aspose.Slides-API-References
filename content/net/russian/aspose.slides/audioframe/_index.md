---
title: AudioFrame
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет аудиоклип на слайде.
type: docs
weight: 790
url: /ru/aspose.slides/audioframe/
---

## AudioFrame класс

Представляет аудиоклип на слайде.

```csharp
public class AudioFrame : PictureFrame, IAudioFrame
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает коллекцию значений настроек формы. Только для чтения [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или устанавливает альтернативный текст, связанный с формой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или устанавливает заголовок альтернативного текста, связанного с формой. Чтение/запись String. |
| [AudioCdEndTrack](../../aspose.slides/audioframe/audiocdendtrack) { get; set; } | Возвращает или устанавливает индекс последнего трека. Чтение/запись Int32. |
| [AudioCdEndTrackTime](../../aspose.slides/audioframe/audiocdendtracktime) { get; set; } | Возвращает или устанавливает время последнего трека. Чтение/запись Int32. |
| [AudioCdStartTrack](../../aspose.slides/audioframe/audiocdstarttrack) { get; set; } | Возвращает или устанавливает индекс стартового трека. Чтение/запись Int32. |
| [AudioCdStartTrackTime](../../aspose.slides/audioframe/audiocdstarttracktime) { get; set; } | Возвращает или устанавливает время стартового трека. Чтение/запись Int32. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как форма будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество соединительных сайтов на форме. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные формы. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к форме. Примечание: может вернуть null для определенных типов форм, у которых нет свойств эффектов. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [Embedded](../../aspose.slides/audioframe/embedded) { get; } | Определяет, встроен ли звук в презентацию. Только для чтения Boolean. |
| [EmbeddedAudio](../../aspose.slides/audioframe/embeddedaudio) { get; set; } | Возвращает или устанавливает встроенный аудиофайл. Чтение/запись [`IAudio`](../iaudio). |
| [FadeInDuration](../../aspose.slides/audioframe/fadeinduration) { get; set; } | Указывает время длительности для начального увеличение громкости медиа в миллисекундах. Чтение/запись Single. |
| [FadeOutDuration](../../aspose.slides/audioframe/fadeoutduration) { get; set; } | Указывает время длительности для окончательного уменьшения громкости медиа в миллисекундах. Чтение/запись Single. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства форматирования для заливки формы. Примечание: может вернуть null для определенных типов форм, у которых нет свойств заливки. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или устанавливает свойства рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или устанавливает высоту формы. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли форма. Чтение/запись Boolean. |
| [HideAtShowing](../../aspose.slides/audioframe/hideatshowing) { get; set; } | Определяет, скрыт ли AudioFrame. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для щелчка мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или устанавливает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Определяет, является ли PictureFrame объектом Cameo или нет. Только для чтения Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или устанавливает параметр 'Отметить как декоративный' Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли форма. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли форма TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для формы. Примечание: может вернуть null для определенных типов форм, у которых нет свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [LinkPathLong](../../aspose.slides/audioframe/linkpathlong) { get; set; } | Возвращает или устанавливает имя аудиофайла, который связан с AudioFrame. Чтение/запись String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или устанавливает имя формы. Не должно быть пустым. Используйте пустую строку, если это необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайда. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если форма сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Возвращает объект PictureFillFormat для рамки изображения. Только для чтения [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Возвращает блокировки формы. Только для чтения [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнител для формы. Возвращает null, если у формы нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [PlayAcrossSlides](../../aspose.slides/audioframe/playacrossslides) { get; set; } | Определяет, воспроизводится ли аудио на слайдах. Чтение/запись Boolean. |
| [PlayLoopMode](../../aspose.slides/audioframe/playloopmode) { get; set; } | Определяет, зациклено ли аудио. Чтение/запись Boolean. |
| [PlayMode](../../aspose.slides/audioframe/playmode) { get; set; } | Возвращает или устанавливает режим воспроизведения аудио. Чтение/запись [`AudioPlayModePreset`](../audioplaymodepreset). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или устанавливает свойства необработанной рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Возвращает или устанавливает масштаб высоты (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100%. Чтение/запись Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Возвращает или устанавливает масштаб ширины (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100%. Чтение/запись Single. |
| [RewindAudio](../../aspose.slides/audioframe/rewindaudio) { get; set; } | Определяет, будет ли аудио автоматически перематываться на начало после воспроизведения. Чтение/запись Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или устанавливает количество градусов, на которые заданная форма поворачивается вокруг оси z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Возвращает блокировки формы. Только для чтения [`IPictureFrameLock`](../ipictureframelock). (2 свойства) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля формы. Только для чтения [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Возвращает или устанавливает тип AutoShape для PictureFrame. Допустимы все элементы набора [`ShapeType`](../shapetype), за исключением всех видов линий: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд формы. Только для чтения [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства 3D эффектов для формы. Примечание: может вернуть null для определенных типов форм, у которых нет свойств 3D. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [TrimFromEnd](../../aspose.slides/audioframe/trimfromend) { get; set; } | Указывает время, которое должно быть удалено с конца медиа при воспроизведении, в миллисекундах. Чтение/запись Single. |
| [TrimFromStart](../../aspose.slides/audioframe/trimfromstart) { get; set; } | Указывает время, которое должно быть удалено с начала медиа при воспроизведении, в миллисекундах. Чтение/запись Single. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора формы в области слайда. |
| [Volume](../../aspose.slides/audioframe/volume) { get; set; } | Возвращает или устанавливает громкость аудио. Чтение/запись [`AudioVolumeMode`](../audiovolumemode). |
| [VolumeValue](../../aspose.slides/audioframe/volumevalue) { get; set; } | Возвращает или устанавливает громкость аудио в процентах. Чтение/запись Single. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или устанавливает ширину формы. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или устанавливает x-координату верхнего левого угла формы. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или устанавливает y-координату верхнего левого угла формы. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию формы в порядке z. Shapes[0] возвращает форму в задней части порядка z, а Shapes[Shapes.Count - 1] возвращает форму в передней части порядка z. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если он отсутствует, и устанавливает свойства заполнителя на заданные. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов формы. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую форму-заполнитель (форму из макета и/или мастер-слайда, от которой наследуется текущая форма). Возвращает null, если текущая форма не наследуется. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической формы. Координаты относительны к левому верхнему углу формы. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру формы. По умолчанию используется тип границ миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта форма не является заполнительной. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию формы из объекта [`IGeometryPath`](../igeometrypath). Координаты должны быть относительно левого верхнего угла формы. Изменяет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Пользовательский. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию формы из массива [`IGeometryPath`](../igeometrypath). Координаты должны быть относительно левого верхнего угла формы. Изменяет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Пользовательский. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы в виде SVG файла. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы в виде SVG файла. |

### Примеры

Ниже приведены примеры, показывающие, как изменить параметры воспроизведения аудио.

```csharp
[C#]
using (Presentation pres = new Presentation("AudioFrameEmbed_out.pptx"))
{
    // Получает форму AudioFrame
    AudioFrame audioFrame = (AudioFrame)pres.Slides[0].Shapes[0];
    // Устанавливает режим воспроизведения на воспроизведение по щелчку
    audioFrame.PlayMode = AudioPlayModePreset.OnClick;
    // Устанавливает громкость на низкую
    audioFrame.Volume = AudioVolumeMode.Low;
    // Устанавливает аудио для воспроизведения на слайдах
    audioFrame.PlayAcrossSlides = true;
    // Отключает зацикливание для аудио
    audioFrame.PlayLoopMode = false;
    // Скрывает AudioFrame во время демонстрации слайда
    audioFrame.HideAtShowing = true;
    // Перематывает аудио на начало после воспроизведения
    audioFrame.RewindAudio = true;
    // Сохраняет файл PowerPoint на диск
    pres.Save("AudioFrameEmbed_changed.pptx", SaveFormat.Pptx);
}
```

### См. также

* класс [PictureFrame](../pictureframe)
* интерфейс [IAudioFrame](../iaudioframe)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->