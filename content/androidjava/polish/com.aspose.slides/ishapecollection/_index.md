---
title: IShapeCollection
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji interfejsu API Java
description: Reprezentuje kolekcję kształtów.
type: docs
url: /pl/com.aspose.slides/ishapecollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Reprezentuje kolekcję kształtów.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o określonym indeksie. |
| [getParentGroup()](#getParentGroup--) | Pobiera obiekt grupy nadrzędnej dla kolekcji kształtów. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów podanym indeksem. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów podanym indeksem. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów podanym indeksem. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów podanym indeksem. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów podanym indeksem. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów podanym indeksem. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Tworzy nową ramkę Zoom sekcji i dodaje ją na koniec kolekcji kształtów. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i dodaje ją na koniec kolekcji kształtów. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Tworzy nową ramkę Zoom sekcji i wstawia ją do kolekcji kształtów podanym indeksem. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i wstawia ją do kolekcji kształtów podanym indeksem. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Tworzy nową ramkę Zoom podsumowania i dodaje ją na koniec kolekcji kształtów. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Tworzy nową ramkę Zoom podsumowania i wstawia ją do kolekcji kształtów podanym indeksem. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów podanym indeksem. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Tworzy nową ramkę audio połączoną z ścieżką CD i dodaje ją na koniec kolekcji kształtów. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Tworzy nową ramkę audio połączoną z ścieżką CD i wstawia ją do kolekcji kształtów podanym indeksem. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Tworzy nową ramkę audio połączoną z zewnętrznym plikiem audio i dodaje ją na koniec kolekcji kształtów. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Tworzy nową ramkę audio połączoną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów podanym indeksem. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Tworzy nową ramkę audio i dodaje ją na koniec kolekcji kształtów przy użyciu istniejącego obiektu audio z listy Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów podanym indeksem. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów podanym indeksem przy użyciu istniejącego obiektu audio z listy Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Zwraca indeks bazujący na zerze pierwszego wystąpienia określonego kształtu w kolekcji. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę zawierającą wszystkie kształty. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Przenosi określony kształt na nową pozycję w kolekcji kształtów. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Przenosi określone kształty w kolekcji kształtów, zaczynając od podanego indeksu. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Tworzy nowy auto-kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Tworzy nowy auto-kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Tworzy nowy prostokątny auto-kształt przeznaczony do treści matematycznych i dodaje go na koniec kolekcji kształtów. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów podanym indeksem, stosując domyślne formatowanie szablonu. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów podanym indeksem, opcjonalnie inicjalizując go domyślnym stylizowaniem szablonu. |
| [addGroupShape()](#addGroupShape--) | Tworzy nowy pusty kształt grupy i dodaje go na koniec kolekcji kształtów. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Tworzy nowy kształt grupy, konwertuje podany obraz SVG na poszczególne kształty i dodaje powstałą grupę na koniec kolekcji kształtów. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Tworzy nowy pusty kształt grupy i wstawia go do kolekcji kształtów podanym indeksem. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Tworzy nowy kształt łącznika z domyślnym stylizowaniem szablonu i dodaje go na koniec kolekcji kształtów. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślne stylizowanie szablonu. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów podanym indeksem, stosując domyślne stylizowanie szablonu. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów podanym indeksem, opcjonalnie stosując domyślne stylizowanie szablonu. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tworzy nową ramkę obrazu zawierającą podany obraz i dodaje ją na koniec kolekcji kształtów. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tworzy nową ramkę obrazu zawierającą podany obraz i wstawia ją do kolekcji kształtów podanym indeksem. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Tworzy nową tabelę i wstawia ją do kolekcji kształtów podanym indeksem. |
| [removeAt(int index)](#removeAt-int-) | Usuwa kształt podanym indeksem z kolekcji kształtów. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Usuwa pierwsze wystąpienie określonego kształtu z kolekcji kształtów. |
| [clear()](#clear--) | Usuwa wszystkie kształty z kolekcji kształtów. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem. |

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

Pobiera obiekt grupy nadrzędnej dla kolekcji kształtów. Tylko do odczytu [IGroupShape](../../com.aspose.slides/igroupshape).

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

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

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do dodania. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość wykresu, w punktach. |
| height | float | Wysokość wykresu, w punktach. |
| initWithSample | boolean | Prawda, aby zainicjować nowy wykres przykładowymi danymi serii i ustawieniami; fałsz, aby utworzyć wykres bez serii i jedynie z minimalnymi ustawieniami, co przyspiesza tworzenie. |

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

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do utworzenia. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość nowego wykresu, w punktach. |
| height | float | Wysokość nowego wykresu, w punktach. |
| index | int | Indeks bazujący na zerze, pod którym wstawić nowy wykres w kolekcji kształtów. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do utworzenia. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość nowego wykresu, w punktach. |
| height | float | Wysokość nowego wykresu, w punktach. |
| index | int | Indeks bazujący na zerze, pod którym wstawić nowy wykres w kolekcji kształtów. |
| initWithSample | boolean | Prawda, aby zainicjować nowy wykres przykładowymi danymi serii i ustawieniami; fałsz, aby utworzyć wykres bez serii i jedynie z minimalnymi ustawieniami, co przyspiesza tworzenie. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

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

Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki OLE, w punktach. |
| y | float | Współrzędna y nowej ramki OLE, w punktach. |
| width | float | Szerokość nowej ramki OLE, w punktach. |
| height | float | Wysokość nowej ramki OLE, w punktach. |
| className | java.lang.String | Nazwa klasy obiektu OLE. |
| path | java.lang.String | Ścieżka do pliku powiązanego.

Ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano ścieżkę względną, plik będzie nie dostępny przy otwieraniu prezentacji z innego katalogu. |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę obiektu OLE. |
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

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę obiektu OLE. |
| x | float | Współrzędna x nowej ramki OLE, w punktach. |
| y | float | Współrzędna y nowej ramki OLE, w punktach. |
| width | float | Szerokość nowej ramki OLE, w punktach. |
| height | float | Wysokość nowej ramki OLE, w punktach. |
| className | java.lang.String | Nazwa klasy obiektu OLE. |
| path | java.lang.String | Ścieżka do pliku powiązanego.

Ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano ścieżkę względną, plik będzie nie dostępny przy otwieraniu prezentacji z innego katalogu. |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.

--------------------

> ```
> Ten przykład demonstruje dodawanie obiektu Zoom na koniec kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwa slajdy):
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
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwołany przez ramkę Zoom; musi należeć do tej prezentacji. |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.

--------------------

> ```
> Ten przykład demonstruje dodawanie obiektu Zoom na koniec kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwa slajdy):
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
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwołany przez ramkę Zoom; musi należeć do tej prezentacji. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obraz dla odwoływanego slajdu [IPPImage](../../com.aspose.slides/ippimage). |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów podanym indeksem.

--------------------

> ```
> Ten przykład demonstruje tworzenie i wstawianie obiektu Zoom pod określonym indeksem w kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwa slajdy):
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
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę Zoom. |
| x | float | Współrzędna x nowej ramki Zoom, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom, w punktach. |
| width | float | Szerokość nowej ramki Zoom, w punktach. |
| height | float | Wysokość nowej ramki Zoom, w punktach. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwołany przez ramkę Zoom. |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów podanym indeksem.

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
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę Zoom. |
| x | float | Współrzędna x nowej ramki Zoom, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom, w punktach. |
| width | float | Szerokość nowej ramki Zoom, w punktach. |
| height | float | Wysokość nowej ramki Zoom, w punktach. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwołany przez ramkę Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obraz dla odwoływanego slajdu [IPPImage](../../com.aspose.slides/ippimage). |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Tworzy nową ramkę Zoom sekcji i dodaje ją na koniec kolekcji kształtów.

--------------------

> ```
> Ten przykład demonstruje dodawanie obiektu Section Zoom na koniec kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje):
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
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwołany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i dodaje ją na koniec kolekcji kształtów.

--------------------

> ```
> Ten przykład demonstruje dodawanie obiektu Section Zoom na koniec kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje):
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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x nowej ramki Zoom sekcji, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom sekcji, w punktach. |
| width | float | Szerokość nowej ramki Zoom sekcji, w punktach. |
| height | float | Wysokość nowej ramki Zoom sekcji, w punktach. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwołany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) do wyświetlenia w ramce Zoom sekcji. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Tworzy nową ramkę Zoom sekcji i wstawia ją do kolekcji kształtów podanym indeksem.

--------------------

> ```
> Ten przykład demonstruje tworzenie i wstawianie obiektu Section Zoom pod określonym indeksem w kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje):
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
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę Zoom sekcji. |
| x | float | Współrzędna x nowej ramki Zoom sekcji, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom sekcji, w punktach. |
| width | float | Szerokość nowej ramki Zoom sekcji, w punktach. |
| height | float | Wysokość nowej ramki Zoom sekcji, w punktach. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwołany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i wstawia ją do kolekcji kształtów podanym indeksem.

--------------------

> ```
> Ten przykład demonstruje tworzenie i wstawianie obiektu Section Zoom pod określonym indeksem w kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje):
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

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę Zoom sekcji. |
| x | float | Współrzędna x nowej ramki Zoom sekcji, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom sekcji, w punktach. |
| width | float | Szerokość nowej ramki Zoom sekcji, w punktach. |
| height | float | Wysokość nowej ramki Zoom sekcji, w punktach. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwołany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Obraz do wyświetlenia w ramce Zoom sekcji. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Tworzy nową ramkę Zoom podsumowania i dodaje ją na koniec kolekcji kształtów.

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

Ta metoda tworzy ramkę Zoom podsumowania, która agreguje odnośniki podsumowujące wszystkie sekcje w prezentacji.

**Zwraca:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nowo utworzony [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Tworzy nową ramkę Zoom podsumowania i wstawia ją do kolekcji kształtów podanym indeksem.

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
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę Zoom podsumowania. |
| x | float | Współrzędna x nowej ramki Zoom podsumowania, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom podsumowania, w punktach. |
| width | float | Szerokość nowej ramki Zoom podsumowania, w punktach. |
| height | float | Wysokość nowej ramki Zoom podsumowania, w punktach. |

Ta metoda tworzy ramkę Zoom podsumowania, która agreguje odnośniki podsumowujące wszystkie sekcje w prezentacji.

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
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) do osadzenia w ramce wideo. |

**Zwraca:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nowo utworzony [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę wideo. |
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

Tworzy nową ramkę audio połączoną z ścieżką CD i dodaje ją na koniec kolekcji kształtów.

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

Tworzy nową ramkę audio połączoną z ścieżką CD i wstawia ją do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę audio. |
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

Tworzy nową ramkę audio połączoną z zewnętrznym plikiem audio i dodaje ją na koniec kolekcji kształtów.

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

Tworzy nową ramkę audio połączoną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę audio. |
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
| audio_stream | java.io.InputStream | Strumień wejściowy zawierający dane WAV do osadzenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Tworzy nową ramkę audio i dodaje ją na koniec kolekcji kształtów przy użyciu istniejącego obiektu audio z listy Presentation.Audios.

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

Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów podanym indeksem. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| audio_stream | java.io.InputStream | Strumień wejściowy zawierający dane WAV do osadzenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów podanym indeksem przy użyciu istniejącego obiektu audio z listy Presentation.Audios.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę audio. |
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

Zwraca indeks bazujący na zerze pierwszego wystąpienia określonego kształtu w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt, który ma zostać zlokalizowany w kolekcji. |

**Zwraca:**
int - Indeks bazujący na zerze pierwszego wystąpienia kształtu w kolekcji kształtów, jeśli znaleziono; w przeciwnym razie \\u20131.

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
| index | int | Indeks bazujący na zerze, w którym kształt zostanie umieszczony. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do przeniesienia w kolekcji. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Przenosi określone kształty w kolekcji kształtów, rozpoczynając od podanego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, w którym zostanie umieszczony pierwszy określony kształt; kolejne kształty podążają w kolejności podanej. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Jedna lub więcej instancji [IShape](../../com.aspose.slides/ishape) do przeniesienia w kolekcji. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Tworzy nowy auto-kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto-kształtu do dodania. |
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

Tworzy nowy auto-kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto-kształtu do dodania. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | boolean | Prawda, aby zastosować domyślne stylizowanie szablonu (prosty styl, wyśrodkowany tekst i niepustą nazwę) do nowego kształtu; fałsz, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na wartości domyślne. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Tworzy nowy prostokątny auto-kształt przeznaczony do treści matematycznych i dodaje go na koniec kolekcji kształtów.

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

Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów podanym indeksem, stosując domyślne formatowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić nowy auto-kształt. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto-kształtu do wstawienia. |
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

Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów podanym indeksem, opcjonalnie inicjalizując go domyślnym stylizowaniem szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić auto-kształt. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) auto-kształtu do wstawienia. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | boolean | Prawda, aby zastosować domyślne stylizowanie szablonu (w tym niepustą nazwę, prosty styl i wyśrodkowany tekst); fałsz, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na wartości domyślne. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Tworzy nowy pusty kształt grupy i dodaje go na koniec kolekcji kształtów. Ramka grupy automatycznie dopasowuje się do wszelkich dodanych do niej kształtów.

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nowo utworzony [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Tworzy nowy kształt grupy, konwertuje podany obraz SVG na poszczególne kształty i dodaje powstałą grupę na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) zawierający treść wektorową do konwersji na kształty. |
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

Tworzy nowy pusty kształt grupy i wstawia go do kolekcji kształtów podanym indeksem. Ramka grupy automatycznie dopasowuje się do wszelkich dodanych do niej kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić kształt grupy. |

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nowo utworzony [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Tworzy nowy kształt łącznika z domyślnym stylizowaniem szablonu i dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) łącznika do dodania. |
| x | float | Współrzędna x ramki łącznika, w punktach. |
| y | float | Współrzędna y ramki łącznika, w punktach. |
| width | float | Szerokość ramki łącznika, w punktach. |
| height | float | Wysokość ramki łącznika, w punktach. |

**Zwraca:**
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślne stylizowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) łącznika do utworzenia. |
| x | float | Współrzędna x ramki łącznika, w punktach. |
| y | float | Współrzędna y ramki łącznika, w punktach. |
| width | float | Szerokość ramki łącznika, w punktach. |
| height | float | Wysokość ramki łącznika, w punktach. |
| createFromTemplate | boolean | Prawda, aby zastosować domyślne stylizowanie szablonu (niepusta nazwa, prosty styl); fałsz, aby utworzyć łącznik z domyślnymi wartościami właściwości. |

**Zwraca:**
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów podanym indeksem, stosując domyślne stylizowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić łącznik. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) łącznika do wstawienia. |
| x | float | Współrzędna x ramki łącznika, w punktach. |
| y | float | Współrzędna y ramki łącznika, w punktach. |
| width | float | Szerokość ramki łącznika, w punktach. |
| height | float | Wysokość ramki łącznika, w punktach. |

**Zwraca:**
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów podanym indeksem, opcjonalnie stosując domyślne stylizowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić łącznik. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) łącznika do wstawienia. |
| x | float | Współrzędna x ramki łącznika, w punktach. |
| y | float | Współrzędna y ramki łącznika, w punktach. |
| width | float | Szerokość ramki łącznika, w punktach. |
| height | float | Wysokość ramki łącznika, w punktach. |
| createFromTemplate | boolean | Prawda, aby zastosować domyślne stylizowanie szablonu (niepusta nazwa, prosty styl); fałsz, aby utworzyć łącznik z domyślnymi wartościami właściwości. |

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
| shapeType | int | Określa typ kształtu zawartego w [ShapeType](../../com.aspose.slides/shapetype), z wyjątkiem wszystkich rodzajów linii:

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
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) do wyświetlenia w ramce obrazu. |

**Zwraca:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nowo utworzony [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tworzy nową ramkę obrazu zawierającą podany obraz i wstawia ją do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić ramkę obrazu. |
| shapeType | int | Określa typ kształtu zawartego w [ShapeType](../../com.aspose.slides/shapetype), z wyjątkiem wszystkich rodzajów linii:

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
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) do wyświetlenia w ramce obrazu. |

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
| columnWidths | double[] | Tablica podająca szerokości kolumn tabeli, w punktach. |
| rowHeights | double[] | Tablica podająca wysokości wierszy tabeli, w punktach. |

**Zwraca:**
[ITable](../../com.aspose.slides/itable) - Nowo utworzony [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Tworzy nową tabelę i wstawia ją do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić tabelę. |
| x | float | Współrzędna x tabeli, w punktach. |
| y | float | Współrzędna y tabeli, w punktach. |
| columnWidths | double[] | Tablica podająca szerokości kolumn tabeli, w punktach. |
| rowHeights | double[] | Tablica podająca wysokości wierszy tabeli, w punktach. |

**Zwraca:**
[ITable](../../com.aspose.slides/itable) - Nowo utworzony [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa kształt podanym indeksem z kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze kształtu do usunięcia. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Usuwa pierwsze wystąpienie określonego kształtu z kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do usunięcia. |

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

Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Nowy kształt zachowuje szerokość i wysokość źródłowego kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |
| x | float | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | float | Współrzędna y ramki sklonowanego kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Tworzy kopię określonego kształtu i dodaje ją na koniec kolekcji kształtów. Sklonowany kształt zachowuje pierwotną pozycję i rozmiar.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |
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

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem. Nowy kształt zachowuje szerokość i wysokość źródłowego kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |
| x | float | Współrzędna x ramki sklonowanego kształtu, w punktach. |
| y | float | Współrzędna y ramki sklonowanego kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Tworzy kopię określonego kształtu i wstawia ją do kolekcji kształtów podanym indeksem. Sklonowany kształt zachowuje pierwotną pozycję i rozmiar.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, pod którym wstawić sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).