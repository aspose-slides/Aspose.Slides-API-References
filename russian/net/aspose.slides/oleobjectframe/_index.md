---
title: OleObjectFrame
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет объект OLE на слайде.
type: docs
weight: 8500
url: /ru/net/aspose.slides/oleobjectframe/
---
## OleObjectFrame class

Представляет объект OLE на слайде.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/записьString . |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/записьString . |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Позволяет получить базовый интерфейс IGraphicalObject. Только для чтения[`IGraphicalObject`](../igraphicalobject) . |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в черно-белом режиме отображения.. Чтение/запись[`BlackWhiteMode`](../blackwhitemode) . |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество сайтов подключения на фигуре. Только для чтенияInt32 . |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения[`ICustomData`](../icustomdata) . |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, который содержит пиксельные эффекты, примененные к фигуре. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств эффекта. Только для чтения[`IEffectFormat`](../ieffectformat) . |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Получает или задает информацию о встроенных данных OLE. Чтение/запись[`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo) . |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Возвращает имя файла встроенного OLE-объекта |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Возвращает путь встроенного OLE-объекта |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства форматирования заливки для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств заливки. Только для чтения[`IFillFormat`](../ifillformat) . |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства фрейма формы. Чтение/запись[`IShapeFrame`](../ishapeframe) . |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки формы. Только для чтения[`IGraphicalObjectLock`](../igraphicalobjectlock) . |
| [Height](../../aspose.slides/shape/height) { get; set; } | Возвращает или задает высоту фигуры. Чтение/записьSingle . |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/записьBoolean . |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определенную для щелчка мыши. Чтение/запись[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает диспетчер гиперссылок. Только для чтения[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определенную для наведения курсора. Чтение/запись[`IHyperlink`](../ihyperlink) . |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, сгруппирована ли фигура. Только для чтенияBoolean . |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Определяет, виден ли объект в виде значка. Чтение/записьBoolean . |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Определяет, связан ли объект с внешним файлом. Только для чтенияBoolean . |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтенияBoolean . |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, который содержит свойства форматирования линии для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих свойств линии. Только для чтения[`ILineFormat`](../ilineformat) . |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Возвращает полный путь к связанному файлу. Будет использоваться короткое имя файла. Только для чтенияString . |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Возвращает полный путь к связанному файлу. Будет использоваться длинное имя файла. Чтение/записьString . |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя фигуры. Должно быть не пустым. При необходимости используйте пустое строковое значение. Чтение/записьString . |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Возвращает или задает имя объекта. Чтение/записьString . |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Возвращает ProgID объекта. Только чтениеString . |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Получает уникальный идентификатор формы в области слайда. Только для чтенияUInt32 . См. также[`UniqueId`](../shape/uniqueid) для получения уникального идентификатора формы в области презентации. |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения[`IGroupShape`](../igroupshape) . |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает значение null, если в фигуре нет заполнителя. Только для чтения[`IPlaceholder`](../iplaceholder) . |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения[`IPresentation`](../ipresentation) . |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает свойства кадра необработанной формы. Чтение/запись[`IShapeFrame`](../ishapeframe) . |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает число градусов, на которое указанная фигура поворачивается вокруг оси Z. Положительное значение указывает на вращение по часовой стрелке; отрицательное значение указывает на вращение против часовой стрелки. Чтение/записьSingle . |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки формы. Только для чтения[`IGraphicalObjectLock`](../igraphicalobjectlock) . (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения[`IBaseSlide`](../ibaseslide) . |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Возвращает объект свойств заливки изображения OleObject. Только для чтения[`IPictureFillFormat`](../ipicturefillformat) . |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Возвращает или задает заголовок для значка OleObject. Чтение/записьString . |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, свойства 3D-эффекта для фигуры. Примечание: может возвращать значение null для определенных типов фигур, не имеющих 3D-свойств. Только для чтения[`IThreeDFormat`](../ithreedformat) . |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Получает уникальный идентификатор формы в области представления. Только для чтенияUInt32 . См. также[`OfficeInteropShapeId`](../shape/officeinteropshapeid) для получения уникального идентификатора формы в области слайдов. |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Определяет, будет ли автоматически обновляться связанный встроенный объект при открытии или печати презентации. Чтение/записьBoolean . |
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
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Задает информацию о встроенных данных OLE.  Этот метод изменяет свойства объекта для отражения новых данных, а устанавливает для флага IsObjectLink значение false, указывая на то, что объект OLE внедрен. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое формы в виде файла SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое формы в виде файла SVG. |

### Смотрите также

* class [GraphicalObject](../graphicalobject)
* interface [IOleObjectFrame](../ioleobjectframe)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
