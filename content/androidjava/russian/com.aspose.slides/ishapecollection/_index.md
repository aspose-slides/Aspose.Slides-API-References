---
title: IShapeCollection
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет коллекцию фигур.
type: docs
url: /ru/com.aspose.slides/ishapecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Представляет коллекцию фигур.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [getParentGroup()](#getParentGroup--) | Получает объект родительской группы для коллекции фигур. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и параметрами и добавляет её в конец коллекции фигур. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и параметрами и добавляет её в конец коллекции фигур. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и параметрами и вставляет её в коллекцию фигур в указанном индексе. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и параметрами и вставляет её в коллекцию фигур в указанном индексе. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Создаёт новый OLE-объектный кадр и добавляет его в конец коллекции фигур. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Создаёт новый OLE-объектный кадр и добавляет его в конец коллекции фигур. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Создаёт новый OLE-объектный кадр и вставляет его в коллекцию фигур в указанном индексе. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Создаёт новый OLE-объектный кадр и вставляет его в коллекцию фигур в указанном индексе. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Создаёт новый Zoom-кадр и добавляет его в конец коллекции фигур. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Создаёт новый Zoom-кадр и добавляет его в конец коллекции фигур. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Создаёт новый Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Создаёт новый Zoom-кадр с предопределённым изображением и вставляет его в коллекцию фигур в указанном индексе. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Создаёт новый Section Zoom-кадр и добавляет его в конец коллекции фигур. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Создаёт новый Section Zoom-кадр с предопределённым изображением и добавляет его в конец коллекции фигур. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Создаёт новый Section Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Создаёт новый Section Zoom-кадр с предопределённым изображением и вставляет его в коллекцию фигур в указанном индексе. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Создаёт новый Summary Zoom-кадр и добавляет его в конец коллекции фигур. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Создаёт новый Summary Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Создаёт новый видеокадр и вставляет его в коллекцию фигур в указанном индексе. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Создаёт новый аудиокадр, связанный с дорожкой CD, и добавляет его в конец коллекции фигур. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Создаёт новый аудиокадр, связанный с дорожкой CD, и вставляет его в коллекцию фигур в указанном индексе. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Создаёт новый аудиокадр, связанный с внешним аудиофайлом, и добавляет его в конец коллекции фигур. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Создаёт новый аудиокадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур в указанном индексе. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Создаёт новый аудиокадр со встроенным WAV-файлом и добавляет его в конец коллекции фигур. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Создаёт новый аудиокадр и добавляет его в конец коллекции фигур, используя существующий аудиофайл из списка Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Создаёт новый аудиокадр со встроенным WAV-файлом и вставляет его в коллекцию фигур в указанном индексе. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Создаёт новый аудиокадр и вставляет его в коллекцию фигур в указанном индексе, используя существующий аудиофайл из списка Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Возвращает нулевой-базовый индекс первого вхождения указанной фигуры в коллекцию. |
| [toArray()](#toArray--) | Создаёт и возвращает массив, содержащий все фигуры. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив, содержащий все фигуры в указанном диапазоне. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Перемещает указанную фигуру в новое положение внутри коллекции фигур. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с указанного индекса. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Создаёт новую автогенерируемую фигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Создаёт новую автогенерируемую фигуру и добавляет её в конец коллекции фигур, опционально инициализируя её форматированием шаблона по умолчанию. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Создаёт новый прямоугольный автогенерируемый объект для размещения математического контента и добавляет его в конец коллекции фигур. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Создаёт новую автогенерируемую фигуру и вставляет её в коллекцию фигур в указанном индексе, применяя форматирование шаблона по умолчанию. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Создаёт новую автогенерируемую фигуру и вставляет её в коллекцию фигур в указанном индексе, опционально инициализируя её стилизацией шаблона по умолчанию. |
| [addGroupShape()](#addGroupShape--) | Создаёт новую пустую группу фигур и добавляет её в конец коллекции фигур. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Создаёт новую группу фигур, преобразует указанный SVG-изображение в отдельные фигуры и добавляет получившуюся группу в конец коллекции фигур. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Создаёт новую пустую группу фигур и вставляет её в коллекцию фигур в указанном индексе. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Создаёт новый соединительный объект с стилизацией шаблона по умолчанию и добавляет его в конец коллекции фигур. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Создаёт новый соединительный объект и добавляет его в конец коллекции фигур, опционально применяя стилизацию шаблона по умолчанию. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Создаёт новый соединительный объект и вставляет его в коллекцию фигур в указанном индексе, применяя стилизацию шаблона по умолчанию. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Создаёт новый соединительный объект и вставляет его в коллекцию фигур в указанном индексе, опционально применяя стилизацию шаблона по умолчанию. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Создаёт новый кадр изображения, содержащий указанный файл, и добавляет его в конец коллекции фигур. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Создаёт новый кадр изображения, содержащий указанный файл, и вставляет его в коллекцию фигур в указанном индексе. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Создаёт новую таблицу и добавляет её в конец коллекции фигур. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Создаёт новую таблицу и вставляет её в коллекцию фигур в указанном индексе. |
| [removeAt(int index)](#removeAt-int-) | Удаляет фигуру в указанном индексе из коллекции фигур. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Удаляет первое вхождение указанной фигуры из коллекции фигур. |
| [clear()](#clear--) | Удаляет все фигуры из коллекции фигур. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанном индексе. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанном индексе. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанном индексе. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Получает объект родительской группы для коллекции фигур. Только для чтения [IGroupShape](../../com.aspose.slides/igroupshape).

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и параметрами и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип добавляемой диаграммы. |
| x | float | Координата X новой диаграммы в пунктах. |
| y | float | Координата Y новой диаграммы в пунктах. |
| width | float | Ширина диаграммы в пунктах. |
| height | float | Высота диаграммы в пунктах. |

**Возвращает:**
[IChart](../../com.aspose.slides/ichart) – Новосозданный [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и параметрами и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип добавляемой диаграммы. |
| x | float | Координата X новой диаграммы в пунктах. |
| y | float | Координата Y новой диаграммы в пунктах. |
| width | float | Ширина диаграммы в пунктах. |
| height | float | Высота диаграммы в пунктах. |
| initWithSample | boolean | true – инициализировать диаграмму образцовыми данными и параметрами; false – создать диаграмму без рядов и лишь с минимальными параметрами, что ускоряет создание. |

**Возвращает:**
[IChart](../../com.aspose.slides/ichart) – Новосозданный [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X рамки диаграммы в пунктах. |
| y | float | Координата Y рамки диаграммы в пунктах. |
| width | float | Ширина рамки диаграммы в пунктах. |
| height | float | Высота рамки диаграммы в пунктах. |
| layoutType | int | Тип компоновки SmartArt. |

**Возвращает:**
[ISmartArt](../../com.aspose.slides/ismartart) – Новосозданный [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и параметрами и вставляет её в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип создаваемой диаграммы. |
| x | float | Координата X новой диаграммы в пунктах. |
| y | float | Координата Y новой диаграммы в пунктах. |
| width | float | Ширина новой диаграммы в пунктах. |
| height | float | Высота новой диаграммы в пунктах. |
| index | int | Нулевой-базовый индекс, в котором вставить новую диаграмму в коллекцию фигур. |

**Возвращает:**
[IChart](../../com.aspose.slides/ichart) – Новосозданный [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Создаёт новую диаграмму, инициализирует её образцовыми данными рядов и параметрами и вставляет её в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип создаваемой диаграммы. |
| x | float | Координата X новой диаграммы в пунктах. |
| y | float | Координата Y новой диаграммы в пунктах. |
| width | float | Ширина новой диаграммы в пунктах. |
| height | float | Высота новой диаграммы в пунктах. |
| index | int | Нулевой-базовый индекс, в котором вставить новую диаграмму в коллекцию фигур. |
| initWithSample | boolean | true – инициализировать диаграмму образцовыми данными и параметрами; false – создать без рядов и только с минимальными параметрами, что ускоряет создание. |

**Возвращает:**
[IChart](../../com.aspose.slides/ichart) – Новосозданный [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Создаёт новый OLE-объектный кадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового OLE-кадра в пунктах. |
| y | float | Координата Y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Информация о внедрённых OLE-данных ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Возвращает:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Новосозданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Создаёт новый OLE-объектный кадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового OLE-кадра в пунктах. |
| y | float | Координата Y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| className | java.lang.String | Имя класса OLE-объекта. |
| path | java.lang.String | Путь к связанному файлу.

Этот путь сохраняется в презентации без изменений. Если указан относительный путь, файл будет недоступен при открытии презентации из другой директории. |

**Возвращает:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Новосозданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Создаёт новый OLE-объектный кадр и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить OLE-кадр. |
| x | float | Координата X нового OLE-кадра в пунктах. |
| y | float | Координата Y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Информация о внедрённых OLE-данных ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Возвращает:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Новосозданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Создаёт новый OLE-объектный кадр и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить OLE-кадр. |
| x | float | Координата X нового OLE-кадра в пунктах. |
| y | float | Координата Y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| className | java.lang.String | Имя класса OLE-объекта. |
| path | java.lang.String | Путь к связанному файлу.

Этот путь сохраняется в презентации без изменений. Если указан относительный путь, файл будет недоступен при открытии презентации из другой директории. |

**Возвращает:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Новосозданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Создаёт новый Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Zoom в конец коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два слайда):
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
| x | float | Координата X нового Zoom-кадра в пунктах. |
| y | float | Координата Y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр; должен принадлежать этой презентации. |

**Возвращает:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Новосозданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Создаёт новый Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Zoom в конец коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два слайда):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового Zoom-кадра в пунктах. |
| y | float | Координата Y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр; должен принадлежать этой презентации. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение для связанного слайда [IPPImage](../../com.aspose.slides/ippimage). |

**Возвращает:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Новосозданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Создаёт новый Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Zoom в указанный индекс коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два слайда):
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
| index | int | Нулевой-базовый индекс, в котором вставить Zoom-кадр. |
| x | float | Координата X нового Zoom-кадра в пунктах. |
| y | float | Координата Y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр. |

**Возвращает:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Новосозданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Создаёт новый Zoom-кадр с предопределённым изображением и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Zoom в указанный индекс коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два слайда):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить Zoom-кадр. |
| x | float | Координата X нового Zoom-кадра в пунктах. |
| y | float | Координата Y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение для связанного слайда [IPPImage](../../com.aspose.slides/ippimage). |

**Возвращает:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Новосозданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Создаёт новый Section Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Section Zoom в конец коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два раздела):
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
| x | float | Координата X нового Section Zoom-кадра в пунктах. |
| y | float | Координата Y нового Section Zoom-кадра в пунктах. |
| width | float | Ширина нового Section Zoom-кадра в пунктах. |
| height | float | Высота нового Section Zoom-кадра в пунктах. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection), на который ссылается Section Zoom-кадр; должен принадлежать этой презентации и содержать хотя бы один слайд. |

**Возвращает:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Новосозданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Создаёт новый Section Zoom-кадр с предопределённым изображением и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Section Zoom в конец коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два раздела):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового Section Zoom-кадра в пунктах. |
| y | float | Координата Y нового Section Zoom-кадра в пунктах. |
| width | float | Ширина нового Section Zoom-кадра в пунктах. |
| height | float | Высота нового Section Zoom-кадра в пунктах. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection), на который ссылается Section Zoom-кадр; должен принадлежать этой презентации и содержать хотя бы один слайд. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage), отображаемый внутри Section Zoom-кадра. |

**Возвращает:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Новосозданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Создаёт новый Section Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Section Zoom в указанный индекс коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два раздела):
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
| index | int | Нулевой-базовый индекс, в котором вставить Section Zoom-кадр. |
| x | float | Координата X нового Section Zoom-кадра в пунктах. |
| y | float | Координата Y нового Section Zoom-кадра в пунктах. |
| width | float | Ширина нового Section Zoom-кадра в пунктах. |
| height | float | Высота нового Section Zoom-кадра в пунктах. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection), на который ссылается Section Zoom-кадр; должен принадлежать этой презентации и содержать хотя бы один слайд. |

