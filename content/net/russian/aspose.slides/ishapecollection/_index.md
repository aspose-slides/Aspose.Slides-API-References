---
title: IShapeCollection
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет коллекцию фигур.
type: docs
weight: 6980
url: /ru/aspose.slides/ishapecollection/
---
## IShapeCollection интерфейс

Представляет коллекцию фигур.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Возвращает элемент по указанному индексу. Только для чтения [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Возвращает объект родительской группы фигур для коллекции фигур. Только для чтения [`IGroupShape`](../igroupshape). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Создаёт новый аудио-кадр, связанный с дорожкой CD, и добавляет его в конец коллекции фигур. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Создаёт новый аудио-кадр и добавляет его в конец коллекции фигур, используя существующий аудио-объект из списка Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Создаёт новый аудио-кадр с вложенным WAV-файлом и добавляет его в конец коллекции фигур. Вложенный аудио-файл добавляется в коллекцию Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Создаёт новый аудио-кадр, связанный с внешним аудио-файлом, и добавляет его в конец коллекции фигур. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Создаёт новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Создаёт новую автофигуру и добавляет её в конец коллекции фигур, необязательно инициализируя её форматированием шаблона по умолчанию. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Создаёт новую диаграмму, инициализирует её образцовыми данными серии и настройками, и добавляет её в конец коллекции фигур. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Создаёт новую диаграмму, инициализирует её образцовыми данными серии и настройками, и добавляет её в конец коллекции фигур. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. Клонированная фигура сохраняет позицию и размер оригинала. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. Новая фигура сохраняет ширину и высоту *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Создаёт новую соединительную фигуру с оформлением шаблона по умолчанию и добавляет её в конец коллекции фигур. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Создаёт новую соединительную фигуру и добавляет её в конец коллекции фигур, при желании применяя оформление шаблона по умолчанию. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Создаёт новую пустую групповую фигуру и добавляет её в конец коллекции фигур. Рамка группы автоматически подстраивается под любые добавленные в неё фигуры. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Создаёт новую групповую фигуру, преобразует указанное SVG-изображение в отдельные фигуры и добавляет полученную группу в конец коллекции фигур. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Создаёт новую автофигуру-прямоугольник для размещения математического контента и добавляет её в конец коллекции фигур. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Создаёт новый кадр изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Создаёт новый кадр Section Zoom и добавляет его в конец коллекции фигур. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Создаёт новый кадр Section Zoom с предопределённым изображением и добавляет его в конец коллекции фигур. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Создаёт новый кадр Summary Zoom и добавляет его в конец коллекции фигур. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Создаёт новую таблицу и добавляет её в конец коллекции фигур. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Создаёт новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Создаёт новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Удаляет все фигуры из коллекции фигур. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Возвращает нулевой индекс первого вхождения указанной фигуры в коллекцию. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Создаёт новый аудио-кадр, связанный с дорожкой CD, и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Создаёт новый аудио-кадр и вставляет его в коллекцию фигур в указанный индекс, используя существующий аудио-объект из списка Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Создаёт новый аудио-кадр с вложенным WAV-файлом и вставляет его в коллекцию фигур в указанный индекс. Вложенный аудио-файл добавляется в коллекцию Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Создаёт новый аудио-кадр, связанный с внешним аудио-файлом, и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Создаёт новую автофигуру и вставляет её в коллекцию фигур в указанный индекс, применяя форматирование шаблона по умолчанию. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Создаёт новую автофигуру и вставляет её в коллекцию фигур в указанный индекс, при желании инициализируя её оформлением шаблона по умолчанию. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Создаёт новую диаграмму, инициализирует её образцовыми данными серии и настройками, и вставляет её в коллекцию фигур в указанный индекс. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Создаёт новую диаграмму, инициализирует её образцовыми данными серии и настройками, и вставляет её в коллекцию фигур в указанный индекс. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанный индекс. Клонированная фигура сохраняет позицию и размер оригинала. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанный индекс. Новая фигура сохраняет ширину и высоту *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанный индекс. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур в указанный индекс, применяя оформление шаблона по умолчанию. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур в указанный индекс, при желании применяя оформление шаблона по умолчанию. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Создаёт новую пустую групповую фигуру и вставляет её в коллекцию фигур в указанный индекс. Рамка группы автоматически подстраивается под любые добавленные в неё фигуры. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Создаёт новый кадр изображения, содержащий указанное изображение, и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Создаёт новый кадр Section Zoom и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Создаёт новый кадр Section Zoom с предопределённым изображением и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Создаёт новый кадр Summary Zoom и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Создаёт новую таблицу и вставляет её в коллекцию фигур в указанный индекс. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Создаёт новый видеокадр и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Создаёт новый кадр Zoom и вставляет его в коллекцию фигур в указанный индекс. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Создаёт новый кадр Zoom с предопределённым изображением и вставляет его в коллекцию фигур в указанный индекс. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Удаляет первое вхождение указанной фигуры из коллекции фигур. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Удаляет фигуру по указанному индексу из коллекции фигур. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Перемещает указанную фигуру в новое положение внутри коллекции фигур. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с указанного индекса. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Создаёт и возвращает массив, содержащий все фигуры. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Создаёт и возвращает массив, содержащий все фигуры в указанном диапазоне. |

### Смотрите также

* интерфейс [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* интерфейс [IShape](../ishape)
* пространство имён [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->