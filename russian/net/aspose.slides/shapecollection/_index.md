---
title: ShapeCollection
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет набор фигур.
type: docs
weight: 9080
url: /ru/net/aspose.slides/shapecollection/
---
## ShapeCollection class

Представляет набор фигур.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Получает количество элементов, фактически содержащихся в коллекции. Только для чтенияInt32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Возвращает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). Только чтениеBoolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения[`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Возвращает родительский объект GroupShape для коллекции фигур. Только для чтения[`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтенияObject. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Добавляет AudioFrame с компакт-диском в конец коллекции. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Добавляет в конец коллекции новый аудиокадр со встроенным аудиофайлом. Используется аудиофайл из списка Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Добавляет в конец коллекции новый аудиокадр со встроенным аудиофайлом. Встроенный аудиофайл может быть только в формате WAV. Добавляет новый звук в список Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Добавляет новый аудиокадр со связанным аудиофайлом в конец коллекции. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Создает новую автофигуру, настраивает ее из шаблона по умолчанию и добавляет в конец коллекции. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Создает новую автофигуру и добавляет ее в конец коллекции. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Создает новую диаграмму, инициализирует ее данными и настройками серии образцов и добавляет в конец коллекции. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Создает новую диаграмму и добавляет ее в конец коллекции. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Добавляет копию указанной фигуры в конец коллекции. X, Y, ширина и высота новой формы равны X, Y, ширине и высоте*sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Добавляет копию указанной фигуры в конец коллекции. Ширина и высота новой формы равны ширине и высоте*sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Добавляет копию указанной фигуры в конец коллекции. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Создает новый коннектор, настраивает его из шаблона по умолчанию и добавляет в конец коллекции. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Создает новый коннектор и добавляет его в конец коллекции. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Создает новый GroupShape и добавляет его в конец коллекции. Размер и положение кадра GroupShape будут соответствовать содержимому, когда в GroupShape будет добавлена новая фигура. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Создает новый GroupShape, заполняет его преобразованными фигурами из SVG и добавляет в конец коллекции. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Создает новую автофигуру, настроенную из шаблона по умолчанию на математический контент, и добавляет ее в конец коллекции. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Добавляет новый объект OLE в конец коллекции. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Добавляет новый объект OLE в конец коллекции. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Создает новый PictureFrame и добавляет его в конец коллекции. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Добавляет новый объект Section Zoom в конец коллекции. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Добавляет новый объект Section Zoom в конец коллекции с предопределенным изображением. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Добавить диаграмму SmartArt. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Добавляет новый объект Суммарное масштабирование в конец коллекции. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Создает новую таблицу и добавляет ее в конец коллекции. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Добавляет новый видеокадр в конец коллекции. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Добавляет новый видеокадр в конец коллекции. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Добавляет новый объект Zoom в конец коллекции. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Добавляет новый объект Zoom в конец коллекции. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Удаляет все фигуры из коллекции. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Возвращает отсчитываемый от нуля индекс первого вхождения фигуры в коллекцию. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Вставьте AudioFrame с CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Вставьте AudioFrame со встроенным аудиофайлом. Используется аудиофайл из списка Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Вставьте AudioFrame со встроенным аудиофайлом. Звук встроенного аудиофайла может быть только в формате WAV. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Создает новый аудиокадр со связанным аудиофайлом и вставляет его в коллекцию по указанному индексу. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Создает новую автофигуру, настраивает ее из шаблона по умолчанию и вставляет в коллекцию по указанному индексу. Примечание:тип фигуры будет определяться параметром shapeType. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Создает новую автофигуру и вставляет ее в коллекцию по указанному индексу. Примечание:тип фигуры будет определяться параметром shapeType. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Создает новую диаграмму, инициализирует ее данными и настройками серии образцов и вставляет в указанную позицию в коллекции. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Создает новую диаграмму и вставляет ее в указанную позицию в коллекции. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Вставляет копию указанной формы в указанную позицию коллекции. X, Y, ширина и высота новой формы равны X, Y, ширине и высоте*sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Вставляет копию указанной формы в указанную позицию коллекции. Ширина и высота новой формы равны ширине и высоте*sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Вставляет копию указанной формы в указанную позицию коллекции. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Создает новый коннектор, настраивает его из шаблона по умолчанию и вставляет в коллекцию по указанному индексу. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Создает новый коннектор и вставляет его в коллекцию по указанному индексу. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Создает новый GroupShape и вставляет его в коллекцию по указанному индексу. Размер и положение кадра GroupShape будут соответствовать содержимому, когда в GroupShape будет добавлена новая фигура. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Создает новый объект OLE и вставляет его в коллекцию по указанному индексу. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Создает новый объект OLE и вставляет его в коллекцию по указанному индексу. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Создает новый PictureFrame и вставляет его в коллекцию по указанному индексу. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Создает новый объект Section Zoom и вставляет его в коллекцию по указанному индексу. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Создает новый объект Section Zoom и вставляет его в коллекцию по указанному индексу. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Создает новый объект Суммарный масштаб и вставляет его в коллекцию по указанному индексу. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Создает новую таблицу и вставляет ее в коллекцию по указанному индексу. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Создает новый видеокадр и вставляет его в коллекцию по указанному индексу. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Создает новый объект Zoom и вставляет его в коллекцию по указанному индексу. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Создает новый объект Zoom и вставляет его в коллекцию по указанному индексу. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Удаляет первое вхождение определенной формы из коллекции. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Удаляет элемент по указанному индексу коллекции. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Перемещает фигуру из коллекции в указанную позицию. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Перемещает фигуры из коллекции в указанную позицию. Фигуры будут размещены, начиная с индекса, в том порядке, в котором они появляются в списке. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Создает и возвращает массив со всеми формами в нем. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив со всеми фигурами из указанного диапазона.  Индекс первой возвращаемой фигуры. Количество возвращаемых фигур. |

### Смотрите также

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
