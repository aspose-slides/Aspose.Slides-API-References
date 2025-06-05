---
title: PictureFrame
second_title: Aspose.Sildes для .NET API Reference
description: Представляет рамку с изображением внутри.
type: docs
weight: 9140
url: /ru/aspose.slides/pictureframe/
---

## PictureFrame class

Представляет рамку с изображением внутри.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Properties

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Возвращает коллекцию значений корректировки формы. Только для чтения [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, ассоциированный с формой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, ассоциированного с формой. Чтение/запись String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство определяет, как форма будет отображаться в черно-белом режиме. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество узлов подключения на форме. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные формы. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, применяемые к форме. Примечание: может вернуть null для определенных типов форм, у которых нет свойств эффекта. Только для чтения [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, который содержит свойства формата заливки для формы. Примечание: может вернуть null для определенных типов форм, у которых нет свойств заливки. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту формы. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли форма. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для щелчка мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Определяет, является ли PictureFrame объектом Cameo или нет. Только для чтения Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или задает опцию 'Отметить как декоративный' Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли форма. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли форма TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линий для формы. Примечание: может вернуть null для определенных типов форм, у которых нет свойств линии. Только для чтения [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя формы. Должно быть не null. Используйте пустую строку, если необходимо. Чтение/запись String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в пределах слайда. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid) для получения уникального идентификатора формы в пределах презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если форма сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Возвращает объект PictureFillFormat для рамки изображения. Только для чтения [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Возвращает блокировки формы. Только для чтения [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнител для формы. Возвращает null, если у формы нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства необработанной рамки формы. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Возвращает или задает масштаб высоты (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100%. Чтение/запись Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Возвращает или задает масштаб ширины (относительно оригинального размера изображения) рамки изображения. Значение 1.0 соответствует 100%. Чтение/запись Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает количество градусов, на которое заданная форма повёрнута вокруг оси Z. Положительное значение указывает на поворот по часовой стрелке; отрицательное значение указывает на поворот против часовой стрелки. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Возвращает блокировки формы. Только для чтения [`IPictureFrameLock`](../ipictureframelock). (2 свойства) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Возвращает объект стиля формы. Только для чтения [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Возвращает или задает тип AutoShape для PictureFrame. Допускаются все элементы набора [`ShapeType`](../shapetype), кроме всех видов линий: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд формы. Только для чтения [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, который содержит свойства 3d эффектов для формы. Примечание: может вернуть null для определенных типов форм, у которых нет свойств 3d. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в пределах презентации. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора формы в пределах слайда. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Возвращает или задает ширину формы. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Возвращает или задает координату x верхнего левого угла формы. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Возвращает или задает координату y верхнего левого угла формы. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию формы в порядке z. Shapes[0] возвращает форму в задней части порядка z, а Shapes[Shapes.Count - 1] возвращает форму в передней части порядка z. Только для чтения Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и устанавливает свойства заполнителя на указанные. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Создает и возвращает массив элементов формы. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовую форму-заполнитель (форму из макета и/или главного слайда, от которой унаследована текущая форма). Если текущая форма не унаследована, возвращается null. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Возвращает копию пути геометрической формы. Координаты относительны к верхнему левому углу формы. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру формы. По умолчанию используется тип ограничений миниатюры ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру формы. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Определяет, что эта форма не является заполнителем. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Обновляет геометрию формы из объекта [`IGeometryPath`](../igeometrypath). Координаты должны быть относительными к верхнему левому углу формы. Меняет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Обновляет геометрию формы из массива [`IGeometryPath`](../igeometrypath). Координаты должны быть относительными к верхнему левому углу формы. Меняет тип формы ([`ShapeType`](../geometryshape/shapetype)) на Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы в виде SVG файла. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы в виде SVG файла. |

### Examples

Следующие примеры показывают, как изменить миниатюру аудио рамки.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Добавляет аудиофрейм на слайд с заданным положением и размером.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Добавляет изображение в ресурсы презентации.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Устанавливает изображение для аудиофрейма.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//Сохраняет изменённую презентацию на диск
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### See Also

* class [GeometryShape](../geometryshape)
* interface [IPictureFrame](../ipictureframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->