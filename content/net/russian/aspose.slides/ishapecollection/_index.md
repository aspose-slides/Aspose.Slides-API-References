---
title: IShapeCollection
second_title: Aspose.Sildes для .NET API Справочник
description: Представляет коллекцию фигур.
type: docs
weight: 6760
url: /ru/aspose.slides/ishapecollection/
---

## Интерфейс IShapeCollection

Представляет коллекцию фигур.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Возвращает родительский объект GroupShape для коллекции фигур. Только для чтения [`IGroupShape`](../igroupshape). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Добавляет AudioFrame с CD в конец коллекции. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Добавляет новый аудиофрейм с встраиваемым аудиофайлом в конец коллекции. Использует аудиофайл из списка Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Добавляет новый аудиофрейм с встраиваемым аудиофайлом в конец коллекции. Встраиваемый аудиофайл может быть только WAV. Добавляет новый аудиофайл в список Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Добавляет новый аудиофрейм с связанным аудиофайлом в конец коллекции. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Создает новую AutoShape, настраивает ее по умолчанию и добавляет в конец коллекции. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Создает новую AutoShape и добавляет в конец коллекции. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Создает новый график, инициализирует его с образцами данных и настройками и добавляет в конец коллекции. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Создает новый график и добавляет в конец коллекции. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Добавляет копию указанной фигуры в конец коллекции. X, Y, Width и Height новой фигуры равны X, Y, Width и Height *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Добавляет копию указанной фигуры в конец коллекции. Width и Height новой фигуры равны Width и Height *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Добавляет копию указанной фигуры в конец коллекции. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Создает новый Connector, настраивает его по умолчанию и добавляет в конец коллекции. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Создает новый Connector и добавляет в конец коллекции. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Создает новый GroupShape и добавляет в конец коллекции. Размер и позиция GroupShape будут подогнаны под содержимое, когда новая фигура будет добавлена в GroupShape. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Создает новый GroupShape, заполняет его сконвертированными фигурами из SVG и добавляет в конец коллекции. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Создает новую AutoShape типа Прямоугольник для размещения математического контента внутри и добавляет в конец коллекции. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Добавляет новый OLE-объект в конец коллекции. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Добавляет новый OLE-объект в конец коллекции. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Создает новый PictureFrame и добавляет в конец коллекции. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Добавляет новый объект Section Zoom в конец коллекции. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Добавляет новый объект Section Zoom в конец коллекции с предопределенным изображением. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Добавляет диаграмму SmartArt. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Добавляет новый объект Summary Zoom в конец коллекции. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Создает новую Таблицу и добавляет в конец коллекции. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Добавляет новый видеопоток в конец коллекции. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Добавляет новый видеопоток в конец коллекции. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Добавляет новый объект Zoom в конец коллекции. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Добавляет новый объект Zoom в конец коллекции. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Удаляет все фигуры из коллекции. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Возвращает индекс нулевой основы первого вхождения фигуры в коллекции. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Вставляет AudioFrame с CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Вставляет AudioFrame с встраиваемым аудиофайлом. Использует аудиофайл из списка Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Вставляет AudioFrame с встраиваемым аудиофайлом. Звук встраиваемого аудиофайла может быть только WAV. Добавляет новый аудиофайл в список Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Создает новый аудиофрейм с связанным аудиофайлом и вставляет его в коллекцию по указанному индексу. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Создает новую AutoShape, настраивает ее по умолчанию и вставляет в коллекцию по указанному индексу. Примечание: тип фигуры будет определяться параметром shapeType. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Создает новую AutoShape и вставляет в коллекцию по указанному индексу. Примечание: тип фигуры будет определяться параметром shapeType. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Создает новый график, инициализирует его с примерами данных и настройками и вставляет в указанное положение коллекции. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Создает новый график и вставляет в указанное положение коллекции. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Вставляет копию указанной фигуры в указанное положение коллекции. X, Y, Width и Height новой фигуры равны X, Y, Width и Height *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Вставляет копию указанной фигуры в указанное положение коллекции. Width и Height новой фигуры равны Width и Height *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Вставляет копию указанной фигуры в указанное положение коллекции. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Создает новый Connector, настраивает его по умолчанию и вставляет в коллекцию по указанному индексу. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Создает новый Connector и вставляет в коллекцию по указанному индексу. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Создает новый GroupShape и вставляет в коллекцию по указанному индексу. Размер и позиция GroupShape будут подогнаны под содержимое, когда новая фигура будет добавлена в GroupShape. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Создает новый OLE-объект и вставляет в коллекцию по указанному индексу. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Создает новый OLE-объект и вставляет в коллекцию по указанному индексу. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Создает новый PictureFrame и вставляет в коллекцию по указанному индексу. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Создает новый объект Section Zoom и вставляет его в коллекцию по указанному индексу. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Создает новый объект Section Zoom и вставляет его в коллекцию по указанному индексу. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Создает новый объект Summary Zoom и вставляет в коллекцию по указанному индексу. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Создает новую Таблицу и вставляет в коллекцию по указанному индексу. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Создает новый видеопоток и вставляет в коллекцию по указанному индексу. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Создает новый объект Zoom и вставляет в коллекцию по указанному индексу. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Создает новый объект Zoom и вставляет в коллекцию по указанному индексу. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Удаляет первое вхождение конкретной фигуры из коллекции. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Удаляет элемент по указанному индексу коллекции. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Перемещает фигуру из коллекции в указанное положение. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Перемещает фигуры из коллекции в указанное положение. Фигуры будут размещены начиная с индекса в порядке их появления в списке. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Создает и возвращает массив со всеми фигурами в нем. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив со всеми фигурами из указанного диапазона в нем. |

### Смотрите также

* интерфейс [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* интерфейс [IShape](../ishape)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->