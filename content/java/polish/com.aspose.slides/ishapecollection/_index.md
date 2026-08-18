---
title: IShapeCollection
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje kolekcję kształtów.
type: docs
url: /pl/com.aspose.slides/ishapecollection/
---
**Wszystkie implementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Reprezentuje kolekcję kształtów.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getParentGroup()](#getParentGroup--) | Gets the parent group shape object for the shapes collection. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Creates a new chart, initializes it with sample series data and settings, and adds it to the end of the shape collection. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Creates a SmartArt diagram and adds it to the end of the shape collection. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Creates a new chart, initializes it with sample series data and settings, and inserts it into the shape collection at the specified index. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Creates a new OLE object frame and adds it to the end of the shape collection. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Creates a new OLE object frame and inserts it into the shape collection at the specified index. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Creates a new Zoom frame and adds it to the end of the shape collection. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Creates a new Zoom frame and inserts it into the shape collection at the specified index. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Creates a new Zoom frame with a predefined image and inserts it into the shape collection at the specified index. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Creates a new Section Zoom frame and adds it to the end of the shape collection. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Creates a new Section Zoom frame with a predefined image and adds it to the end of the shape collection. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Creates a new Section Zoom frame and inserts it into to the shape collection at the specified index. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Creates a new Section Zoom frame with a predefined image and inserts it into to the shape collection at the specified index. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Creates a new Summary Zoom frame and adds it to the end of the shape collection. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Creates a new Summary Zoom frame and inserts it into the shape collection at the specified index. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Creates a new video frame and adds it to the end of the shape collection. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Creates a new video frame and adds it to the end of the shape collection. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Creates a new video frame and inserts it into the shape collection at the specified index. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Creates a new audio frame linked to a CD track and adds it to the end of the shape collection. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Creates a new audio frame linked to a CD track and inserts it into the shape collection at the specified index. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Creates a new audio frame linked to an external audio file and adds it to the end of the shape collection. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Creates a new audio frame linked to an external audio file and inserts it into the shape collection at the specified index. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Creates a new audio frame with an embedded WAV file and adds it to the end of the shape collection. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Creates a new audio frame and adds it to the end of the shape collection using an existing audio object from the Presentation.Audios list. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Creates a new audio frame with an embedded WAV file and inserts it into the shape collection at the specified index. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Creates a new audio frame and inserts it into the shape collection at the specified index using an existing audio object from the Presentation.Audios list. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Returns the zero-based index of the first occurrence of the specified shape in the collection. |
| [toArray()](#toArray--) | Creates and returns an array that contains all shapes. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Creates and returns an array that contains all shapes in the specified range. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Moves the specified shape to a new position within the shape collection. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Moves the specified shapes within the shape collection, placing them starting at the given index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Creates a new auto shape with default formatting and adds it to the end of the shape collection. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Creates a new auto shape and adds it to the end of the shape collection, optionally initializing it with default template formatting. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Creates a new rectangle auto shape to host mathematical content and adds it to the end of the shape collection. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Creates a new auto shape and inserts it into the shape collection at the specified index, applying default template formatting. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Creates a new auto shape and inserts it into the shape collection at the specified index, optionally initializing it with default template styling. |
| [addGroupShape()](#addGroupShape--) | Creates a new empty group shape and adds it to the end of the shape collection. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Creates a new group shape, converts the specified SVG image into individual shapes, and adds the resulting group to the end of the shape collection. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Creates a new empty group shape and inserts it to the shape collection at the specified index. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Creates a new connector shape with default template styling and adds it to the end of the shape collection. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Creates a new connector shape and adds it to the end of the shape collection, optionally applying default template styling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Creates a new connector shape and inserts it into the shape collection at the specified index, applying default template styling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Creates a new connector shape and inserts it into the shape collection at the specified index, optionally applying default template styling. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Creates a new picture frame containing the specified image and adds it to the end of the shape collection. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Creates a new picture frame containing the specified image and inserts it into the shape collection at the specified index. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Creates a new table and adds it to the end of the shape collection. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Creates a new table and inserts it into the shape collection at the specified index. |
| [removeAt(int index)](#removeAt-int-) | Removes the shape at the specified index from the shape collection. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Removes the first occurrence of the specified shape from the shape collection. |
| [clear()](#clear--) | Removes all shapes from the shape collection. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Creates a copy of the specified shape and adds it to the end of the shape collection. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Creates a copy of the specified shape and inserts it into the shape collection at the specified index. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Pobiera element o określonym indeksie. Tylko do odczytu [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Pobiera obiekt kształtu grupy nadrzędnej dla kolekcji kształtów. Tylko do odczytu [IGroupShape](../../com.aspose.slides/igroupshape).

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, a następnie dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do dodania. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość wykresu, w punktach. |
| height | float | Wysokość wykresu, w punktach. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, a następnie dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do dodania. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość wykresu, w punktach. |
| height | float | Wysokość wykresu, w punktach. |
| initWithSample | boolean | true, aby zainicjalizować nowy wykres przykładowymi danymi serii i ustawieniami; false, aby utworzyć wykres bez serii i tylko z minimalnymi ustawieniami, co przyspiesza tworzenie. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x ramki diagramu, w punktach. |
| y | float | Współrzędna y ramki diagramu, w punktach. |
| width | float | Szerokość ramki diagramu, w punktach. |
| height | float | Wysokość ramki diagramu, w punktach. |
| layoutType | int | Typ układu SmartArt. |

**Zwraca:**
[ISmartArt](../../com.aspose.slides/ismartart) - Nowo utworzony [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, a następnie wstawia go do kolekcji kształtów w określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do utworzenia. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość nowego wykresu, w punktach. |
| height | float | Wysokość nowego wykresu, w punktach. |
| index | int | Indeks (liczony od zera), w którym wstawić nowy wykres w kolekcji kształtów. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami, a następnie wstawia go do kolekcji kształtów w określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do utworzenia. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość nowego wykresu, w punktach. |
| height | float | Wysokość nowego wykresu, w punktach. |
| index | int | Indeks (liczony od zera), w którym wstawić nowy wykres w kolekcji kształtów. |
| initWithSample | boolean | true, aby zainicjalizować nowy wykres przykładowymi danymi serii i ustawieniami; false, aby utworzyć wykres bez serii i tylko z minimalnymi ustawieniami, co przyspiesza tworzenie. |

| initWithSample | boolean | True, aby zainicjować nowy wykres danymi i ustawieniami przykładowych serii; false, aby utworzyć wykres bez serii i tylko z minimalnymi ustawieniami, co przyspiesza tworzenie. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tworzy nową ramkę obiektu OLE i dodaje ją na końcu kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki OLE, w punktach. |
| y | float | Współrzędna y nowej ramki OLE, w punktach. |
| width | float | Szerokość nowej ramki OLE, w punktach. |
| height | float | Wysokość nowej ramki OLE, w punktach. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informacje o osadzonych danych OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Tworzy nową ramkę obiektu OLE i dodaje ją na końcu kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki OLE, w punktach. |
| y | float | Współrzędna y nowej ramki OLE, w punktach. |
| width | float | Szerokość nowej ramki OLE, w punktach. |
| height | float | Wysokość nowej ramki OLE, w punktach. |
| className | java.lang.String | Nazwa klasy obiektu OLE. |
| path | java.lang.String | Ścieżka do powiązanego pliku.

Ta ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano ścieżkę względną, plik będzie niedostępny przy otwieraniu prezentacji z innego katalogu. |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawić ramkę obiektu OLE. |
| x | float | Współrzędna x nowej ramki OLE, w punktach. |
| y | float | Współrzędna y nowej ramki OLE, w punktach. |
| width | float | Szerokość nowej ramki OLE, w punktach. |
| height | float | Wysokość nowej ramki OLE, w punktach. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informacje o osadzonych danych OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawić ramkę obiektu OLE. |
| x | float | Współrzędna x nowej ramki OLE, w punktach. |
| y | float | Współrzędna y nowej ramki OLE, w punktach. |
| width | float | Szerokość nowej ramki OLE, w punktach. |
| height | float | Wysokość nowej ramki OLE, w punktach. |
| className | java.lang.String | Nazwa klasy obiektu OLE. |
| path | java.lang.String | Ścieżka do powiązanego pliku.

Ta ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano ścieżkę względną, plik będzie niedostępny przy otwieraniu prezentacji z innego katalogu. |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Tworzy nową ramkę Zoom i dodaje ją na końcu kolekcji kształtów.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki Zoom, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom, w punktach. |
| width | float | Szerokość nowej ramki Zoom, w punktach. |
| height | float | Wysokość nowej ramki Zoom, w punktach. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwoływany przez ramkę Zoom; musi należeć do tej prezentacji. |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tworzy nową ramkę Zoom i dodaje ją na końcu kolekcji kształtów.

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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki Zoom, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom, w punktach. |
| width | float | Szerokość nowej ramki Zoom, w punktach. |
| height | float | Wysokość nowej ramki Zoom, w punktach. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwoływany przez ramkę Zoom; musi należeć do tej prezentacji. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obraz dla odwoływanego slajdu [IPPImage](../../com.aspose.slides/ippimage). |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów w podanym indeksie.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawić ramkę Zoom. |
| x | float | Współrzędna x nowej ramki Zoom, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom, w punktach. |
| width | float | Szerokość nowej ramki Zoom, w punktach. |
| height | float | Wysokość nowej ramki Zoom, w punktach. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwoływany przez ramkę Zoom. |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w podanym indeksie.

--------------------

> ```
> Ten przykład demonstruje tworzenie i wstawianie obiektu Zoom pod określonym indeksem w kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwa slajdy):
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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawić ramkę Zoom. |
| x | float | Współrzędna x nowej ramki Zoom, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom, w punktach. |
| width | float | Szerokość nowej ramki Zoom, w punktach. |
| height | float | Wysokość nowej ramki Zoom, w punktach. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwoływany przez ramkę Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obraz dla odwoływanego slajdu [IPPImage](../../com.aspose.slides/ippimage). |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Tworzy nową ramkę Zoom sekcji i dodaje ją na końcu kolekcji kształtów.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki Zoom sekcji, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom sekcji, w punktach. |
| width | float | Szerokość nowej ramki Zoom sekcji, w punktach. |
| height | float | Wysokość nowej ramki Zoom sekcji, w punktach. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwoływany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i dodaje ją na końcu kolekcji kształtów.

--------------------

> ```
> Ten przykład demonstruje dodawanie obiektu Section Zoom na końcu kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje):
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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki Zoom sekcji, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom sekcji, w punktach. |
| width | float | Szerokość nowej ramki Zoom sekcji, w punktach. |
| height | float | Wysokość nowej ramki Zoom sekcji, w punktach. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwoływany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) wyświetlany wewnątrz ramki Zoom sekcji. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Tworzy nową ramkę Zoom sekcji i wstawia ją do kolekcji kształtów w podanym indeksie.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawić ramkę Zoom sekcji. |
| x | float | Współrzędna x nowej ramki Zoom sekcji, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom sekcji, w punktach. |
| width | float | Szerokość nowej ramki Zoom sekcji, w punktach. |
| height | float | Wysokość nowej ramki Zoom sekcji, w punktach. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwoływany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w podanym indeksie.

--------------------

> ```
> Ten przykład demonstruje tworzenie i wstawianie obiektu Section Zoom pod określonym indeksem w kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje):
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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawić ramkę Zoom sekcji. |
| x | float | Współrzędna x nowej ramki Zoom sekcji, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom sekcji, w punktach. |
| width | float | Szerokość nowej ramki Zoom sekcji, w punktach. |
| height | float | Wysokość nowej ramki Zoom sekcji, w punktach. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwoływany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obraz wyświetlany wewnątrz ramki Zoom sekcji. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Tworzy nową ramkę Zoom podsumowania i dodaje ją na końcu kolekcji kształtów.

--------------------

> ```
> This example demonstrates adding a Summary Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki Zoom podsumowania, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom podsumowania, w punktach. |
| width | float | Szerokość nowej ramki Zoom podsumowania, w punktach. |
| height | float | Wysokość nowej ramki Zoom podsumowania, w punktach. |
Ta metoda tworzy ramkę podsumowania Zoom, która agreguje odnośniki podsumowujące dla wszystkich sekcji w prezentacji. |

**Zwraca:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nowo utworzony [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Tworzy nową ramkę podsumowania Zoom i wstawia ją do kolekcji kształtów w określonym indeksie.

--------------------

> ```
> Ten przykład demonstruje tworzenie i wstawianie obiektu Summary Zoom pod określonym indeksem w kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks, w którym należy wstawić ramkę podsumowania Zoom. |
| x | float | Współrzędna x nowej ramki podsumowania Zoom, w punktach. |
| y | float | Współrzędna y nowej ramki podsumowania Zoom, w punktach. |
| width | float | Szerokość nowej ramki podsumowania Zoom, w punktach. |
| height | float | Wysokość nowej ramki podsumowania Zoom, w punktach. |

--------------------

Ta metoda tworzy ramkę podsumowania Zoom, która agreguje odnośniki podsumowujące dla wszystkich sekcji w prezentacji. |

**Zwraca:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nowo utworzony [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki wideo, w punktach. |
| y | float | Współrzędna y nowej ramki wideo, w punktach. |
| width | float | Szerokość nowej ramki wideo, w punktach. |
| height | float | Wysokość nowej ramki wideo, w punktach. |
| fname | java.lang.String | Ścieżka lub nazwa pliku wideo do osadzenia. |

**Zwraca:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nowo utworzony [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki wideo, w punktach. |
| y | float | Współrzędna y nowej ramki wideo, w punktach. |
| width | float | Szerokość nowej ramki wideo, w punktach. |
| height | float | Wysokość nowej ramki wideo, w punktach. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Obiekt [IVideo](../../com.aspose.slides/ivideo) do osadzenia w ramce wideo. |

**Zwraca:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nowo utworzony [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów w określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks, w którym należy wstawić ramkę wideo. |
| x | float | Współrzędna x nowej ramki wideo, w punktach. |
| y | float | Współrzędna y nowej ramki wideo, w punktach. |
| width | float | Szerokość nowej ramki wideo, w punktach. |
| height | float | Wysokość nowej ramki wideo, w punktach. |
| fname | java.lang.String | Ścieżka lub nazwa pliku wideo do osadzenia. |

**Zwraca:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nowo utworzony [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Tworzy nową ramkę audio powiązaną z utworem CD i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Tworzy nową ramkę audio powiązaną z utworem CD i wstawia ją do kolekcji kształtów w określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks, w którym należy wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| fname | java.lang.String | Ścieżka lub nazwa zewnętrznego pliku audio do połączenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów w określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks, w którym należy wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| fname | java.lang.String | Ścieżka lub nazwa zewnętrznego pliku audio do połączenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| audio_stream | java.io.InputStream | Strumień wejściowy zawierający dane audio WAV do osadzenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Tworzy nową ramkę audio i dodaje ją na koniec kolekcji kształtów, używając istniejącego obiektu audio z listy Presentation.Audios.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instancja [IAudio](../../com.aspose.slides/iaudio) z kolekcji Presentation.Audios. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów w określonym indeksie. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks, w którym należy wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| audio_stream | java.io.InputStream | Strumień wejściowy zawierający dane audio WAV do osadzenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów w określonym indeksie, używając istniejącego obiektu audio z listy Presentation.Audios.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks, w którym należy wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instancja [IAudio](../../com.aspose.slides/iaudio) z kolekcji Presentation.Audios do osadzenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Zwraca zero-indeksowy indeks pierwszego wystąpienia określonego kształtu w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt, który ma zostać zlokalizowany w kolekcji. |

**Zwraca:**
int - Zero-indeksowy indeks pierwszego wystąpienia kształtu w kolekcji kształtów, jeśli znaleziono; w przeciwnym razie \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Tworzy i zwraca tablicę zawierającą wszystkie kształty.

**Zwraca:**
com.aspose.slides.IShape[] - Tablica obiektów [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszego kształtu do zwrócenia. |
| count | int | Liczba kształtów do zwrócenia. |

**Zwraca:**
com.aspose.slides.IShape[] - Tablica obiektów [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Przenosi określony kształt na nową pozycję w kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks docelowy, w którym kształt zostanie umieszczony. |
| shape | [IShape](../../com.aspose.slides/ishape) | Obiekt [IShape](../../com.aspose.slides/ishape) do przeniesienia w kolekcji. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Przenosi określone kształty w kolekcji kształtów, umieszczając je począwszy od podanego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks docelowy, w którym pierwszy określony kształt zostanie umieszczony; kolejne kształty podążają kolejno. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Jedna lub więcej instancji [IShape](../../com.aspose.slides/ishape) do przeniesienia w kolekcji. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Tworzy nowy automatyczny kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | Typ [ShapeType](../../com.aspose.slides/shapetype) automatycznego kształtu do dodania. |

| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |

**Zwraca:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).  

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy kształt automatyczny i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) automatycznego kształtu do dodania. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | boolean | True, aby zastosować domyślne formatowanie szablonu (prosty styl, wyśrodkowany tekst i niepustą nazwę) do nowego kształtu; false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na wartości domyślne. |

**Zwraca:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).  

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Tworzy nowy prostokątny kształt automatyczny, który będzie przechowywać treść matematyczną i dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |

**Zwraca:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów pod podanym indeksem, stosując domyślne formatowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym ma zostać wstawiony nowy kształt automatyczny. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) automatycznego kształtu do wstawienia. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |

**Zwraca:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy kształt automatyczny i wstawia go do kolekcji kształtów pod podanym indeksem, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym ma zostać wstawiony kształt automatyczny. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) automatycznego kształtu do wstawienia. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | boolean | True, aby zastosować domyślne formatowanie szablonu (w tym niepustą nazwę, prosty styl i wyśrodkowany tekst); false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na wartości domyślne. |

**Zwraca:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).  

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Tworzy nową pustą grupę kształtów i dodaje ją na koniec kolekcji kształtów. Ramka grupy automatycznie dopasowuje się do zawartych w niej kształtów.

**Zwraca:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Nowo utworzony [IGroupShape](../../com.aspose.slides/igroupshape).  

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Tworzy nową grupę kształtów, konwertuje podany obraz SVG na poszczególne kształty i dodaje powstałą grupę na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) zawierający zawartość wektorową do konwersji na kształty. |
| x | float | Współrzędna x ramki grupy, w punktach. |
| y | float | Współrzędna y ramki grupy, w punktach. |
| width | float | Szerokość ramki grupy, w punktach. |
| height | float | Wysokość ramki grupy, w punktach. |

**Zwraca:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Nowo utworzony [IGroupShape](../../com.aspose.slides/igroupshape).  

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Tworzy nową pustą grupę kształtów i wstawia ją do kolekcji kształtów pod podanym indeksem. Ramka grupy automatycznie dopasowuje się do zawartych w niej kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym ma zostać wstawiona grupa kształtów. |

**Zwraca:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Nowo utworzony [IGroupShape](../../com.aspose.slides/igroupshape).  

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Tworzy nowy kształt łącza z domyślnym formatowaniem szablonu i dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) łącza do dodania. |
| x | float | Współrzędna x ramki łącza, w punktach. |
| y | float | Współrzędna y ramki łącza, w punktach. |
| width | float | Szerokość ramki łącza, w punktach. |
| height | float | Wysokość ramki łącza, w punktach. |

**Zwraca:**  
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).  

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy kształt łącza i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślne formatowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) łącza do utworzenia. |
| x | float | Współrzędna x ramki łącza, w punktach. |
| y | float | Współrzędna y ramki łącza, w punktach. |
| width | float | Szerokość ramki łącza, w punktach. |
| height | float | Wysokość ramki łącza, w punktach. |
| createFromTemplate | boolean | True, aby zastosować domyślne formatowanie szablonu (niepusta nazwa, prosty styl); false, aby utworzyć łącze z wartościami domyślnymi właściwości. |

**Zwraca:**  
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).  

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Tworzy nowy kształt łącza i wstawia go do kolekcji kształtów pod podanym indeksem, stosując domyślne formatowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym ma zostać wstawiony kształt łącza. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) łącza do wstawienia. |
| x | float | Współrzędna x ramki łącza, w punktach. |
| y | float | Współrzędna y ramki łącza, w punktach. |
| width | float | Szerokość ramki łącza, w punktach. |
| height | float | Wysokość ramki łącza, w punktach. |

**Zwraca:**  
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).  

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy kształt łącza i wstawia go do kolekcji kształtów pod podanym indeksem, opcjonalnie stosując domyślne formatowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym ma zostać wstawiony kształt łącza. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) łącza do wstawienia. |
| x | float | Współrzędna x ramki łącza, w punktach. |
| y | float | Współrzędna y ramki łącza, w punktach. |
| width | float | Szerokość ramki łącza, w punktach. |
| height | float | Wysokość ramki łącza, w punktach. |
| createFromTemplate | boolean | True, aby zastosować domyślne formatowanie szablonu (niepusta nazwa, prosty styl); false, aby utworzyć łącze z wartościami domyślnymi właściwości. |

**Zwraca:**  
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).  

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tworzy nową ramkę obrazu zawierającą podany obraz i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | Określa typ kształtu zawarty w [ShapeType](../../com.aspose.slides/shapetype), z wyjątkiem wszystkich rodzajów linii:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | Współrzędna x ramki obrazu, w punktach. |
| y | float | Współrzędna y ramki obrazu, w punktach. |
| width | float | Szerokość ramki obrazu, w punktach. |
| height | float | Wysokość ramki obrazu, w punktach. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) wyświetlany w ramce obrazu. |

**Zwraca:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nowo utworzony [IPictureFrame](../../com.aspose.slides/ipictureframe).  

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tworzy nową ramkę obrazu zawierającą podany obraz i wstawia ją do kolekcji kształtów pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym ma zostać wstawiona ramka obrazu. |
| shapeType | int | Określa typ kształtu zawarty w [ShapeType](../../com.aspose.slides/shapetype), z wyjątkiem wszystkich rodzajów linii:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | Współrzędna x ramki obrazu, w punktach. |
| y | float | Współrzędna y ramki obrazu, w punktach. |
| width | float | Szerokość ramki obrazu, w punktach. |
| height | float | Wysokość ramki obrazu, w punktach. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) wyświetlany w ramce obrazu. |

**Zwraca:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nowo utworzony [IPictureFrame](../../com.aspose.slides/ipictureframe).  

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x tabeli, w punktach. |
| y | float | Współrzędna y tabeli, w punktach. |
| columnWidths | double[] | Tablica podwójnych wartości reprezentująca szerokości kolumn tabeli, w punktach. |
| rowHeights | double[] | Tablica podwójnych wartości reprezentująca wysokości wierszy tabeli, w punktach. |

**Zwraca:**  
[ITable](../../com.aspose.slides/itable) - Nowo utworzony [ITable](../../com.aspose.slides/itable).  

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```
Tworzy nową tabelę i wstawia ją do kolekcji kształtów w określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawia się tabelę. |
| x | float | Współrzędna x tabeli, w punktach. |
| y | float | Współrzędna y tabeli, w punktach. |
| columnWidths | double[] | Tablica liczb zmiennoprzecinkowych (double) reprezentująca szerokości kolumn tabeli, w punktach. |
| rowHeights | double[] | Tablica liczb zmiennoprzecinkowych (double) reprezentująca wysokości wierszy tabeli, w punktach. |

**Zwraca:**
[ITable](../../com.aspose.slides/itable) - Nowo utworzony [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa kształt o określonym indeksie z kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy kształtu do usunięcia. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Usuwa pierwsze wystąpienie określonego kształtu z kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Obiekt [IShape](../../com.aspose.slides/ishape) do usunięcia. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie kształty z kolekcji kształtów.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kształt do sklonowania. |
| x | float | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | float | Współrzędna y ramki sklonowanego kształtu, w punktach. |
| width | float | Szerokość ramki sklonowanego kształtu, w punktach. |
| height | float | Wysokość ramki sklonowanego kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Nowy kształt zachowuje szerokość i wysokość  sourceShape .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Obiekt [IShape](../../com.aspose.slides/ishape) do sklonowania. |
| x | float | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | float | Współrzędna y ramki sklonowanego kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Obiekt [IShape](../../com.aspose.slides/ishape) do sklonowania. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawia się sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Obiekt [IShape](../../com.aspose.slides/ishape) do sklonowania. |
| x | float | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | float | Współrzędna y ramki sklonowanego kształtu, w punktach. |
| width | float | Szerokość ramki sklonowanego kształtu, w punktach. |
| height | float | Wysokość ramki sklonowanego kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie. Nowy kształt zachowuje szerokość i wysokość  sourceShape .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawia się sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Obiekt [IShape](../../com.aspose.slides/ishape) do sklonowania. |
| x | float | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | float | Współrzędna y ramki sklonowanego kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów w określonym indeksie. Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, w którym wstawia się sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Obiekt [IShape](../../com.aspose.slides/ishape) do sklonowania. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).