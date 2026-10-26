---
title: IShapeCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет собой коллекцию фигур.
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
| [getParentGroup()](#getParentGroup--) | Получает объект родительской группы фигур для коллекции фигур. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Создаёт новую диаграмму, инициализирует её примерными данными серий и настройками и добавляет в конец коллекции фигур. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Создаёт новую диаграмму, инициализирует её примерными данными серий и настройками и добавляет в конец коллекции фигур. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Создаёт диаграмму SmartArt и добавляет её в конец коллекции фигур. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Создаёт новую диаграмму, инициализирует её примерными данными серий и настройками и вставляет в коллекцию фигур в указанном индексе. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Создаёт новую диаграмму, инициализирует её примерными данными серий и настройками и вставляет в коллекцию фигур в указанном индексе. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Создаёт новый кадр OLE-объекта и добавляет его в конец коллекции фигур. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур в указанном индексе. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Создаёт новый кадр OLE-объекта и вставляет его в коллекцию фигур в указанном индексе. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Создаёт новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Создаёт новый кадр Zoom и добавляет его в конец коллекции фигур. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Создаёт новый кадр Zoom и вставляет его в коллекцию фигур в указанном индексе. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Создаёт новый кадр Zoom с предопределённым изображением и вставляет его в коллекцию фигур в указанном индексе. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Создаёт новый кадр Section Zoom и добавляет его в конец коллекции фигур. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Создаёт новый кадр Section Zoom с предопределённым изображением и добавляет его в конец коллекции фигур. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Создаёт новый кадр Section Zoom и вставляет его в коллекцию фигур в указанном индексе. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Создаёт новый кадр Section Zoom с предопределённым изображением и вставляет его в коллекцию фигур в указанном индексе. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Создаёт новый кадр Summary Zoom и добавляет его в конец коллекции фигур. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Создаёт новый кадр Summary Zoom и вставляет его в коллекцию фигур в указанном индексе. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Создаёт новый видеокадр и добавляет его в конец коллекции фигур. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Создаёт новый видеокадр и вставляет его в коллекцию фигур в указанном индексе. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Создаёт новый аудиокадр, привязанный к дорожке CD, и добавляет его в конец коллекции фигур. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Создаёт новый аудиокадр, привязанный к дорожке CD, и вставляет его в коллекцию фигур в указанном индексе. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Создаёт новый аудиокадр, привязанный к внешнему аудиофайлу, и добавляет его в конец коллекции фигур. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Создаёт новый аудиокадр, привязанный к внешнему аудиофайлу, и вставляет его в коллекцию фигур в указанном индексе. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Создаёт новый аудиокадр с вложенным WAV-файлом и добавляет его в конец коллекции фигур. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Создаёт новый аудиокадр и добавляет его в конец коллекции фигур, используя существующий аудио-объект из списка Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Создаёт новый аудиокадр с вложенным WAV-файлом и вставляет его в коллекцию фигур в указанном индексе. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Создаёт новый аудиокадр и вставляет его в коллекцию фигур в указанном индексе, используя существующий аудио-объект из списка Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Возвращает нулевой индекс первого вхождения указанной фигуры в коллекцию. |
| [toArray()](#toArray--) | Создаёт и возвращает массив, содержащий все фигуры. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив, содержащий все фигуры в указанном диапазоне. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Перемещает указанную фигуру в новое положение внутри коллекции фигур. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Перемещает указанные фигуры внутри коллекции фигур, размещая их, начиная с указанного индекса. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Создаёт новую авто-фигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Создаёт новую авто-фигуру и добавляет её в конец коллекции фигур, при желании инициализируя её форматированием шаблона по умолчанию. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Создаёт новую прямоугольную авто-фигуру для размещения математического содержимого и добавляет её в конец коллекции фигур. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Создаёт новую авто-фигуру и вставляет её в коллекцию фигур в указанном индексе, применяя форматирование шаблона по умолчанию. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Создаёт новую авто-фигуру и вставляет её в коллекцию фигур в указанном индексе, при желании инициализируя её стилизацию шаблона по умолчанию. |
| [addGroupShape()](#addGroupShape--) | Создаёт новую пустую групповую фигуру и добавляет её в конец коллекции фигур. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Создаёт новую групповую фигуру, преобразует указанное SVG-изображение в отдельные фигуры и добавляет полученную группу в конец коллекции фигур. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Создаёт новую пустую групповую фигуру и вставляет её в коллекцию фигур в указанном индексе. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Создаёт новую соединительную фигуру с стилизацией шаблона по умолчанию и добавляет её в конец коллекции фигур. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Создаёт новую соединительную фигуру и добавляет её в конец коллекции фигур, при желании применяя стилизацию шаблона по умолчанию. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур в указанном индексе, применяя стилизацию шаблона по умолчанию. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур в указанном индексе, при желании применяя стилизацию шаблона по умолчанию. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Создаёт новый рамочный объект изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Создаёт новый рамочный объект изображения, содержащий указанное изображение, и вставляет его в коллекцию фигур в указанном индексе. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Создаёт новую таблицу и добавляет её в конец коллекции фигур. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Создаёт новую таблицу и вставляет её в коллекцию фигур в указанном индексе. |
| [removeAt(int index)](#removeAt-int-) | Удаляет фигуру по указанному индексу из коллекции фигур. |
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

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Получает объект родительской группы фигур для коллекции фигур. Только для чтения [IGroupShape](../../com.aspose.slides/igroupshape).

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Создаёт новую диаграмму, инициализирует её примерными данными серий и настройками и добавляет в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип добавляемой диаграммы. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина диаграммы в пунктах. |
| height | float | Высота диаграммы в пунктах. |

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart) - Новосозданный [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Создаёт новую диаграмму, инициализирует её примерными данными серий и настройками и добавляет в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип добавляемой диаграммы. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина диаграммы в пунктах. |
| height | float | Высота диаграммы в пунктах. |
| initWithSample | boolean | True, чтобы инициализировать новую диаграмму примерными данными серий и настройками; false, чтобы создать диаграмму без серий и лишь с минимальными настройками, что ускоряет создание. |

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart) - Новосозданный [IChart](../../com.aspose.slides/ichart).

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
| x | float | Координата x кадра диаграммы в пунктах. |
| y | float | Координата y кадра диаграммы в пунктах. |
| width | float | Ширина кадра диаграммы в пунктах. |
| height | float | Высота кадра диаграммы в пунктах. |
| layoutType | int | Тип макета SmartArt. |

**Возвращаемое значение:**
[ISmartArt](../../com.aspose.slides/ismartart) - Новосозданный [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Создаёт новую диаграмму, инициализирует её примерными данными серий и настройками и вставляет её в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип создаваемой диаграммы. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина новой диаграммы в пунктах. |
| height | float | Высота новой диаграммы в пунктах. |
| index | int | Нулевой индекс, по которому вставлять новую диаграмму в коллекцию фигур. |

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart) - Новосозданный [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Создаёт новую диаграмму, инициализирует её примерными данными серий и настройками и вставляет её в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип создаваемой диаграммы. |
| x | float | Координата x новой диаграммы в пунктах. |
| y | float | Координата y новой диаграммы в пунктах. |
| width | float | Ширина новой диаграммы в пунктах. |
| height | float | Высота новой диаграммы в пунктах. |
| index | int | Нулевой индекс, по которому вставлять новую диаграмму в коллекцию фигур. |
| initWithSample | boolean | True, чтобы инициализировать новую диаграмму примерными данными серий и настройками; false, чтобы создать диаграмму без серий и лишь с минимальными настройками, что ускоряет создание. |
| initWithSample | boolean | True — инициализировать новую диаграмму с образцовыми данными серии и настройками; false — создать диаграмму без серий и только с минимальными настройками, что ускоряет создание. |

**Возвращаемое значение:**
[IChart](../../com.aspose.slides/ichart) - The newly created [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Создает новый OLE-объектный кадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового OLE-кадра в пунктах. |
| y | float | Координата y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Встроенная информация OLE-данных ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Возвращаемое значение:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Недавно созданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Создает новый OLE-объектный кадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового OLE-кадра в пунктах. |
| y | float | Координата y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| className | java.lang.String | Имя класса OLE-объекта. |
| path | java.lang.String | Путь к связанному файлу. Этот путь сохраняется в презентации без изменений. Если указан относительный путь, файл будет недоступен при открытии презентации из другого каталога. |

**Возвращаемое значение:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Недавно созданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Создает новый OLE-объектный кадр и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить OLE-кадр. |
| x | float | Координата x нового OLE-кадра в пунктах. |
| y | float | Координата y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Встроенная информация OLE-данных ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Возвращаемое значение:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Недавно созданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Создает новый OLE-объектный кадр и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, в котором следует вставить OLE-кадр. |
| x | float | Координата x нового OLE-кадра в пунктах. |
| y | float | Координата y нового OLE-кадра в пунктах. |
| width | float | Ширина нового OLE-кадра в пунктах. |
| height | float | Высота нового OLE-кадра в пунктах. |
| className | java.lang.String | Имя класса OLE-объекта. |
| path | java.lang.String | Путь к связанному файлу. Этот путь сохраняется в презентации без изменений. Если указан относительный путь, файл будет недоступен при открытии презентации из другого каталога. |

**Возвращаемое значение:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Недавно созданный [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
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
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Создает новый Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
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
| x | float | Координата x нового Zoom-кадра в пунктах. |
| y | float | Координата y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | Объект [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр; должен принадлежать этой презентации. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение для ссылки на слайд [IPPImage](../../com.aspose.slides/ippimage). |

**Возвращаемое значение:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Недавно созданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Создает новый Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Zoom в указанную позицию коллекции
>  (предполагается, что в презентации "Presentation.pptx" присутствует как минимум два слайда):
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
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Создает новый Zoom-кадр с предварительно заданным изображением и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Zoom в указанную позицию коллекции
>  (предполагается, что в презентации "Presentation.pptx" присутствует как минимум два слайда):
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
| index | int | Нулевой индекс, в котором следует вставить Zoom-кадр. |
| x | float | Координата x нового Zoom-кадра в пунктах. |
| y | float | Координата y нового Zoom-кадра в пунктах. |
| width | float | Ширина нового Zoom-кадра в пунктах. |
| height | float | Высота нового Zoom-кадра в пунктах. |
| slide | [ISlide](../../com.aspose.slides/islide) | Объект [ISlide](../../com.aspose.slides/islide), на который ссылается Zoom-кадр. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Изображение для ссылки на слайд [IPPImage](../../com.aspose.slides/ippimage). |

**Возвращаемое значение:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Недавно созданный [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Создает новый Section Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Section Zoom в конец коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум две секции):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  ```


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
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Создает новый Section Zoom-кадр с предварительно заданным изображением и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Section Zoom в конец коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум две секции):
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
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) для отображения внутри Section Zoom-кадра. |

**Возвращаемое значение:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Недавно созданный [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Создает новый Section Zoom-кадр и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Section Zoom в указанную позицию коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум две секции):
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
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Создает новый Section Zoom-кадр с предварительно заданным изображением и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Section Zoom в указанную позицию коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум две секции):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
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
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Создает новый Summary Zoom-кадр и добавляет его в конец коллекции фигур.

--------------------

> ```
> Этот пример демонстрирует добавление объекта Summary Zoom в конец коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум две секции):
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
Этот метод создает кадр Summary Zoom, который агрегирует ссылки-резюме для всех разделов презентации. |

**Возврат:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - - Новый созданный [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Создает новый кадр Summary Zoom и вставляет его в коллекцию фигур в указанном индексе.

--------------------

> ```
> Этот пример демонстрирует создание и вставку объекта Summary Zoom в указанную позицию коллекции
>  (предполагается, что в презентации "Presentation.pptx" есть как минимум две секции):
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
| index | int | Нулевой индекс, по которому вставляется кадр Summary Zoom. |
| x | float | Координата x нового кадра Summary Zoom в пунктах. |
| y | float | Координата y нового кадра Summary Zoom в пунктах. |
| width | float | Ширина нового кадра Summary Zoom в пунктах. |
| height | float | Высота нового кадра Summary Zoom в пунктах. |

--------------------

Этот метод создает кадр Summary Zoom, который агрегирует ссылки-резюме для всех разделов презентации. |

**Возврат:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - - Новый созданный [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Создает новый видеокадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового видеокадра в пунктах. |
| y | float | Координата y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| fname | java.lang.String | Путь или имя видеофайла для встраивания. |

**Возврат:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - - Новый созданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Создает новый видеокадр и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового видеокадра в пунктах. |
| y | float | Координата y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Объект [IVideo](../../com.aspose.slides/ivideo) для встраивания в видеокадр. |

**Возврат:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - - Новый созданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Создает новый видеокадр и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому вставляется видеокадр. |
| x | float | Координата x нового видеокадра в пунктах. |
| y | float | Координата y нового видеокадра в пунктах. |
| width | float | Ширина нового видеокадра в пунктах. |
| height | float | Высота нового видеокадра в пунктах. |
| fname | java.lang.String | Путь или имя видеофайла для встраивания. |

**Возврат:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - - Новый созданный [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Создает новый аудиокадр, связанный с дорожкой CD, и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |

**Возврат:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - - Новый созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Создает новый аудиокадр, связанный с дорожкой CD, и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому вставляется аудиокадр. |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |

**Возврат:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - - Новый созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Создает новый аудиокадр, связанный с внешним аудиофайлом, и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| fname | java.lang.String | Путь или имя внешнего аудиофайла для ссылки. |

**Возврат:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - - Новый созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Создает новый аудиокадр, связанный с внешним аудиофайлом, и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому вставляется аудиокадр. |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| fname | java.lang.String | Путь или имя внешнего аудиофайла для ссылки. |

**Возврат:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - - Новый созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Создает новый аудиокадр с встроенным WAV-файлом и добавляет его в конец коллекции фигур. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio_stream | java.io.InputStream | Поток ввода, содержащий данные WAV-аудио для встраивания. |

**Возврат:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - - Новый созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Создает новый аудиокадр и добавляет его в конец коллекции фигур, используя существующий аудио-объект из списка Presentation.Audios.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Экземпляр [IAudio](../../com.aspose.slides/iaudio) из коллекции Presentation.Audios. |

**Возврат:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - - Новый созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Создает новый аудиокадр с встроенным WAV-файлом и вставляет его в коллекцию фигур в указанном индексе. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому вставляется аудиокадр. |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio_stream | java.io.InputStream | Поток ввода, содержащий данные WAV-аудио для встраивания. |

**Возврат:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - - Новый созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Создает новый аудиокадр и вставляет его в коллекцию фигур в указанном индексе, используя существующий аудио-объект из списка Presentation.Audios.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому вставляется аудиокадр. |
| x | float | Координата x нового аудиокадра в пунктах. |
| y | float | Координата y нового аудиокадра в пунктах. |
| width | float | Ширина нового аудиокадра в пунктах. |
| height | float | Высота нового аудиокадра в пунктах. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Экземпляр [IAudio](../../com.aspose.slides/iaudio) из коллекции Presentation.Audios для встраивания. |

**Возврат:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - - Новый созданный [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Возвращает нулевой индекс первого вхождения указанной фигуры в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, которую нужно найти в коллекции. |

**Возврат:**
int - Нулевой индекс первого вхождения фигуры в коллекцию фигур, если найдено; иначе \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Создает и возвращает массив, содержащий все фигуры.

**Возврат:**
com.aspose.slides.IShape[] - Массив объектов [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Создает и возвращает массив, содержащий все фигуры в указанном диапазоне.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первой фигуры, которую нужно вернуть. |
| count | int | Количество фигур, которое нужно вернуть. |

**Возврат:**
com.aspose.slides.IShape[] - Массив объектов [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Перемещает указанную фигуру в новое положение внутри коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой целевой индекс, куда будет помещена фигура. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) для перемещения внутри коллекции. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Перемещает указанные фигуры внутри коллекции, размещая их, начиная с заданного индекса.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой целевой индекс, куда будет помещена первая указанная фигура; последующие фигуры следуют в указанном порядке. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Один или более экземпляров [IShape](../../com.aspose.slides/ishape) для перемещения внутри коллекции. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Создает новую автофигуру с форматированием по умолчанию и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автофигуры для добавления. |

| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую автофигуру и добавляет её в конец коллекции фигур, при необходимости инициализируя её форматированием из шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автофигуры, которую следует добавить. |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |
| createFromTemplate | boolean | True — применить стиль шаблона по умолчанию (простой стиль, центрированный текст и непустое имя) к новой фигуре; false — создать фигуру со всеми свойствами, установленными в их значения по умолчанию. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Создаёт новую прямоугольную автофигуру для размещения математического контента и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Создаёт новую автофигуру и вставляет её в коллекцию фигур в указанном индексе, применяя форматирование шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевая позиция, в которую следует вставить новую автофигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автофигуры, которую следует вставить. |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую автофигуру и вставляет её в коллекцию фигур в указанном индексе, при необходимости инициализируя её стилем шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевая позиция, в которую следует вставить автофигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) автофигуры, которую следует вставить. |
| x | float | Координата x рамки фигуры, в пунктах. |
| y | float | Координата y рамки фигуры, в пунктах. |
| width | float | Ширина рамки фигуры, в пунктах. |
| height | float | Высота рамки фигуры, в пунктах. |
| createFromTemplate | boolean | True — применить стиль шаблона по умолчанию (включая непустое имя, простой стиль и центрированный текст); false — создать фигуру со всеми свойствами, установленными в их значения по умолчанию. |

**Возвращаемое значение:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Новосозданный [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Создаёт новую пустую группу фигур и добавляет её в конец коллекции фигур. Кадр группы автоматически подгоняется под любые добавляемые в неё фигуры.

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Новосозданный [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Создаёт новую группу фигур, преобразует указанное SVG-изображение в отдельные фигуры и добавляет полученную группу в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Объект [ISvgImage](../../com.aspose.slides/isvgimage), содержащий векторный контент для преобразования в фигуры. |
| x | float | Координата x кадра группы, в пунктах. |
| y | float | Координата y кадра группы, в пунктах. |
| width | float | Ширина кадра группы, в пунктах. |
| height | float | Высота кадра группы, в пунктах. |

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Новосозданный [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Создаёт новую пустую группу фигур и вставляет её в коллекцию фигур в указанном индексе. Кадр группы автоматически подгоняется под любые добавляемые в неё фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевая позиция, в которую следует вставить группу фигур. |

**Возвращаемое значение:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Новосозданный [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Создаёт новую соединительную фигуру с оформлением шаблона по умолчанию и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительной фигуры, которую следует добавить. |
| x | float | Координата x кадра соединителя, в пунктах. |
| y | float | Координата y кадра соединителя, в пунктах. |
| width | float | Ширина кадра соединителя, в пунктах. |
| height | float | Высота кадра соединителя, в пунктах. |

**Возвращаемое значение:**
[IConnector](../../com.aspose.slides/iconnector) - Новосозданный [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую соединительную фигуру и добавляет её в конец коллекции фигур, при необходимости применяя стиль шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительной фигуры, которую следует создать. |
| x | float | Координата x кадра соединителя, в пунктах. |
| y | float | Координата y кадра соединителя, в пунктах. |
| width | float | Ширина кадра соединителя, в пунктах. |
| height | float | Высота кадра соединителя, в пунктах. |
| createFromTemplate | boolean | True — применить стиль шаблона по умолчанию (непустое имя, простой стиль); false — создать соединитель со значениями свойств по умолчанию. |

**Возвращаемое значение:**
[IConnector](../../com.aspose.slides/iconnector) - Новосозданный [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур в указанном индексе, применяя стиль шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевая позиция, в которую следует вставить соединительную фигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительной фигуры, которую следует вставить. |
| x | float | Координата x кадра соединителя, в пунктах. |
| y | float | Координата y кадра соединителя, в пунктах. |
| width | float | Ширина кадра соединителя, в пунктах. |
| height | float | Высота кадра соединителя, в пунктах. |

**Возвращаемое значение:**
[IConnector](../../com.aspose.slides/iconnector) - Новосозданный [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Создаёт новую соединительную фигуру и вставляет её в коллекцию фигур в указанном индексе, при необходимости применяя стиль шаблона по умолчанию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевая позиция, в которую следует вставить соединительную фигуру. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) соединительной фигуры, которую следует вставить. |
| x | float | Координата x кадра соединителя, в пунктах. |
| y | float | Координата y кадра соединителя, в пунктах. |
| width | float | Ширина кадра соединителя, в пунктах. |
| height | float | Высота кадра соединителя, в пунктах. |
| createFromTemplate | boolean | True — применить стиль шаблона по умолчанию (непустое имя, простой стиль); false — создать соединитель со значениями свойств по умолчанию. |

**Возвращаемое значение:**
[IConnector](../../com.aspose.slides/iconnector) - Новосозданный [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Создаёт новый кадр изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | int | Указывает тип фигуры, содержащейся в [ShapeType](../../com.aspose.slides/shapetype), за исключением всех видов линий:\n\nShapeType.Line,\n\nShapeType.StraightConnector1,\n\nShapeType.BentConnector2,\n\nShapeType.BentConnector3,\n\nShapeType.BentConnector4,\n\nShapeType.BentConnector5,\n\nShapeType.CurvedConnector2,\n\nShapeType.CurvedConnector3,\n\nShapeType.CurvedConnector4,\n\nShapeType.CurvedConnector5. |
| x | float | Координата x кадра изображения, в пунктах. |
| y | float | Координата y кадра изображения, в пунктах. |
| width | float | Ширина кадра изображения, в пунктах. |
| height | float | Высота кадра изображения, в пунктах. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Объект [IPPImage](../../com.aspose.slides/ippimage), отображаемый в кадре изображения. |

**Возвращаемое значение:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Новосозданный [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Создаёт новый кадр изображения, содержащий указанное изображение, и вставляет его в коллекцию фигур в указанном индексе.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевая позиция, в которую следует вставить кадр изображения. |
| shapeType | int | Указывает тип фигуры, содержащейся в [ShapeType](../../com.aspose.slides/shapetype), за исключением всех видов линий:\n\nShapeType.Line,\n\nShapeType.StraightConnector1,\n\nShapeType.BentConnector2,\n\nShapeType.BentConnector3,\n\nShapeType.BentConnector4,\n\nShapeType.BentConnector5,\n\nShapeType.CurvedConnector2,\n\nShapeType.CurvedConnector3,\n\nShapeType.CurvedConnector4,\n\nShapeType.CurvedConnector5. |
| x | float | Координата x кадра изображения, в пунктах. |
| y | float | Координата y кадра изображения, в пунктах. |
| width | float | Ширина кадра изображения, в пунктах. |
| height | float | Высота кадра изображения, в пунктах. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Объект [IPPImage](../../com.aspose.slides/ippimage), отображаемый в кадре изображения. |

**Возвращаемое значение:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Новосозданный [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Создаёт новую таблицу и добавляет её в конец коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x таблицы, в пунктах. |
| y | float | Координата y таблицы, в пунктах. |
| columnWidths | double[] | Массив значений double, представляющих ширины колонок таблицы, в пунктах. |
| rowHeights | double[] | Массив значений double, представляющих высоты строк таблицы, в пунктах. |

**Возвращаемое значение:**
[ITable](../../com.aspose.slides/itable) - Новосозданный [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Создаёт новую таблицу и вставляет её в коллекцию фигур по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлена таблица. |
| x | float | Координата x таблицы, в пунктах. |
| y | float | Координата y таблицы, в пунктах. |
| columnWidths | double[] | Массив double, представляющий ширины столбцов таблицы, в пунктах. |
| rowHeights | double[] | Массив double, представляющий высоты строк таблицы, в пунктах. |

**Возврат:**
[ITable](../../com.aspose.slides/itable) - Недавно созданный [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет фигуру по указанному индексу из коллекции фигур.

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Удаляет первое вхождение указанной фигуры из коллекции фигур.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Объект [IShape](../../com.aspose.slides/ishape), который нужно удалить. |

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
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Фигура для клонирования. |
| x | float | Координата x рамки клонированной фигуры, в пунктах. |
| y | float | Координата y рамки клонированной фигуры, в пунктах. |
| width | float | Ширина рамки клонированной фигуры, в пунктах. |
| height | float | Высота рамки клонированной фигуры, в пунктах. |

**Возврат:**
[IShape](../../com.aspose.slides/ishape) - Недавно созданный [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. Новая фигура сохраняет ширину и высоту исходной фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Объект [IShape](../../com.aspose.slides/ishape) для клонирования. |
| x | float | Координата x рамки клонированной фигуры, в пунктах. |
| y | float | Координата y рамки клонированной фигуры, в пунктах. |

**Возврат:**
[IShape](../../com.aspose.slides/ishape) - Недавно созданный [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Создаёт копию указанной фигуры и добавляет её в конец коллекции фигур. Клонированная фигура сохраняет позицию и размер оригинала.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Объект [IShape](../../com.aspose.slides/ishape) для клонирования. |

**Возврат:**
[IShape](../../com.aspose.slides/ishape) - Недавно созданный [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлена клонированная фигура. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Объект [IShape](../../com.aspose.slides/ishape) для клонирования. |
| x | float | Координата x рамки клонированной фигуры, в пунктах. |
| y | float | Координата y рамки клонированной фигуры, в пунктах. |
| width | float | Ширина рамки клонированной фигуры, в пунктах. |
| height | float | Высота рамки клонированной фигуры, в пунктах. |

**Возврат:**
[IShape](../../com.aspose.slides/ishape) - Недавно созданный [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. Новая фигура сохраняет ширину и высоту исходной фигуры.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлена клонированная фигура. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Объект [IShape](../../com.aspose.slides/ishape) для клонирования. |
| x | float | Координата x рамки клонированной фигуры, в пунктах. |
| y | float | Координата y рамки клонированной фигуры, в пунктах. |

**Возврат:**
[IShape](../../com.aspose.slides/ishape) - Недавно созданный [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Создаёт копию указанной фигуры и вставляет её в коллекцию фигур по указанному индексу. Клонированная фигура сохраняет позицию и размер оригинала.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс, по которому будет вставлена клонированная фигура. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Объект [IShape](../../com.aspose.slides/ishape) для клонирования. |

**Возврат:**
[IShape](../../com.aspose.slides/ishape) - Недавно созданный [IShape](../../com.aspose.slides/ishape).