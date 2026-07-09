---
title: OleObjectFrame
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет объект OLE на слайде.
type: docs
weight: 9230
url: /ru/aspose.slides/oleobjectframe/
---
## OleObjectFrame класс

Представляет объект OLE на слайде.

```csharp
public class OleObjectFrame : GraphicalObject, IOleObjectFrame
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Возвращает или задает альтернативный текст, связанный с фигурой. Чтение/запись String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Возвращает или задает заголовок альтернативного текста, связанного с фигурой. Чтение/запись String. |
| [AsIGraphicalObject](../../aspose.slides/oleobjectframe/asigraphicalobject) { get; } | Позволяет получить базовый интерфейс IGraphicalObject. Только для чтения [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Свойство указывает, как фигура будет отображаться в режиме черно-белого отображения. Чтение/запись [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Возвращает количество точек соединения на фигуре. Только для чтения Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Возвращает пользовательские данные фигуры. Только для чтения [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Возвращает объект EffectFormat, содержащий пиксельные эффекты, применённые к фигуре. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств эффекта. Только для чтения [`IEffectFormat`](../ieffectformat). |
| [EmbeddedData](../../aspose.slides/oleobjectframe/embeddeddata) { get; } | Получает или задаёт информацию о внедрённых данных OLE. Чтение/запись [`IOleEmbeddedDataInfo`](../ioleembeddeddatainfo). |
| [EmbeddedFileLabel](../../aspose.slides/oleobjectframe/embeddedfilelabel) { get; } | Возвращает имя файла встроенного объекта OLE. |
| [EmbeddedFileName](../../aspose.slides/oleobjectframe/embeddedfilename) { get; } | Возвращает путь к встроенному объекту OLE. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Возвращает объект FillFormat, содержащий свойства заполнения для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств заполнения. Только для чтения [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Возвращает или задает свойства кадра фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Получает или задаёт высоту фигуры в пунктах. Чтение/запись Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Определяет, скрыта ли фигура. Чтение/запись Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Возвращает или задает гиперссылку, определённую для клика мышью. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Возвращает менеджер гиперссылок. Только для чтения [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Возвращает или задает гиперссылку, определённую для наведения мыши. Чтение/запись [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Получает или задаёт параметр «Отметить как декоративный». Чтение/запись Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Определяет, входит ли фигура в группу. Только для чтения Boolean. |
| [IsObjectIcon](../../aspose.slides/oleobjectframe/isobjecticon) { get; set; } | Определяет, отображается ли объект как значок. Чтение/запись Boolean. |
| [IsObjectLink](../../aspose.slides/oleobjectframe/isobjectlink) { get; } | Определяет, связан ли объект с внешним файлом. Только для чтения Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Определяет, является ли фигура TextHolder_PPT. Только для чтения Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Возвращает объект LineFormat, содержащий свойства форматирования линий для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет свойств линий. Только для чтения [`ILineFormat`](../ilineformat). |
| [LinkFileName](../../aspose.slides/oleobjectframe/linkfilename) { get; } | Возвращает полный путь к связанному файлу. Будет использовано короткое имя файла. Только для чтения String. |
| [LinkPathLong](../../aspose.slides/oleobjectframe/linkpathlong) { get; set; } | Возвращает полный путь к связанному файлу. Будет использовано полное имя файла. Чтение/запись String. |
| [LinkPathRelative](../../aspose.slides/oleobjectframe/linkpathrelative) { get; } | Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. Только для чтения String. |
| [Name](../../aspose.slides/shape/name) { get; set; } | Возвращает или задает имя фигуры. Не должно быть null. При необходимости используйте пустую строку. Чтение/запись String. |
| [ObjectName](../../aspose.slides/oleobjectframe/objectname) { get; set; } | Возвращает или задает имя объекта. Чтение/запись String. |
| [ObjectProgId](../../aspose.slides/oleobjectframe/objectprogid) { get; set; } | Возвращает ProgID объекта. Только для чтения String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Возвращает уникальный идентификатор фигуры в пределах слайда, который остаётся постоянным в течение жизни фигуры и позволяет PowerPoint или коду interop надёжно ссылаться на фигуру из любого места документа. Только для чтения UInt32. См. также [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Возвращает родительский объект GroupShape, если фигура сгруппирована. В противном случае возвращает null. Только для чтения [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Возвращает заполнитель для фигуры. Возвращает null, если у фигуры нет заполнителя. Только для чтения [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Возвращает родительскую презентацию слайда. Только для чтения [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Возвращает или задает необработанные свойства кадра фигуры. Чтение/запись [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Возвращает или задает количество градусов, на которое указанная фигура вращается вокруг оси Z. Положительное значение указывает вращение по часовой стрелке; отрицательное — против часовой. Чтение/запись Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Возвращает блокировки фигуры. Только для чтения [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 свойства) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Возвращает родительский слайд фигуры. Только для чтения [`IBaseSlide`](../ibaseslide). |
| [SubstitutePictureFormat](../../aspose.slides/oleobjectframe/substitutepictureformat) { get; } | Возвращает объект свойств заполнения изображения OleObject. Только для чтения [`IPictureFillFormat`](../ipicturefillformat). |
| [SubstitutePictureTitle](../../aspose.slides/oleobjectframe/substitutepicturetitle) { get; set; } | Возвращает или задает заголовок для значка OleObject. Чтение/запись String. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Возвращает объект ThreeDFormat, содержащий свойства 3D-эффектов для фигуры. Примечание: может возвращать null для некоторых типов фигур, у которых нет 3D-свойств. Только для чтения [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Возвращает внутренний идентификатор, привязанный к презентации, предназначенный для использования надстройками или другим кодом. Поскольку это значение может быть переопределено пользователем или программно, его нельзя рассматривать как постоянный уникальный ключ. Только для чтения UInt32. См. также [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [UpdateAutomatic](../../aspose.slides/oleobjectframe/updateautomatic) { get; set; } | Определяет, обновляется ли связанный встроенный объект автоматически при открытии или печати презентации. Чтение/запись Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | Получает или задаёт ширину фигуры в пунктах. Чтение/запись Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Получает или задаёт координату X левого верхнего угла фигуры в пунктах. Чтение/запись Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Получает или задаёт координату Y левого верхнего угла фигуры в пунктах. Чтение/запись Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Возвращает позицию фигуры в порядке Z. Shapes[0] возвращает фигуру в самом заднем слое, Shapes[Shapes.Count - 1] — в переднем. Только для чтения Int32. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Добавляет новый заполнитель, если его нет, и задаёт свойства заполнителя указанному. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Возвращает базовый заполнитель (фигуру из макета и/или образца, от которой унаследована текущая фигура). Возвращает null, если текущая фигура не унаследована. |
| [GetImage](../../aspose.slides/shape/getimage)() | Возвращает миниатюру фигуры. По умолчанию используется тип ShapeThumbnailBounds.Shape. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Возвращает миниатюру фигуры. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Получает визуальные границы фигуры, рассчитанные на основе её отрисованного содержимого. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Указывает, что эта фигура не является заполнителем. |
| [SetEmbeddedData](../../aspose.slides/oleobjectframe/setembeddeddata)(IOleEmbeddedDataInfo) | Задаёт информацию о внедрённых данных OLE. Этот метод изменяет свойства объекта, отражая новые данные, и устанавливает флаг IsObjectLink в false, указывая, что объект OLE внедрён. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Сохраняет содержимое фигуры в файл SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Сохраняет содержимое фигуры в файл SVG. |

### Примеры

Следующий пример демонстрирует, как получить доступ к кадрам OLE Object.

```csharp
[C#]
// Загружает PPTX в объект презентации
using (Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx"))
{
    // Получает первый слайд
    ISlide sld = pres.Slides[0];
    // Преобразует форму в OleObjectFrame
    OleObjectFrame oleObjectFrame = sld.Shapes[0] as OleObjectFrame;
    // Читает объект OLE и записывает его на диск
    if (oleObjectFrame != null)
    {
        // Получает данные встроенного файла
        byte[] data = oleObjectFrame.EmbeddedData.EmbeddedFileData;
        // Получает расширение встроенного файла
        string fileExtention = oleObjectFrame.EmbeddedData.EmbeddedFileExtension;
        // Создаёт путь для сохранения извлечённого файла
        string extractedPath = "excelFromOLE_out" + fileExtention;
        // Сохраняет извлечённые данные
        using (FileStream fstr = new FileStream(extractedPath, FileMode.Create, FileAccess.Write))
        {
            fstr.Write(data, 0, data.Length);
        }
    }
}
```

### См. также

* класс [GraphicalObject](../graphicalobject)
* интерфейс [IOleObjectFrame](../ioleobjectframe)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->