**Возвращает:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Новосозданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Создаёт новый Section Zoom-кадр с предопределённым изображением и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Section Zoom в указанный индекс коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два раздела):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить Section Zoom-кадр. |
| x | float | Координата X нового Section Zoom-кадра в пунктах. |
| y | float | Координата Y нового Section Zoom-кадра в пунктах. |
| width | float | Ширина нового Section Zoom-кадра в пунктах. |
| height | float | Высота нового Section Zoom-кадра в пунктах. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection), на который ссылается Section Zoom-кадр; должен принадлежать этой презентации и содержать хотя бы один слайд. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение, отображаемое внутри Section Zoom-кадра. |

**Возвращает:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Новосозданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Создаёт новый Summary Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Summary Zoom в конец коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два раздела):
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
| x | float | Координата X нового Summary Zoom-кадра в пунктах. |
| y | float | Координата Y нового Summary Zoom-кадра в пунктах. |
| width | float | Ширина нового Summary Zoom-кадра в пунктах. |
| height | float | Высота нового Summary Zoom-кадра в пунктах. |

--------------------

Этот метод создаёт Summary Zoom-кадр, агрегирующий ссылки-сводки для всех секций в презентации. |

**Возвращает:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Новосозданный [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Создаёт новый Summary Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Summary Zoom в указанный индекс коллекции
>  (предположим, что в презентации "Presentation.pptx" есть как минимум два раздела):
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
| index | int | Нулевой-базовый индекс, в котором вставить Summary Zoom-кадр. |
| x | float | Координата X нового Summary Zoom-кадра в пунктах. |
| y | float | Координата Y нового Summary Zoom-кадра в пунктах. |
| width | float | Ширина нового Summary Zoom-кадра в пунктах. |
| height | float | Высота нового Summary Zoom-кадра в пунктах. |

--------------------

Этот метод создаёт Summary Zoom-кадр, агрегирующий ссылки-сводки для всех секций в презентации. |

**Возвращает:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Новосозданный [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Создаёт новый видеокадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового видеокадра в пунктах. |
| y | float | Координата Y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| fname | java.lang.String | Путь или имя видеофайла для внедрения. |

**Возвращает:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Новосозданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Создаёт новый видеокадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового видеокадра в пунктах. |
| y | float | Координата Y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) для внедрения в видеокадр. |

**Возвращает:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Новосозданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Создаёт новый видеокадр и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить видеокадр. |
| x | float | Координата X нового видеокадра в пунктах. |
| y | float | Координата Y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| fname | java.lang.String | Путь или имя видеофайла для внедрения. |

**Возвращает:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Новосозданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Создаёт новый аудиокадр, связанный с дорожкой CD, и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового аудиокадра в пунктах. |
| y | float | Координата Y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |

**Возвращает:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Новосозданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Создаёт новый аудиокадр, связанный с дорожкой CD, и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить аудиокадр. |
| x | float | Координата X нового аудиокадра в пунктах. |
| y | float | Координата Y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |

**Возвращает:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Новосозданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Создаёт новый аудиокадр, связанный с внешним аудиофайлом, и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового аудиокадра в пунктах. |
| y | float | Координата Y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| fname | java.lang.String | Путь или имя внешнего аудиофайла для ссылки. |

**Возвращает:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Новосозданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Создаёт новый аудиокадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить аудиокадр. |
| x | float | Координата X нового аудиокадра в пунктах. |
| y | float | Координата Y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| fname | java.lang.String | Путь или имя внешнего аудиофайла для ссылки. |

**Возвращает:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Новосозданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Создаёт новый аудиокадр со встроенным WAV-файлом и добавляет его в конец коллекции фигур. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового аудиокадра в пунктах. |
| y | float | Координата Y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio_stream | java.io.InputStream | Поток ввода, содержащий WAV-данные для встраивания. |

**Возвращает:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Новосозданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Создаёт новый аудиокадр и добавляет его в конец коллекции фигур, используя существующий аудио-объект из списка Presentation.Audios.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X нового аудиокадра в пунктах. |
| y | float | Координата Y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Экземпляр [IAudio](../../com.aspose.slides/iaudio) из коллекции Presentation.Audios. |

**Возвращает:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Новосозданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Создаёт новый аудиокадр со встроенным WAV-файлом и вставляет его в коллекцию фигур в указанном индексе. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить аудиокадр. |
| x | float | Координата X нового аудиокадра в пунктах. |
| y | float | Координата Y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio_stream | java.io.InputStream | Поток ввода, содержащий WAV-данные для встраивания. |

**Возвращает:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Новосозданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Создаёт новый аудиокадр и вставляет его в коллекцию фигур в указанном индексе, используя существующий аудио-объект из списка Presentation.Audios.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить аудиокадр. |
| x | float | Координата X нового аудиокадра в пунктах. |
| y | float | Координата Y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Экземпляр [IAudio](../../com.aspose.slides/iaudio) из коллекции Presentation.Audios для встраивания. |

**Возвращает:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Новосозданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Возвращает нулевой-базовый индекс первого вхождения указанной фигуры в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, которую нужно найти в коллекции. |

**Возвращает:**
int – Нулевой-базовый индекс первого вхождения фигуры в коллекцию фигур, если найдена; иначе -1.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Создаёт и возвращает массив, содержащий все фигуры.

**Возвращает:**
com.aspose.slides.IShape[] – Массив объектов [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Создаёт и возвращает массив, содержащий все фигуры в указанном диапазоне.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первой фигуры, которую нужно вернуть. |
| count | int | Количество фигур, которые нужно вернуть. |

**Возвращает:**
com.aspose.slides.IShape[] – Массив объектов [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Перемещает указанную фигуру в новое положение внутри коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый целевой индекс, куда будет помещена фигура. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape), которую нужно переместить внутри коллекции. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с указанного индекса.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый целевой индекс, где будет размещена первая указанная фигура; последующие фигуры следуют в указанном порядке. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Один или несколько экземпляров [IShape](../../com.aspose.slides/ishape) для перемещения внутри коллекции. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Создаёт новую автогенерируемую фигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автогенерируемой фигуры, которую нужно добавить. |
| x | float | Координата X рамки фигуры в пунктах. |
| y | float | Координата Y рамки фигуры в пунктах. |
| width | float | Ширина рамки фигуры в пунктах. |
| height | float | Высота рамки фигуры в пунктах. |

**Возвращает:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую автогенерируемую фигуру и добавляет её в конец коллекции фигур, опционально инициализируя её форматированием шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автогенерируемой фигуры, которую нужно добавить. |
| x | float | Координата X рамки фигуры в пунктах. |
| y | float | Координата Y рамки фигуры в пунктах. |
| width | float | Ширина рамки фигуры в пунктах. |
| height | float | Высота рамки фигуры в пунктах. |
| createFromTemplate | boolean | true – применить стилизация шаблона по умолчанию (простой стиль, центрированный текст и непустое имя) к новой фигуре; false – создать фигуру со всеми свойствами, установленными в их значения по умолчанию. |

**Возвращает:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Создаёт новый прямоугольный автогенерируемый объект для размещения математического контента и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X рамки фигуры в пунктах. |
| y | float | Координата Y рамки фигуры в пунктах. |
| width | float | Ширина рамки фигуры в пунктах. |
| height | float | Высота рамки фигуры в пунктах. |

**Возвращает:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Создаёт новую автогенерируемую фигуру и вставляет её в коллекцию фигур в указанном индексе, применяя форматирование шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить новую автогенерируемую фигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автогенерируемой фигуры, которую нужно вставить. |
| x | float | Координата X рамки фигуры в пунктах. |
| y | float | Координата Y рамки фигуры в пунктах. |
| width | float | Ширина рамки фигуры в пунктах. |
| height | float | Высота рамки фигуры в пунктах. |

**Возвращает:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую автогенерируемую фигуру и вставляет её в коллекцию фигур в указанном индексе, опционально инициализируя её стилизацией шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить автогенерируемую фигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автогенерируемой фигуры, которую нужно вставить. |
| x | float | Координата X рамки фигуры в пунктах. |
| y | float | Координата Y рамки фигуры в пунктах. |
| width | float | Ширина рамки фигуры в пунктах. |
| height | float | Высота рамки фигуры в пунктах. |
| createFromTemplate | boolean | true – применить стилизацию шаблона по умолчанию (включая непустое имя, простой стиль и центрированный текст); false – создать фигуру со всеми свойствами, установленными в их значения по умолчанию. |

**Возвращает:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Создаёт новую пустую группу фигур и добавляет её в конец коллекции фигур. Кадр группы автоматически подгоняется под любые добавляемые в неё фигуры.

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Новосозданный [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Создаёт новую группу фигур, преобразует указанное SVG-изображение в отдельные фигуры и добавляет полученную группу в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage), содержащее векторный контент для преобразования в фигуры. |
| x | float | Координата X кадра группы в пунктах. |
| y | float | Координата Y кадра группы в пунктах. |
| width | float | Ширина кадра группы в пунктах. |
| height | float | Высота кадра группы в пунктах. |

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Новосозданный [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Создаёт новую пустую группу фигур и вставляет её в коллекцию фигур в указанном индексе. Кадр группы автоматически подгоняется под любые добавляемые в неё фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить группу фигур. |

**Возвращает:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Новосозданный [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Создаёт новый соединительный объект с стилизацией шаблона по умолчанию и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительного объекта, который нужно добавить. |
| x | float | Координата X кадра соединителя в пунктах. |
| y | float | Координата Y кадра соединителя в пунктах. |
| width | float | Ширина кадра соединителя в пунктах. |
| height | float | Высота кадра соединителя в пунктах. |

**Возвращает:**
[IConnector](../../com.aspose.slides/iconnector) – Новосозданный [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новый соединительный объект и добавляет его в конец коллекции фигур, опционально применяя стилизацию шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительного объекта, который нужно создать. |
| x | float | Координата X кадра соединителя в пунктах. |
| y | float | Координата Y кадра соединителя в пунктах. |
| width | float | Ширина кадра соединителя в пунктах. |
| height | float | Высота кадра соединителя в пунктах. |
| createFromTemplate | boolean | true – применить стилизацию шаблона по умолчанию (непустое имя, простой стиль); false – создать соединитель со значениями свойств по умолчанию. |

**Возвращает:**
[IConnector](../../com.aspose.slides/iconnector) – Новосозданный [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Создаёт новый соединительный объект и вставляет его в коллекцию фигур в указанном индексе, применяя стилизацию шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить соединительный объект. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительного объекта, который нужно вставить. |
| x | float | Координата X кадра соединителя в пунктах. |
| y | float | Координата Y кадра соединителя в пунктах. |
| width | float | Ширина кадра соединителя в пунктах. |
| height | float | Высота кадра соединителя в пунктах. |

**Возвращает:**
[IConnector](../../com.aspose.slides/iconnector) – Новосозданный [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новый соединительный объект и вставляет его в коллекцию фигур в указанном индексе, опционально применяя стилизацию шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить соединительный объект. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительного объекта, который нужно вставить. |
| x | float | Координата X кадра соединителя в пунктах. |
| y | float | Координата Y кадра соединителя в пунктах. |
| width | float | Ширина кадра соединителя в пунктах. |
| height | float | Высота кадра соединителя в пунктах. |
| createFromTemplate | boolean | true – применить стилизацию шаблона по умолчанию (непустое имя, простой стиль); false – создать соединитель со значениями свойств по умолчанию. |

**Возвращает:**
[IConnector](../../com.aspose.slides/iconnector) – Новосозданный [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Создаёт новый кадр изображения, содержащий указанный файл, и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | Указывает тип фигуры, содержащейся в [ShapeType](../../com.aspose.slides/shapetype), за исключением всех видов линий: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Координата X кадра изображения в пунктах. |
| y | float | Координата Y кадра изображения в пунктах. |
| width | float | Ширина кадра изображения в пунктах. |
| height | float | Высота кадра изображения в пунктах. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage), отображаемый в кадре изображения. |

**Возвращает:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – Новосозданный [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Создаёт новый кадр изображения, содержащий указанный файл, и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить кадр изображения. |
| shapeType | int | Указывает тип фигуры, содержащейся в [ShapeType](../../com.aspose.slides/shapetype), за исключением всех видов линий: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Координата X кадра изображения в пунктах. |
| y | float | Координата Y кадра изображения в пунктах. |
| width | float | Ширина кадра изображения в пунктах. |
| height | float | Высота кадра изображения в пунктах. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage), отображаемый в кадре изображения. |

**Возвращает:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – Новосозданный [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Создаёт новую таблицу и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата X таблицы в пунктах. |
| y | float | Координата Y таблицы в пунктах. |
| columnWidths | double[] | Массив чисел, представляющих ширины столбцов таблицы, в пунктах. |
| rowHeights | double[] | Массив чисел, представляющих высоты строк таблицы, в пунктах. |

**Возвращает:**
[ITable](../../com.aspose.slides/itable) – Новосозданный [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Создаёт новую таблицу и вставляет её в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить таблицу. |
| x | float | Координата X таблицы в пунктах. |
| y | float | Координата Y таблицы в пунктах. |
| columnWidths | double[] | Массив чисел, представляющих ширины столбцов таблицы, в пунктах. |
| rowHeights | double[] | Массив чисел, представляющих высоты строк таблицы, в пунктах. |

**Возвращает:**
[ITable](../../com.aspose.slides/itable) – Новосозданный [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет фигуру в указанном индексе из коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс удаляемой фигуры. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Удаляет первое вхождение указанной фигуры из коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape), которую нужно удалить. |

### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все фигуры из коллекции фигур.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Фигура, которую нужно клонировать. |
| x | float | Координата X кадра клонированной фигуры в пунктах. |
| y | float | Координата Y кадра клонированной фигуры в пунктах. |
| width | float | Ширина кадра клонированной фигуры в пунктах. |
| height | float | Высота кадра клонированной фигуры в пунктах. |

**Возвращает:**
[IShape](../../com.aspose.slides/ishape) – Новосозданный [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. Новая фигура сохраняет ширину и высоту исходной фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape), которую нужно клонировать. |
| x | float | Координата X кадра клонированной фигуры в пунктах. |
| y | float | Координата Y кадра клонированной фигуры в пунктах. |

**Возвращает:**
[IShape](../../com.aspose.slides/ishape) – Новосозданный [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. Клонированная фигура сохраняет исходное положение и размер.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape), которую нужно клонировать. |

**Возвращает:**
[IShape](../../com.aspose.slides/ishape) – Новосозданный [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить клонированную фигуру. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape), которую нужно клонировать. |
| x | float | Координата X кадра клонированной фигуры в пунктах. |
| y | float | Координата Y кадра клонированной фигуры в пунктах. |
| width | float | Ширина кадра клонированной фигуры в пунктах. |
| height | float | Высота кадра клонированной фигуры в пунктах. |

**Возвращает:**
[IShape](../../com.aspose.slides/ishape) – Новосозданный [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанном индексе. Новая фигура сохраняет ширину и высоту исходной фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить клонированную фигуру. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape), которую нужно клонировать. |
| x | float | Координата X кадра клонированной фигуры в пунктах. |
| y | float | Координата Y кадра клонированной фигуры в пунктах. |

**Возвращает:**
[IShape](../../com.aspose.slides/ishape) – Новосозданный [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур в указанном индексе. Клонированная фигура сохраняет исходное положение и размер.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой-базовый индекс, в котором вставить клонированную фигуру. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape), которую нужно клонировать. |

**Возвращает:**
[IShape](../../com.aspose.slides/ishape) – Новосозданный [IShape](../../com.aspose.slides/ishape).