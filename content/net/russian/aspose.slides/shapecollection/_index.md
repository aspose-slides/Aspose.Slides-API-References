---
title: ShapeCollection
second_title: Aspose.Sildes для .NET справки API
description: Представляет коллекцию фигур.
type: docs
weight: 9860
url: /ru/aspose.slides/shapecollection/
---
## ShapeCollection класс

Представляет коллекцию фигур.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Получает объект родительской группы фигур для коллекции фигур. Только для чтения [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Возвращает корневой объект синхронизации. Только для чтения Object. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Создает новый аудио-кадр, связанный с дорожкой CD, и добавляет его в конец коллекции фигур. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Создает новый аудио-кадр и добавляет его в конец коллекции фигур, используя существующий аудио-объект из списка Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Создает новый аудио-кадр с встроенным WAV-файлом и добавляет его в конец коллекции фигур. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Создает новый аудио-кадр, связанный с внешним аудио-файлом, и добавляет его в конец коллекции фигур. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Создает новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Создает новую автофигуру и добавляет её в конец коллекции фигур, при необходимости инициализируя её форматированием шаблона по умолчанию. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Создает новую диаграмму, инициализирует её примерными данными серии и настройками, и добавляет её в конец коллекции фигур. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Создает новую диаграмму, инициализирует её примерными данными серии и настройками, и добавляет её в конец коллекции фигур. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Создает копию указанной фигуры и добавляет её в конец коллекции фигур. Клонированная фигура сохраняет положение и размер оригинала. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Создает копию указанной фигуры и добавляет её в конец коллекции фигур. Новая фигура сохраняет ширину и высоту *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Создает копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Создает новую соединительную фигуру с оформлением шаблона по умолчанию и добавляет её в конец коллекции фигур. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Создает новую соединительную фигуру и добавляет её в конец коллекции фигур, при необходимости применяя оформление шаблона по умолчанию. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Создает новую пустую групповую фигуру и добавляет её в конец коллекции фигур. Рамка группы автоматически подстраивается под любые добавленные в неё фигуры. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Создает новую групповую фигуру, преобразует указанное SVG-изображение в отдельные фигуры и добавляет полученную группу в конец коллекции фигур. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Создает новую прямоугольную автофигуру для размещения математического контента и добавляет её в конец коллекции фигур. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Создает новый кадр OLE-объекта и добавляет её в конец коллекции фигур. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Создает новый кадр OLE-объекта и добавляет её в конец коллекции фигур. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Создает новый кадр изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Создает новый кадр Section Zoom и добавляет его в конец коллекции фигур. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Создает новый кадр Section Zoom с предустановленным изображением и добавляет его в конец коллекции фигур. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Создает диаграмму SmartArt и добавляет её в конец коллекции фигур. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Создает новый кадр Summary Zoom и добавляет его в конец коллекции фигур. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Создает новую таблицу и добавляет её в конец коллекции фигур. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Создает новый видеокадр и добавляет его в конец коллекции фигур. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Создает новый видеокадр и добавляет его в конец коллекции фигур. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Создает новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Создает новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Удаляет все фигуры из коллекции фигур. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Копирует все элементы из коллекции в указанный массив. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Возвращает перечислитель, который перебирает элементы коллекции. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Возвращает нулевой индекс первого вхождения указанной фигуры в коллекцию. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Создает новый аудио-кадр, связанный с дорожкой CD, и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Создает новый аудио-кадр и вставляет его в коллекцию фигур в указанный индекс, используя существующий аудио-объект из списка Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Создает новый аудио-кадр с встроенным WAV-файлом и вставляет его в коллекцию фигур в указанный индекс. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Создает новый аудио-кадр, связанный с внешним аудио-файлом, и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Создает новую автофигуру и вставляет её в коллекцию фигур в указанный индекс, применяя форматирование шаблона по умолчанию. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Создает новую автофигуру и вставляет её в коллекцию фигур в указанный индекс, при необходимости инициализируя её оформлением шаблона по умолчанию. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Создает новую диаграмму, инициализирует её примерными данными серии и настройками, и вставляет её в коллекцию фигур в указанный индекс. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Создает новую диаграмму, инициализирует её примерными данными серии и настройками, и вставляет её в коллекцию фигур в указанный индекс. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Создает копию указанной фигуры и вставляет её в коллекцию фигур в указанный индекс. Клонированная фигура сохраняет положение и размер оригинала. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Создает копию указанной фигуры и вставляет её в коллекцию фигур в указанный индекс. Новая фигура сохраняет ширину и высоту *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Создает копию указанной фигуры и вставляет её в коллекцию фигур в указанный индекс. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Создает новую соединительную фигуру и вставляет её в коллекцию фигур в указанный индекс, применяя оформление шаблона по умолчанию. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Создает новую соединительную фигуру и вставляет её в коллекцию фигур в указанный индекс, при необходимости применяя оформление шаблона по умолчанию. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Создает новую пустую групповую фигуру и вставляет её в коллекцию фигур в указанный индекс. Рамка группы автоматически подстраивается под любые добавленные в неё фигуры. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Создает новый кадр OLE-объекта и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Создает новый кадр OLE-объекта и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Создает новый кадр изображения, содержащий указанное изображение, и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Создает новый кадр Section Zoom и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Создает новый кадр Section Zoom с предустановленным изображением и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Создает новый кадр Summary Zoom и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Создает новую таблицу и вставляет её в коллекцию фигур в указанный индекс. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Создает новый видеокадр и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Создает новый кадр Zoom и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Создает новый кадр Zoom с предустановленным изображением и вставляет его в коллекцию фигур в указанный индекс. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Удаляет первое вхождение указанной фигуры из коллекции фигур. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Удаляет фигуру по указанному индексу из коллекции фигур. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Перемещает указанную фигуру в новое положение внутри коллекции фигур. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с заданного индекса. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Создает и возвращает массив, содержащий все фигуры. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив, содержащий все фигуры в указанном диапазоне. |

### Смотрите также

* класс [DomObject&lt;TParent&gt;](../domobject-1)
* класс [GroupShape](../groupshape)
* интерфейс [IShapeCollection](../ishapecollection)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->