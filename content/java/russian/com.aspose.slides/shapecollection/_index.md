---
title: ShapeCollection
second_title: Aspose.Slides для Java: справочник API
description: Представляет коллекцию фигур.
type: docs
url: /ru/com.aspose.slides/shapecollection/
---
**Наследование:**
java.lang.Object, com.aspose.slides.DomObject

**Все реализованные интерфейсы:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Представляет коллекцию фигур.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Получает количество элементов, фактически содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Создаёт новую диаграмму, инициализирует её данными примера серии и настройками, и добавляет её в конец коллекции фигур. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Создаёт новую диаграмму, инициализирует её данными примера серии и настройками, и добавляет её в конец коллекции фигур. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Создаёт новую диаграмму, инициализирует её данными примера серии и настройками, и вставляет её в коллекцию фигур по указанному индексу. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Создаёт новую диаграмму, инициализирует её данными примера серии и настройками, и вставляет её в коллекцию фигур по указанному индексу. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Создаёт новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Создаёт новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Создаёт новый кадр Zoom и вставляет его в коллекцию фигур по указанному индексу. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Создаёт новый кадр Zoom с предопределённым изображением и вставляет его в коллекцию фигур по указанному индексу. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Создаёт новый кадр Section Zoom и добавляет его в конец коллекции фигур. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Создаёт новый кадр Section Zoom с предопределённым изображением и добавляет его в конец коллекции фигур. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Создаёт новый кадр Section Zoom и вставляет его в коллекцию фигур по указанному индексу. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Создаёт новый кадр Section Zoom с предопределённым изображением и вставляет его в коллекцию фигур по указанному индексу. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Создаёт новый кадр Summary Zoom и добавляет его в конец коллекции фигур. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Создаёт новый кадр Summary Zoom и вставляет его в коллекцию фигур по указанному индексу. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур по указанному индексу. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Создаёт новый видеокадр и вставляет его в коллекцию фигур по указанному индексу. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Создаёт новый аудиокадр, связанный с дорожкой CD, и добавляет его в конец коллекции фигур. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Создаёт новый аудиокадр, связанный с дорожкой CD, и вставляет его в коллекцию фигур по указанному индексу. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Создаёт новый аудиокадр, связанный с внешним аудиофайлом, и добавляет его в конец коллекции фигур. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Создаёт новый аудиокадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур по указанному индексу. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Создаёт новый аудиокадр с встроенным WAV-файлом и добавляет его в конец коллекции фигур. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Создаёт новый аудиокадр с встроенным WAV-файлом и вставляет его в коллекцию фигур по указанному индексу. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Создаёт новый аудиокадр и добавляет его в конец коллекции фигур, используя существующий аудио-объект из списка Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Создаёт новый аудиокадр и вставляет его в коллекцию фигур по указанному индексу, используя существующий аудио-объект из списка Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Возвращает нулевой индекс первого вхождения указанной фигуры в коллекцию. |
| [toArray()](#toArray--) | Создаёт и возвращает массив, содержащий все фигуры. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив, содержащий все фигуры в указанном диапазоне. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Перемещает указанную фигуру в новое положение внутри коллекции фигур. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с указанного индекса. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Создаёт новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Создаёт новую автофигуру и добавляет её в конец коллекции фигур, при желании инициализируя её форматированием шаблона по умолчанию. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Создаёт новый автофигурный прямоугольник для размещения математического содержимого и добавляет его в конец коллекции фигур. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Создаёт новую автофигуру и вставляет её в коллекцию фигур по указанному индексу, применяя форматирование шаблона по умолчанию. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Создаёт новую автофигуру и вставляет её в коллекцию фигур по указанному индексу, при желании инициализируя её стилем шаблона по умолчанию. |
| [addGroupShape()](#addGroupShape--) | Создаёт новую пустую групповую фигуру и добавляет её в конец коллекции фигур. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Создаёт новую групповую фигуру, преобразует указанное SVG-изображение в отдельные фигуры и добавляет полученную группу в конец коллекции фигур. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Создаёт новую пустую групповую фигуру и вставляет её в коллекцию фигур по указанному индексу. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Создаёт новую соединительную фигуру с оформлением шаблона по умолчанию и добавляет её в конец коллекции фигур. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Создаёт новую соединительную фигуру и добавляет её в конец коллекции фигур, при желании применяя оформление шаблона по умолчанию. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур по указанному индексу, применяя оформление шаблона по умолчанию. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур по указанному индексу, при желании применяя оформление шаблона по умолчанию. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Создаёт новый кадр изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Создаёт новый кадр изображения, содержащий указанное изображение, и вставляет его в коллекцию фигур по указанному индексу. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Создаёт новую таблицу и добавляет её в конец коллекции фигур. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Создаёт новую таблицу и вставляет её в коллекцию фигур по указанному индексу. |
| [removeAt(int index)](#removeAt-int-) | Удаляет фигуру по указанному индексу из коллекции фигур. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Удаляет первое вхождение указанной фигуры из коллекции фигур. |
| [clear()](#clear--) | Удаляет все фигуры из коллекции фигур. |
| [iterator()](#iterator--) | Возвращает перечислитель, который перебирает элементы коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [getParentGroup()](#getParentGroup--) | Получает объект родительской групповой фигуры для коллекции фигур. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |

### size() {#size--}
```
public final int size()
```

Получает количество элементов, фактически содержащихся в коллекции. Только для чтения  int .

**Возвращает:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Создаёт новую диаграмму, инициализирует её данными примера серии и настройками, и добавляет её в конец коллекции фигур.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Создает экземпляр класса Presentation, который представляет файл PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Получает первый слайд
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Добавляет диаграмму с её данными по умолчанию
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Устанавливает заголовок диаграммы
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Устанавливает отображение значений для первой серии
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Устанавливает индекс листа данных диаграммы
>      int defaultWorksheetIndex = 0;
>      // Получает лист данных диаграммы
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Удаляет автоматически сгенерированные серию и категории
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Добавляет новые серии
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Adds new categories
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Берёт первую серию диаграммы
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Заполняет данные серии
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Устанавливает цвет заливки для серии
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Берёт вторую серию диаграммы
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Заполняет данные серии
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Устанавливает цвет заливки для серии
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Устанавливает первое поле подписи для отображения названия категории
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Устанавливает отображение значения в третьей подписи серии
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Сохраняет файл PPTX на диск
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип диаграммы для добавления. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина диаграммы в пунктах. |
| height | float | Высота диаграммы в пунктах. |

**Возвращает:**
[IChart](../../com.aspose.slides/ichart) - Новосозданный [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Создаёт новую диаграмму, инициализирует её данными примера серии и настройками, и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип диаграммы для добавления. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина диаграммы в пунктах. |
| height | float | Высота диаграммы в пунктах. |
| initWithSample | boolean | True, чтобы инициализировать новую диаграмму данными примера серии и настройками; false, чтобы создать диаграмму без серий и только с минимальными настройками, что ускоряет её создание. |

**Возвращает:**
[IChart](../../com.aspose.slides/ichart) - Новосозданный [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур.

--------------------

> ```
> Следующий пример показывает, как добавить смарт-форму в презентацию PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x кадра диаграммы в пунктах. |
| y | float | Координата y кадра диаграммы в пунктах. |
| width | float | Ширина кадра диаграммы в пунктах. |
| height | float | Высота кадра диаграммы в пунктах. |
| layoutType | int | Тип макета SmartArt. |

**Возвращает:**
[ISmartArt](../../com.aspose.slides/ismartart) - Новосозданный [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Создаёт новую диаграмму, инициализирует её данными примера серии и настройками, и вставляет её в коллекцию фигур по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип диаграммы для создания. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина новой диаграммы в пунктах. |
| height | float | Высота новой диаграммы в пунктах. |
| index | int | Нулевой индекс, по которому вставить новую диаграмму в коллекцию фигур. |

**Возвращает:**
[IChart](../../com.aspose.slides/ichart) - Новосозданный [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Создаёт новую диаграмму, инициализирует её данными примера серии и настройками, и вставляет её в коллекцию фигур по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип диаграммы для создания. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина новой диаграммы в пунктах. |
| height | float | Высота новой диаграммы в пунктах. |
| index | int | Нулевой индекс, по которому вставить новую диаграмму в коллекцию фигур. |
| initWithSample | boolean | True, чтобы инициализировать новую диаграмму данными примера серии и настройками; false, чтобы создать диаграмму без серий и только с минимальными настройками, что ускоряет её создание. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина новой диаграммы в пунктах. |
| height | float | Высота новой диаграммы в пунктах. |
| index | int | Нулевой индекс, по которому следует вставить новую диаграмму в коллекцию фигур. |
| initWithSample | boolean | true, чтобы инициализировать новую диаграмму образцовыми данными и настройками; false, чтобы создать диаграмму без рядов и только с минимальными настройками, что ускоряет создание. |

**Возвращаемое значение:**  
[IChart](../../com.aspose.slides/ichart) - Недавно созданный [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Создает новый Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового Zoom-кадра в пунктах. |
| y | float | Координата y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | Объект [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр; должен принадлежать этой презентации. |

**Возвращаемое значение:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Недавно созданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Создает новый Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Zoom в конец коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два слайда):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового Zoom-кадра в пунктах. |
| y | float | Координата y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | Объект [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр; должен принадлежать этой презентации. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение для ссылочного слайда [IPPImage](../../com.aspose.slides/ippimage). |

**Возвращаемое значение:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Недавно созданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Создает новый Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Zoom в указанный индекс коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два слайда):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить Zoom-кадр. |
| x | float | Координата x нового Zoom-кадра в пунктах. |
| y | float | Координата y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | Объект [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр. |

**Возвращаемое значение:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Недавно созданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Создает новый Zoom-кадр с предустановленным изображением и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Zoom в указанный индекс коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два слайда):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить Zoom-кадр. |
| x | float | Координата x нового Zoom-кадра в пунктах. |
| y | float | Координата y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | Объект [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение для ссылочного слайда [IPPImage](../../com.aspose.slides/ippimage). |

**Возвращаемое значение:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Недавно созданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Создает новый Section Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Section Zoom в конец коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два раздела):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового Section Zoom-кадра в пунктах. |
| y | float | Координата y нового Section Zoom-кадра в пунктах. |
| width | float | Ширина нового Section Zoom-кадра в пунктах. |
| height | float | Высота нового Section Zoom-кадра в пунктах. |
| section | [ISection](../../com.aspose.slides/isection) | Объект [ISection](../../com.aspose.slides/isection), на который ссылается Section Zoom-кадр; должен принадлежать этой презентации и содержать как минимум один слайд. |

**Возвращаемое значение:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Недавно созданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Создает новый Section Zoom-кадр с предустановленным изображением и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Section Zoom в конец коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два раздела):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового Section Zoom-кадра в пунктах. |
| y | float | Координата y нового Section Zoom-кадра в пунктах. |
| width | float | Ширина нового Section Zoom-кадра в пунктах. |
| height | float | Высота нового Section Zoom-кадра в пунктах. |
| section | [ISection](../../com.aspose.slides/isection) | Объект [ISection](../../com.aspose.slides/isection), на который ссылается Section Zoom-кадр; должен принадлежать этой презентации и содержать как минимум один слайд. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение [IPPImage](../../com.aspose.slides/ippimage) для отображения внутри Section Zoom-кадра. |

**Возвращаемое значение:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Недавно созданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Создает новый Section Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Section Zoom в указанный индекс коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два раздела):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить Section Zoom-кадр. |
| x | float | Координата x нового Section Zoom-кадра в пунктах. |
| y | float | Координата y нового Section Zoom-кадра в пунктах. |
| width | float | Ширина нового Section Zoom-кадра в пунктах. |
| height | float | Высота нового Section Zoom-кадра в пунктах. |
| section | [ISection](../../com.aspose.slides/isection) | Объект [ISection](../../com.aspose.slides/isection), на который ссылается Section Zoom-кадр; должен принадлежать этой презентации и содержать как минимум один слайд. |

**Возвращаемое значение:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Недавно созданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Создает новый Section Zoom-кадр с предустановленным изображением и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Section Zoom в указанный индекс коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два раздела):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить Section Zoom-кадр. |
| x | float | Координата x нового Section Zoom-кадра в пунктах. |
| y | float | Координата y нового Section Zoom-кадра в пунктах. |
| width | float | Ширина нового Section Zoom-кадра в пунктах. |
| height | float | Высота нового Section Zoom-кадра в пунктах. |
| section | [ISection](../../com.aspose.slides/isection) | Объект [ISection](../../com.aspose.slides/isection), на который ссылается Section Zoom-кадр; должен принадлежать этой презентации и содержать как минимум один слайд. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение для отображения внутри Section Zoom-кадра. |

**Возвращаемое значение:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Недавно созданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Создает новый Summary Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Summary Zoom в конец коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два раздела):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового Summary Zoom-кадра в пунктах. |
| y | float | Координата y нового Summary Zoom-кадра в пунктах. |
| width | float | Ширина нового Summary Zoom-кадра в пунктах. |
| height | float | Высота нового Summary Zoom-кадра в пунктах. |

Этот метод создает новый Summary Zoom и помещает в него коллекцию объектов для всех разделов этой презентации.

**Возвращаемое значение:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Недавно созданный [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Создает новый Summary Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Summary Zoom в указанный индекс коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум два раздела):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить Summary Zoom-кадр. |
| x | float | Координата x нового Summary Zoom-кадра в пунктах. |
| y | float | Координата y нового Summary Zoom-кадра в пунктах. |
| width | float | Ширина нового Summary Zoom-кадра в пунктах. |
| height | float | Высота нового Summary Zoom-кадра в пунктах. |

Этот метод создает Summary Zoom-кадр, который агрегирует ссылки-резюме для всех разделов в презентации.

**Возвращаемое значение:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Недавно созданный [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Создает новый кадр OLE-объекта и добавляет его в конец коллекции фигур.

--------------------

> ```
> Следующий пример показывает, как добавить OLE Object Frame на слайды PowerPoint презентации.
>  
>  // Создает экземпляр класса Presentation, который представляет PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Получает первый слайд
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Загружает файл .xlsx в поток
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // Создает объект данных для встраивания
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Добавляет форму OLE Object Frame
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Сохраняет PPTX на диск
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового OLE-кадра в пунктах. |
| y | float | Координата y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Информация о вложенных данных OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Возвращаемое значение:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Недавно созданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Создает новый кадр OLE-объекта и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового OLE-кадра в пунктах. |
| y | float | Координата y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| className | java.lang.String | Имя класса OLE-объекта. |
| path | java.lang.String | Путь к связанному файлу.

Этот путь сохраняется в презентации без изменений. Если указан относительный путь, файл будет недоступен при открытии презентации из другого каталога. |

**Возвращаемое значение:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Недавно созданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Создает новый кадр OLE-объекта и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует вставку OLE объекта во второй позиции:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить кадр OLE-объекта. |
| x | float | Координата x нового OLE-кадра в пунктах. |
| y | float | Координата y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Встроенная информация OLE-данных ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Возвращаемое значение:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - только что созданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Создает новый OLE-объектный кадр и вставляет его в коллекцию фигур по указанному индексу.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлен OLE-объектный кадр. |
| x | float | Координата x нового OLE-кадра в пунктах. |
| y | float | Координата y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| className | java.lang.String | Имя класса OLE-объекта. |
| path | java.lang.String | Путь к связанному файлу.  

Этот путь сохраняется в презентации без изменений. Если указан относительный путь, файл будет недоступен при открытии презентации из другого каталога. |

**Возвращаемое значение:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - только что созданный OLE-объектный кадр.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Создает новый видеокадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Координата x нового видеокадра в пунктах. |
| y | float | Координата y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| fname | java.lang.String | Путь или имя видеофайла для внедрения. |

**Возвращаемое значение:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - только что созданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Создает новый видеокадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Координата x нового видеокадра в пунктах. |
| y | float | Координата y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) для внедрения в видеокадр. |

**Возвращаемое значение:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - только что созданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Создает новый видеокадр и вставляет его в коллекцию фигур по указанному индексу.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлен видеокадр. |
| x | float | Координата x нового видеокадра в пунктах. |
| y | float | Координата y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| fname | java.lang.String | Путь или имя видеофайла для внедрения. |

**Возвращаемое значение:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - только что созданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Создает новый аудиокадр, связанный с дорожкой CD, и добавляет его в конец коллекции фигур.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |

**Возвращаемое значение:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - только что созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Создает новый аудиокадр, связанный с дорожкой CD, и вставляет его в коллекцию фигур по указанному индексу.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлен аудиокадр. |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |

**Возвращаемое значение:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - только что созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Создает новый аудиокадр, связанный с внешним аудиофайлом, и добавляет его в конец коллекции фигур.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| fname | java.lang.String | Путь или имя внешнего аудиофайла для ссылки. |

**Возвращаемое значение:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - только что созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Создает новый аудиокадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур по указанному индексу.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлен аудиокадр. |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| fname | java.lang.String | Путь или имя внешнего аудиофайла для ссылки. |

**Возвращаемое значение:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - только что созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Создает новый аудиокадр с внедренным WAV-файлом и добавляет его в конец коллекции фигур. Встроенный аудио добавляется в коллекцию Presentation.Audios.

--------------------

> ```
> Следующий пример показывает, как создать Audio Frame.
>  
>  // Создает экземпляр класса презентации, который представляет файл презентации
>  Presentation pres = new Presentation();
>  try {
>      // Получает первый слайд
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Загружает wav звуковой файл в поток
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Добавляет Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Устанавливает режим воспроизведения и громкость аудио
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Сохраняет файл PowerPoint на диск
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio_stream | java.io.InputStream | Поток ввода, содержащий WAV-данные для внедрения. |

**Возвращаемое значение:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - только что созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Создает новый аудиокадр с внедренным WAV-файлом и вставляет его в коллекцию фигур по указанному индексу. Встроенный аудио добавляется в коллекцию Presentation.Audios.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлен аудиокадр. |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio_stream | java.io.InputStream | Поток ввода, содержащий WAV-данные для внедрения. |

**Возвращаемое значение:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - только что созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Создает новый аудиокадр и добавляет его в конец коллекции фигур, используя существующий объект аудио из списка Presentation.Audios.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Экземпляр [IAudio](../../com.aspose.slides/iaudio) из коллекции Presentation.Audios. |

**Возвращаемое значение:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - только что созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Создает новый аудиокадр и вставляет его в коллекцию фигур по указанному индексу, используя существующий объект аудио из списка Presentation.Audios.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлен аудиокадр. |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Экземпляр [IAudio](../../com.aspose.slides/iaudio) из коллекции Presentation.Audios для внедрения. |

**Возвращаемое значение:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - только что созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Возвращает нулевой индекс первого вхождения указанной фигуры в коллекцию.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, которую необходимо найти в коллекции. |

**Возвращаемое значение:**  
int - Нулевой индекс первого вхождения фигуры в коллекцию фигур, если найдена; иначе \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Создает и возвращает массив, содержащий все фигуры.

**Возвращаемое значение:**  
com.aspose.slides.IShape[] - Массив объектов [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Создает и возвращает массив, содержащий все фигуры в указанном диапазоне.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Индекс первой фигуры для возврата. |
| count | int | Количество фигур для возврата. |

**Возвращаемое значение:**  
com.aspose.slides.IShape[] - Массив объектов [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Перемещает указанную фигуру в новое положение внутри коллекции фигур.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой целевой индекс, куда будет помещена фигура. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape), которую нужно переместить в коллекции. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с указанного индекса.

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Нулевой целевой индекс, где будет помещена первая указанная фигура; последующие фигуры следуют в порядке, указанном в массиве. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Один или несколько экземпляров [IShape](../../com.aspose.slides/ishape) для перемещения внутри коллекции. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Создаёт новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автофигуры для добавления. |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) – только что созданный [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую автофигуру и добавляет её в конец коллекции фигур, опционально инициализируя её форматированием из шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автофигуры для добавления. |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |
| createFromTemplate | boolean | true — применить стиль шаблона по умолчанию (простой стиль, центрированный текст и непустое имя) к новой фигуре; false — создать фигуру со всеми свойствами, имеющими значения по умолчанию. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) – только что созданный [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Создаёт новый прямоугольный автофрейм для размещения математического содержимого и добавляет его в конец коллекции фигур.

--------------------

> ```
> The following example shows how to add Mathematical Equation in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) – только что созданный [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Создаёт новую автофигуру и вставляет её в коллекцию фигур в указанную позицию, применяя стиль шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить новую автофигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автофигуры для вставки. |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) – только что созданный [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую автофигуру и вставляет её в коллекцию фигур в указанную позицию, опционально инициализируя её стиль шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить автофигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автофигуры для вставки. |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |
| createFromTemplate | boolean | true — применить стиль шаблона по умолчанию (включая непустое имя, простой стиль и центрированный текст); false — создать фигуру со всеми свойствами, имеющими значения по умолчанию. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) – только что созданный [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Создаёт новую пустую группирующую фигуру и добавляет её в конец коллекции фигур. Объём группы автоматически подстраивается под любые добавленные в неё фигуры.

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Instantiate Presentation class
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Accessing the shape collection of slides
>      IShapeCollection slideShapes = sld.getShapes();
>      // Adding a group shape to the slide
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Adding shapes inside added group shape
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Adding group shape frame
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Write the PPTX file to disk
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape) – только что созданный [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Создаёт новую группирующую фигуру, преобразует указанное SVG-изображение в отдельные фигуры и добавляет полученную группу в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) с векторным содержимым для преобразования в фигуры. |
| x | float | Координата x рамки группы, в пунктах. |
| y | float | Координата y рамки группы, в пунктах. |
| width | float | Ширина рамки группы, в пунктах. |
| height | float | Высота рамки группы, в пунктах. |

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape) – только что созданный [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Создаёт новую пустую группирующую фигуру и вставляет её в коллекцию фигур в указанную позицию. Объём группы автоматически подстраивается под любые добавленные в неё фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить группирующую фигуру. |

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape) – только что созданный [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Создаёт новую соединительную фигуру со стилем шаблона по умолчанию и добавляет её в конец коллекции фигур.

--------------------

> ```
> The following example shows how to add a connector (a bent connector) between two shapes (an ellipse and rectangle) in PowerPoint Presentation.
>  
>  // Instantiates a presentation class that represents a PPTX file
>  Presentation pres = new Presentation();
>  try {
>      // Accesses the shapes collection for a specific slide
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Adds an Ellipse autoshape
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Adds a Rectangle autoshape
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Adds a connector shape to the slide shape collection
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Connects the shapes using the connector
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Calls reroute that sets the automatic shortest path between shapes
>      connector.reroute();
>      // Saves the presentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительной фигуры для добавления. |
| x | float | Координата x рамки соединителя, в пунктах. |
| y | float | Координата y рамки соединителя, в пунктах. |
| width | float | Ширина рамки соединителя, в пунктах. |
| height | float | Высота рамки соединителя, в пунктах. |

**Возвращаемое значение:**
[IConnector](../../com.aspose.slides/iconnector) – только что созданный [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую соединительную фигуру и добавляет её в конец коллекции фигур, опционально применяя стиль шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительной фигуры для создания. |
| x | float | Координата x рамки соединителя, в пунктах. |
| y | float | Координата y рамки соединителя, в пунктах. |
| width | float | Ширина рамки соединителя, в пунктах. |
| height | float | Высота рамки соединителя, в пунктах. |
| createFromTemplate | boolean | true — применить стиль шаблона по умолчанию (непустое имя, простой стиль); false — создать соединитель со значениями свойств по умолчанию. |

**Возвращаемое значение:**
[IConnector](../../com.aspose.slides/iconnector) – только что созданный [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур в указанную позицию, применяя стиль шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить соединительную фигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительной фигуры для вставки. |
| x | float | Координата x рамки соединителя, в пунктах. |
| y | float | Координата y рамки соединителя, в пунктах. |
| width | float | Ширина рамки соединителя, в пунктах. |
| height | float | Высота рамки соединителя, в пунктах. |

**Возвращаемое значение:**
[IConnector](../../com.aspose.slides/iconnector) – только что созданный [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур в указанную позицию, опционально применяя стиль шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить соединительную фигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительной фигуры для вставки. |
| x | float | Координата x рамки соединителя, в пунктах. |
| y | float | Координата y рамки соединителя, в пунктах. |
| width | float | Ширина рамки соединителя, в пунктах. |
| height | float | Высота рамки соединителя, в пунктах. |
| createFromTemplate | boolean | true — применить стиль шаблона по умолчанию (непустое имя, простой стиль); false — создать соединитель со значениями свойств по умолчанию. |

**Возвращаемое значение:**
[IConnector](../../com.aspose.slides/iconnector) – только что созданный [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Создаёт новый рамочный объект изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | Указывает тип фигуры, содержащейся в [ShapeType](../../com.aspose.slides/shapetype), за исключением всех видов линий: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Координата x рамки изображения, в пунктах. |
| y | float | Координата y рамки изображения, в пунктах. |
| width | float | Ширина рамки изображения, в пунктах. |
| height | float | Высота рамки изображения, в пунктах. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) для отображения в рамке изображения. |

**Возвращаемое значение:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – только что созданный [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Создаёт новый рамочный объект изображения, содержащий указанное изображение, и вставляет его в коллекцию фигур в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить рамку изображения. |
| shapeType | int | Указывает тип фигуры, содержащейся в [ShapeType](../../com.aspose.slides/shapetype), за исключением всех видов линий: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Координата x рамки изображения, в пунктах. |
| y | float | Координата y рамки изображения, в пунктах. |
| width | float | Ширина рамки изображения, в пунктах. |
| height | float | Высота рамки изображения, в пунктах. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) для отображения в рамке изображения. |

**Возвращаемое значение:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – только что созданный [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Создаёт новую таблицу и добавляет её в конец коллекции фигур.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents PPTX file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Access first slide
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Define columns with widths and rows with heights
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Add table shape to slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Set border format for each cell
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // Merge cells 1 & 2 of row 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Add text to the merged cell
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Save PPTX to Disk
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```
**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x таблицы в пунктах. |
| y | float | Координата y таблицы в пунктах. |
| columnWidths | double[] | Массив double, представляющий ширины столбцов таблицы, в пунктах. |
| rowHeights | double[] | Массив double, представляющий высоты строк таблицы, в пунктах. |

**Возвращаемое значение:**
[ITable](../../com.aspose.slides/itable) - Новый созданный [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Создаёт новую таблицу и вставляет её в коллекцию фигур по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлена таблица. |
| x | float | Координата x таблицы в пунктах. |
| y | float | Координата y таблицы в пунктах. |
| columnWidths | double[] | Массив double, представляющий ширины столбцов таблицы, в пунктах. |
| rowHeights | double[] | Массив double, представляющий высоты строк таблицы, в пунктах. |

**Возвращаемое значение:**
[ITable](../../com.aspose.slides/itable) - Новый созданный [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет фигуру с заданным индексом из коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс удаляемой фигуры. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Удаляет первое вхождение указанной фигуры из коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) для удаления. |

### clear() {#clear--}
```
public final void clear()
```

Удаляет все фигуры из коллекции фигур.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Возвращает перечислитель, который перебирает элементы коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumerator, который можно использовать для перебора коллекции.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator для всей коллекции.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Получает объект родительской групповой фигуры для коллекции фигур. Только для чтения [IGroupShape](../../com.aspose.slides/igroupshape).

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Фигура для клонирования. |
| x | float | Координата x нового кадра фигуры в пунктах. |
| y | float | Координата y нового кадра фигуры в пунктах. |
| width | float | Ширина нового кадра фигуры в пунктах. |
| height | float | Высота нового кадра фигуры в пунктах. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Новый созданный [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. Новая фигура сохраняет ширину и высоту исходной фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Фигура для клонирования. |
| x | float | Координата x нового кадра фигуры в пунктах. |
| y | float | Координата y нового кадра фигуры в пунктах. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Новый созданный [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. Клонированная фигура сохраняет исходную позицию и размер.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) для клонирования. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Новый созданный [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлена клонированная фигура. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) для клонирования. |
| x | float | Координата x клонированной фигуры в пунктах. |
| y | float | Координата y клонированной фигуры в пунктах. |
| width | float | Ширина клонированной фигуры в пунктах. |
| height | float | Высота клонированной фигуры в пунктах. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Новый созданный [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по заданному индексу. Новая фигура сохраняет ширину и высоту исходной фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлена клонированная фигура. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) для клонирования. |
| x | float | Координата x клонированной фигуры в пунктах. |
| y | float | Координата y клонированной фигуры в пунктах. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Новый созданный [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по заданному индексу. Клонированная фигура сохраняет исходную позицию и размер.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлена клонированная фигура. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) для клонирования. |

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape) - Новый созданный [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Копирует все элементы коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращаемое значение:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object