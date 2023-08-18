---
title: IShapeCollection
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет набор фигур.
type: docs
weight: 6400
url: /ru/aspose.slides/ishapecollection/
---
## IShapeCollection interface

Представляет набор фигур.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Характеристики

| Имя | Описание |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Получает элемент по указанному индексу. Только для чтения[`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Возвращает родительский объект GroupShape для коллекции фигур. Только для чтения[`IGroupShape`](../igroupshape). |

## Методы

| Имя | Описание |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Добавляет AudioFrame с компакт-диском в конец коллекции. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Добавляет в конец коллекции новый аудиокадр со встроенным аудиофайлом. Используется аудиофайл из списка Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Добавляет в конец коллекции новый аудиокадр со встроенным аудиофайлом. Встроенный аудиофайл может быть только в формате WAV. Добавляет новый звук в список Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Добавляет новый аудиокадр со связанным аудиофайлом в конец коллекции. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Создает новую автофигуру, настраивает ее из шаблона по умолчанию и добавляет в конец коллекции. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Создает новую автофигуру и добавляет ее в конец коллекции. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Создает новую диаграмму, инициализирует ее данными и настройками серии образцов и добавляет в конец коллекции. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Создает новую диаграмму и добавляет ее в конец коллекции. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Добавляет копию указанной фигуры в конец коллекции. X, Y, ширина и высота новой формы равны X, Y, ширине и высоте*sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Добавляет копию указанной фигуры в конец коллекции. Ширина и высота новой формы равны ширине и высоте*sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Добавляет копию указанной фигуры в конец коллекции. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Создает новый коннектор, настраивает его из шаблона по умолчанию и добавляет в конец коллекции. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Создает новый коннектор и добавляет его в конец коллекции. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Создает новый GroupShape и добавляет его в конец коллекции. Размер и положение кадра GroupShape будут соответствовать содержимому, когда в GroupShape будет добавлена новая фигура. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Создает новый GroupShape, заполняет его преобразованными фигурами из SVG и добавляет в конец коллекции. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Создает новую автофигуру типа Rectangle для размещения внутри математического содержимого и добавляет ее в конец коллекции. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Добавляет новый объект OLE в конец коллекции. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Добавляет новый объект OLE в конец коллекции. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Создает новый PictureFrame и добавляет его в конец коллекции. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Добавляет новый объект Section Zoom в конец коллекции. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Добавляет новый объект Section Zoom в конец коллекции с предопределенным изображением. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Добавить диаграмму SmartArt. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Добавляет новый объект Суммарное масштабирование в конец коллекции. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Создает новую таблицу и добавляет ее в конец коллекции. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Добавляет новый видеокадр в конец коллекции. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Добавляет новый видеокадр в конец коллекции. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Добавляет новый объект Zoom в конец коллекции. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Добавляет новый объект Zoom в конец коллекции. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Удаляет все фигуры из коллекции. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Возвращает отсчитываемый от нуля индекс первого вхождения фигуры в коллекцию. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Вставьте AudioFrame с CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Вставьте AudioFrame со встроенным аудиофайлом. Используется аудиофайл из списка Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Вставьте AudioFrame со встроенным аудиофайлом. Звук встроенного аудиофайла может быть только в формате WAV. Добавляет новый звук в список Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Создает новый аудиокадр со связанным аудиофайлом и вставляет его в коллекцию по указанному индексу. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Создает новую автофигуру, настраивает ее из шаблона по умолчанию и вставляет в коллекцию по указанному индексу. Примечание:тип фигуры будет определяться параметром shapeType. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Создает новую автофигуру и вставляет ее в коллекцию по указанному индексу. Примечание:тип фигуры будет определяться параметром shapeType. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Создает новую диаграмму, инициализирует ее данными и настройками серии образцов и вставляет в указанную позицию в коллекции. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Создает новую диаграмму и вставляет ее в указанную позицию в коллекции. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Вставляет копию указанной формы в указанную позицию коллекции. X, Y, ширина и высота новой формы равны X, Y, ширине и высоте*sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Вставляет копию указанной формы в указанную позицию коллекции. Ширина и высота новой формы равны ширине и высоте*sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Вставляет копию указанной формы в указанную позицию коллекции. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Создает новый коннектор, настраивает его из шаблона по умолчанию и вставляет в коллекцию по указанному индексу. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Создает новый коннектор и вставляет его в коллекцию по указанному индексу. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Создает новый GroupShape и вставляет его в коллекцию по указанному индексу. Размер и положение кадра GroupShape будут соответствовать содержимому, когда в GroupShape будет добавлена новая фигура. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Создает новый объект OLE и вставляет его в коллекцию по указанному индексу. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Создает новый объект OLE и вставляет его в коллекцию по указанному индексу. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Создает новый PictureFrame и вставляет его в коллекцию по указанному индексу. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Создает новый объект Section Zoom и вставляет его в коллекцию по указанному индексу. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Создает новый объект Section Zoom и вставляет его в коллекцию по указанному индексу. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Создает новый объект Суммарный масштаб и вставляет его в коллекцию по указанному индексу. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Создает новую таблицу и вставляет ее в коллекцию по указанному индексу. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Создает новый видеокадр и вставляет его в коллекцию по указанному индексу. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Создает новый объект Zoom и вставляет его в коллекцию по указанному индексу. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Создает новый объект Zoom и вставляет его в коллекцию по указанному индексу. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Удаляет первое вхождение определенной формы из коллекции. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Удаляет элемент по указанному индексу коллекции. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Перемещает фигуру из коллекции в указанную позицию. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Перемещает фигуры из коллекции в указанную позицию. Фигуры будут размещены, начиная с индекса, в том порядке, в котором они появляются в списке. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Создает и возвращает массив со всеми формами в нем. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Создает и возвращает массив со всеми фигурами из указанного диапазона. |

### Смотрите также

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* пространство имен [Aspose.Slides](../../aspose.slides)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
