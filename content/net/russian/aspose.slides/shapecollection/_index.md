---  
title: ShapeCollection  
second_title: Aspose.Slides для .NET API Reference  
description: Представляет коллекцию фигур.
type: docs  
weight: 9550  
url: /ru/aspose.slides/shapecollection/
---  

## Класс ShapeCollection  

Представляет коллекцию фигур.  

```csharp  
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection  
```  

## Свойства  

| Название | Описание |  
| --- | --- |  
| [Count](../../aspose.slides/shapecollection/count) { get; } | Получает количество элементов, фактически содержащихся в коллекции. Только для чтения Int32. |  
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (безопасно для потоков). Только для чтения Boolean. |  
| [Item](../../aspose.slides/shapecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения [`IShape`](../ishape). |  
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Возвращает родительский объект GroupShape для коллекции фигур. Только для чтения [`IGroupShape`](../igroupshape). |  
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Возвращает корень синхронизации. Только для чтения Object. |  

## Методы  

| Название | Описание |  
| --- | --- |  
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Добавляет AudioFrame с CD в конец коллекции. |  
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Добавляет новый audio frame с встроенным аудиофайлом в конец коллекции. Использует аудиофайл из списка Presentation.Audios. |  
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Добавляет новый audio frame с встроенным аудиофайлом в конец коллекции. Встроенный аудиофайл может быть только WAV. Добавляет новый аудио в список Presentation.Audios. |  
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Добавляет новый audio frame с привязанным аудиофайлом в конец коллекции. |  
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Создает новую AutoShape, настраивает её по умолчанию и добавляет в конец коллекции. |  
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Создает новую AutoShape и добавляет её в конец коллекции. |  
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Создает новый Chart, инициализирует его с примером данных и настроек и добавляет в конец коллекции. |  
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Создает новый Chart и добавляет его в конец коллекции. |  
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Добавляет копию указанной фигуры в конец коллекции. X, Y, Width и Height новой фигуры равны X, Y, Width и Height *sourceShape*. |  
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Добавляет копию указанной фигуры в конец коллекции. Width и Height новой фигуры равны Width и Height *sourceShape*. |  
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Добавляет копию указанной фигуры в конец коллекции. |  
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Создает новый Connector, настраивает его по умолчанию и добавляет в конец коллекции. |  
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Создает новый Connector и добавляет его в конец коллекции. |  
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Создает новый GroupShape и добавляет его в конец коллекции. Размер и положение рамки GroupShape будут подстраиваться под содержимое при добавлении новой фигуры в GroupShape. |  
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Создает новый GroupShape, заполняет его преобразованными фигурами из SVG и добавляет его в конец коллекции. |  
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Создает новую Autoshape, настроенную по умолчанию для математического содержимого, и добавляет её в конец коллекции. |  
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Добавляет новый OLE объект в конец коллекции. |  
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Добавляет новый OLE объект в конец коллекции. |  
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Создает новый PictureFrame и добавляет его в конец коллекции. |  
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Добавляет новый объект Section Zoom в конец коллекции. |  
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Добавляет новый объект Section Zoom в конец коллекции с заранее заданным изображением. |  
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Добавляет диаграмму SmartArt. |  
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Добавляет новый объект Summary Zoom в конец коллекции. |  
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Создает новую таблицу и добавляет ее в конец коллекции. |  
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Добавляет новый видеофрейм в конец коллекции. |  
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Добавляет новый видеофрейм в конец коллекции. |  
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Добавляет новый объект Zoom в конец коллекции. |  
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Добавляет новый объект Zoom в конец коллекции. |  
| [Clear](../../aspose.slides/shapecollection/clear)() | Удаляет все фигуры из коллекции. |  
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |  
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Возвращает перечислитель, который итеративно проходит по коллекции. |  
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Возвращает индекс на нулевой основе первого вхождения фигуры в коллекцию. |  
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Вставляет AudioFrame с CD. |  
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Вставляет AudioFrame с встроенным аудиофайлом. Использует аудиофайл из списка Presentation.Audios. |  
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Вставляет AudioFrame с встроенным аудиофайлом. Звук встроенного аудиофайла может быть только WAV. |  
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Создает новый audio frame с привязанным аудиофайлом и вставляет его в коллекцию по указанному индексу. |  
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Создает новую AutoShape, настраивает её по умолчанию и вставляет в коллекцию по указанному индексу. Примечание: тип фигуры будет определяться параметром shapeType. |  
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Создает новую AutoShape и вставляет её в коллекцию по указанному индексу. Примечание: тип фигуры будет определяться параметром shapeType. |  
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Создает новый Chart, инициализирует его примером данных и настроек и вставляет его в указанную позицию в коллекции. |  
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Создает новый Chart и вставляет его в указанную позицию в коллекции. |  
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Вставляет копию указанной фигуры в указанную позицию коллекции. X, Y, Width и Height новой фигуры равны X, Y, Width и Height *sourceShape*. |  
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Вставляет копию указанной фигуры в указанную позицию коллекции. Width и Height новой фигуры равны Width и Height *sourceShape*. |  
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Вставляет копию указанной фигуры в указанную позицию коллекции. |  
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Создает новый Connector, настраивает его по умолчанию и вставляет в коллекцию по указанному индексу. |  
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Создает новый Connector и вставляет его в коллекцию по указанному индексу. |  
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Создает новый GroupShape и вставляет его в коллекцию по указанному индексу. Размер и положение рамки GroupShape будут подстраиваться под содержимое при добавлении новой фигуры в GroupShape. |  
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Создает новый OLE объект и вставляет его в коллекцию по указанному индексу. |  
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Создает новый OLE объект и вставляет его в коллекцию по указанному индексу. |  
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Создает новый PictureFrame и вставляет его в коллекцию по указанному индексу. |  
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Создает новый объект Section Zoom и вставляет его в коллекцию по указанному индексу. |  
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Создает новый объект Section Zoom и вставляет его в коллекцию по указанному индексу. |  
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Создает новый объект Summary Zoom и вставляет его в коллекцию по указанному индексу. |  
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Создает новую таблицу и вставляет её в коллекцию по указанному индексу. |  
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Создает новый видеофрейм и вставляет его в коллекцию по указанному индексу. |  
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Создает новый объект Zoom и вставляет его в коллекцию по указанному индексу. |  
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Создает новый объект Zoom и вставляет его в коллекцию по указанному индексу. |  
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Удаляет первое вхождение конкретной фигуры из коллекции. |  
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Удаляет элемент по указанному индексу в коллекции. |  
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Перемещает фигуру из коллекции в указанное положение. |  
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Перемещает фигуры из коллекции в указанное положение. Фигуры будут размещены начиная с индекса в порядке их появления в списке. |  
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Создает и возвращает массив со всеми фигурами в нем. |  
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив со всеми фигурами из указанного диапазона в нем. Индекс первой фигуры для возврата. Количество фигур для возврата. |  

### См. также  

* класс [DomObject&lt;TParent&gt;](../domobject-1)  
* класс [GroupShape](../groupshape)  
* интерфейс [IShapeCollection](../ishapecollection)  
* пространство имен [Aspose.Slides](../../aspose.slides)  
* сборка [Aspose.Slides](../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  