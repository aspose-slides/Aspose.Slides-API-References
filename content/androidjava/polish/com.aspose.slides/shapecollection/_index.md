---
title: ShapeCollection
second_title: Aspose.Slides dla Androida poprzez Java API Reference
description: Reprezentuje kolekcję kształtów.
type: docs
url: /pl/com.aspose.slides/shapecollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Reprezentuje kolekcję kształtów.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę elementów faktycznie znajdujących się w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca element o podanym indeksie. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów w podanym indeksie. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów w podanym indeksie. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Tworzy nową ramkę Zoom z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Tworzy nową ramkę Zoom sekcji i dodaje ją na koniec kolekcji kształtów. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i dodaje ją na koniec kolekcji kształtów. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Tworzy nową ramkę Zoom sekcji i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Tworzy nową ramkę Zoom podsumowania i dodaje ją na koniec kolekcji kształtów. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Tworzy nową ramkę Zoom podsumowania i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Tworzy nową ramkę wideo i dodaje ją na koniec kolekcji kształtów. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Tworzy nową ramkę audio powiązaną z utworem CD i dodaje ją na koniec kolekcji kształtów. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Tworzy nową ramkę audio powiązaną z utworem CD i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i dodaje ją na koniec kolekcji kształtów. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Tworzy nową ramkę audio i dodaje ją na koniec kolekcji kształtów, używając istniejącego obiektu audio z listy Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów w podanym indeksie, używając istniejącego obiektu audio z listy Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Zwraca indeks (zero-based) pierwszego wystąpienia podanego kształtu w kolekcji. |
| [toArray()](#toArray--) | Tworzy i zwraca tablicę zawierającą wszystkie kształty. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Tworzy i zwraca tablicę zawierającą wszystkie kształty w określonym zakresie. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Przenosi podany kształt na nową pozycję w kolekcji kształtów. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Przenosi podane kształty w kolekcji, umieszczając je począwszy od podanego indeksu. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Tworzy nowy auto-kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Tworzy nowy auto-kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Tworzy nowy prostokątny auto-kształt do hostowania treści matematycznych i dodaje go na koniec kolekcji kształtów. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów w podanym indeksie, stosując domyślne formatowanie szablonu. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów w podanym indeksie, opcjonalnie inicjalizując go domyślnym stylowaniem szablonu. |
| [addGroupShape()](#addGroupShape--) | Tworzy nowy pusty kształt grupy i dodaje go na koniec kolekcji kształtów. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Tworzy nowy kształt grupy, konwertuje podany obraz SVG na poszczególne kształty i dodaje powstałą grupę na koniec kolekcji kształtów. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Tworzy nowy pusty kształt grupy i wstawia go do kolekcji kształtów w podanym indeksie. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Tworzy nowy kształt łącznika z domyślnym stylowaniem szablonu i dodaje go na koniec kolekcji kształtów. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślne stylowanie szablonu. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w podanym indeksie, stosując domyślne stylowanie szablonu. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w podanym indeksie, opcjonalnie stosując domyślne stylowanie szablonu. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tworzy nową ramkę obrazu zawierającą podany obraz i dodaje ją na koniec kolekcji kształtów. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Tworzy nową ramkę obrazu zawierającą podany obraz i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Tworzy nową tabelę i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [removeAt(int index)](#removeAt-int-) | Usuwa kształt o podanym indeksie z kolekcji kształtów. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Usuwa pierwsze wystąpienie podanego kształtu z kolekcji kształtów. |
| [clear()](#clear--) | Usuwa wszystkie kształty z kolekcji kształtów. |
| [iterator()](#iterator--) | Zwraca enumerator umożliwiający iterację po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
| [getParentGroup()](#getParentGroup--) | Pobiera obiekt rodzica grupy dla kolekcji kształtów. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Tworzy kopię podanego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Tworzy kopię podanego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Tworzy kopię podanego kształtu i dodaje ją na koniec kolekcji kształtów. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Tworzy kopię podanego kształtu i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Tworzy kopię podanego kształtu i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Tworzy kopię podanego kształtu i wstawia ją do kolekcji kształtów w podanym indeksie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do podanej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo-bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów faktycznie zawartych w kolekcji. **Tylko do odczytu**  int .

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Zwraca element o podanym indeksie. **Tylko do odczytu** [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz dodaje go na koniec kolekcji kształtów.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Tworzy instancję klasy Presentation reprezentującej plik PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Uzyskuje dostęp do pierwszego slajdu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Dodaje wykres z domyślnymi danymi
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Ustawia tytuł wykresu
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Ustawia pierwszą serię, aby wyświetlała wartości
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Ustawia indeks arkusza danych wykresu
>      int defaultWorksheetIndex = 0;
>      // Pobiera arkusz danych wykresu
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Usuwa domyślnie wygenerowane serie i kategorie
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Dodaje nowe serie
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Dodaje nowe kategorie
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Pobiera pierwszą serię wykresu
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Wypełnia dane serii
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Ustawia kolor wypełnienia serii
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Pobiera drugą serię wykresu
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Wypełnia dane serii
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Ustawia kolor wypełnienia serii
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Ustawia pierwszą etykietę, aby wyświetlała nazwę kategorii
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Ustawia serię, aby wyświetlała wartość dla trzeciej etykiety
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Zapisuje plik PPTX na dysku
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


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
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
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
| initWithSample | boolean | True, aby zainicjować nowy wykres przykładowymi danymi serii i ustawieniami; false, aby utworzyć wykres bez serii i jedynie z minimalnymi ustawieniami, co przyspiesza tworzenie. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Tworzy diagram SmartArt i dodaje go na koniec kolekcji kształtów.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać inteligentny kształt w prezentacji PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
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
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do utworzenia. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość nowego wykresu, w punktach. |
| height | float | Wysokość nowego wykresu, w punktach. |
| index | int | Zero-based indeks, w którym wstawić nowy wykres w kolekcji kształtów. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Tworzy nowy wykres, inicjalizuje go przykładowymi danymi serii i ustawieniami oraz wstawia go do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Typ wykresu do utworzenia. |
| x | float | Współrzędna x nowego wykresu, w punktach. |
| y | float | Współrzędna y nowego wykresu, w punktach. |
| width | float | Szerokość nowego wykresu, w punktach. |
| height | float | Wysokość nowego wykresu, w punktach. |
| index | int | Zero-based indeks, w którym wstawić nowy wykres w kolekcji kształtów. |
| initWithSample | boolean | True, aby zainicjować nowy wykres przykładowymi danymi serii i ustawieniami; false, aby utworzyć wykres bez serii i z minimalnymi ustawieniami, co przyspiesza tworzenie. |

**Zwraca:**
[IChart](../../com.aspose.slides/ichart) - Nowo utworzony [IChart](../../com.aspose.slides/ichart).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Tworzy nową ramkę Zoom i dodaje ją na koniec kolekcji kształtów.

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
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwołany przez ramkę Zoom; musi należeć do tej prezentacji. |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
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
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Tworzy nową ramkę Zoom i wstawia ją do kolekcji kształtów w podanym indeksie.

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
| index | int | Zero-based indeks, w którym wstawić ramkę Zoom. |
| x | float | Współrzędna x nowej ramki Zoom, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom, w punktach. |
| width | float | Szerokość nowej ramki Zoom, w punktach. |
| height | float | Wysokość nowej ramki Zoom, w punktach. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) odwołany przez ramkę Zoom. |

**Zwraca:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Nowo utworzony [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
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
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę Zoom. |
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
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
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
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
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
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Tworzy nową ramkę Zoom sekcji i wstawia ją do kolekcji kształtów w podanym indeksie.

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
| index | int | Zero-based indeks, w którym wstawić ramkę Zoom sekcji. |
| x | float | Współrzędna x nowej ramki Zoom sekcji, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom sekcji, w punktach. |
| width | float | Szerokość nowej ramki Zoom sekcji, w punktach. |
| height | float | Wysokość nowej ramki Zoom sekcji, w punktach. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) odwołany przez ramkę Zoom sekcji; musi należeć do tej prezentacji i zawierać co najmniej jeden slajd. |

**Zwraca:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Nowo utworzony [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Tworzy nową ramkę Zoom sekcji z predefiniowanym obrazem i wstawia ją do kolekcji kształtów w podanym indeksie.

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
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę Zoom sekcji. |
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
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Tworzy nową ramkę Zoom podsumowania i dodaje ją na koniec kolekcji kształtów.

--------------------

> ```
> Ten przykład demonstruje dodawanie obiektu Summary Zoom na koniec kolekcji
>  (zakładając, że w prezentacji "Presentation.pptx" znajduje się co najmniej dwie sekcje):
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

--------------------
Ta metoda tworzy nowy Zoom podsumowania i umieszcza w nim kolekcję obiektów dla wszystkich sekcji w tej prezentacji.

**Zwraca:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nowo utworzony [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Tworzy nową ramkę Zoom podsumowania i wstawia ją do kolekcji kształtów w podanym indeksie.

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
| index | int | Zero-based indeks, w którym wstawić ramkę Zoom podsumowania. |
| x | float | Współrzędna x nowej ramki Zoom podsumowania, w punktach. |
| y | float | Współrzędna y nowej ramki Zoom podsumowania, w punktach. |
| width | float | Szerokość nowej ramki Zoom podsumowania, w punktach. |
| height | float | Wysokość nowej ramki Zoom podsumowania, w punktach. |

--------------------
Ta metoda tworzy ramkę Zoom podsumowania, która agreguje linki podsumowujące wszystkie sekcje w prezentacji.

**Zwraca:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Nowo utworzony [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tworzy nową ramkę obiektu OLE i dodaje ją na koniec kolekcji kształtów.

--------------------

> ```
> Poniższe przykłady pokazują, jak dodawać ramki obiektów OLE do slajdów prezentacji PowerPoint.
>  
>  // Utwórz instancję klasy Presentation reprezentującej plik PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Uzyskaj dostęp do pierwszego slajdu
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Wczytaj plik Excel do strumienia
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
>      // Utwórz obiekt danych do osadzenia
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Dodaj kształt ramki obiektu OLE
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Zapisz plik PPTX na dysku
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


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
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
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
| path | java.lang.String | Ścieżka do powiązanego pliku.

Ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano ścieżkę względną, plik będzie niedostępny przy otwieraniu prezentacji z innego katalogu. |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w podanym indeksie.

--------------------

> ```
> Ten przykład demonstruje wstawianie obiektu OLE pod drugim indeksem:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę obiektu OLE. |
| x | float | Współrzędna x nowej ramki OLE, w punktach. |
| y | float | Współrzędna y nowej ramki OLE, w punktach. |
| width | float | Szerokość nowej ramki OLE, w punktach. |
| height | float | Wysokość nowej ramki OLE, w punktach. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Informacje o osadzonych danych OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Tworzy nową ramkę obiektu OLE i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę obiektu OLE. |
| x | float | Współrzędna x nowej ramki OLE, w punktach. |
| y | float | Współrzędna y nowej ramki OLE, w punktach. |
| width | float | Szerokość nowej ramki OLE, w punktach. |
| height | float | Wysokość nowej ramki OLE, w punktach. |
| className | java.lang.String | Nazwa klasy obiektu OLE. |
| path | java.lang.String | Ścieżka do powiązanego pliku.

Ścieżka jest przechowywana dosłownie w prezentacji. Jeśli podano ścieżkę względną, plik będzie niedostępny przy otwieraniu prezentacji z innego katalogu. |

**Zwraca:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Nowo utworzony obiekt OLE.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
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
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
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
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Tworzy nową ramkę wideo i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę wideo. |
| x | float | Współrzędna x nowej ramki wideo, w punktach. |
| y | float | Współrzędna y nowej ramki wideo, w punktach. |
| width | float | Szerokość nowej ramki wideo, w punktach. |
| height | float | Wysokość nowej ramki wideo, w punktach. |
| fname | java.lang.String | Ścieżka lub nazwa pliku wideo do osadzenia. |

**Zwraca:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Nowo utworzony [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
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
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Tworzy nową ramkę audio powiązaną z utworem CD i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
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
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Tworzy nową ramkę audio powiązaną z zewnętrznym plikiem audio i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| fname | java.lang.String | Ścieżka lub nazwa zewnętrznego pliku audio do połączenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Tworzy nową ramkę audio z osadzonym plikiem WAV i dodaje ją na koniec kolekcji kształtów. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

--------------------

> ```
> Poniższy przykład pokazuje, jak utworzyć ramkę audio.
>  
>  // Tworzy instancję klasy Presentation reprezentującej plik prezentacji
>  Presentation pres = new Presentation();
>  try {
>      // Pobiera pierwszy slajd
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Wczytuje plik dźwiękowy wav do strumienia
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Dodaje ramkę audio
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Ustawia tryb odtwarzania i głośność dźwięku
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Zapisuje plik PowerPoint na dysku
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


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
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Tworzy nową ramkę audio z osadzonym plikiem WAV i wstawia ją do kolekcji kształtów w podanym indeksie. Osadzony dźwięk jest dodawany do kolekcji Presentation.Audios.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| audio_stream | java.io.InputStream | Strumień wejściowy zawierający dane audio WAV do osadzenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
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
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Tworzy nową ramkę audio i wstawia ją do kolekcji kształtów w podanym indeksie, używając istniejącego obiektu audio z listy Presentation.Audios.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę audio. |
| x | float | Współrzędna x nowej ramki audio, w punktach. |
| y | float | Współrzędna y nowej ramki audio, w punktach. |
| width | float | Szerokość nowej ramki audio, w punktach. |
| height | float | Wysokość nowej ramki audio, w punktach. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Instancja [IAudio](../../com.aspose.slides/iaudio) z kolekcji Presentation.Audios do osadzenia. |

**Zwraca:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Nowo utworzony [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Zwraca zero-based indeks pierwszego wystąpienia podanego kształtu w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Kształt, którego położenie ma być wyszukane w kolekcji. |

**Zwraca:**
int - Zero-based indeks pierwszego wystąpienia kształtu w kolekcji kształtów, jeśli znaleziono; w przeciwnym razie \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Tworzy i zwraca tablicę zawierającą wszystkie kształty.

**Zwraca:**
com.aspose.slides.IShape[] - Tablica obiektów [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Tworzy i zwraca tablicę zawierającą wszystkie kształty w podanym zakresie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | int | Indeks pierwszego kształtu do zwrócenia. |
| count | int | Liczba kształtów do zwrócenia. |

**Zwraca:**
com.aspose.slides.IShape[] - Tablica obiektów [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Przenosi podany kształt na nową pozycję w kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks docelowy, w którym kształt zostanie umieszczony. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do przeniesienia w kolekcji. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Przenosi podane kształty w kolekcji kształtów, umieszczając je począwszy od podanego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks docelowy, w którym zostanie umieszczony pierwszy podany kształt; kolejne kształty będą podążać w kolejności podanej. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Jeden lub więcej instancji [IShape](../../com.aspose.slides/ishape) do przeniesienia w kolekcji. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Tworzy nowy auto-kształt z domyślnym formatowaniem i dodaje go na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nowego auto-kształtu. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy auto-kształt i dodaje go na koniec kolekcji kształtów, opcjonalnie inicjalizując go domyślnym formatowaniem szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nowego auto-kształtu. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | boolean | True, aby zastosować domyślne stylowanie szablonu (prosty styl, wyśrodkowany tekst i niepustą nazwę) do nowego kształtu; false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na wartości domyślne. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Tworzy nowy prostokątny auto-kształt do hostowania treści matematycznych i dodaje go na koniec kolekcji kształtów.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać równanie matematyczne w prezentacji PowerPoint.
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
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów w podanym indeksie, stosując domyślne formatowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić nowy auto-kształt. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nowego auto-kształtu. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy auto-kształt i wstawia go do kolekcji kształtów w podanym indeksie, opcjonalnie inicjalizując go domyślnym stylowaniem szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić auto-kształt. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nowego auto-kształtu. |
| x | float | Współrzędna x ramki kształtu, w punktach. |
| y | float | Współrzędna y ramki kształtu, w punktach. |
| width | float | Szerokość ramki kształtu, w punktach. |
| height | float | Wysokość ramki kształtu, w punktach. |
| createFromTemplate | boolean | True, aby zastosować domyślne stylowanie szablonu (w tym niepustą nazwę, prosty styl i wyśrodkowany tekst); false, aby utworzyć kształt ze wszystkimi właściwościami ustawionymi na domyślne. |

**Zwraca:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Nowo utworzony [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Tworzy nowy pusty kształt grupy i dodaje go na koniec kolekcji kształtów. Ramka grupy automatycznie dostosowuje się do zawartych w niej kształtów.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać grupowy kształt do slajdu prezentacji PowerPoint.
>  
>  // Tworzy instancję klasy Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Pobiera pierwszy slajd
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Uzyskiwanie kolekcji kształtów slajdu
>      IShapeCollection slideShapes = sld.getShapes();
>      // Dodawanie grupowego kształtu do slajdu
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Dodawanie kształtów wewnątrz dodanego grupowego kształtu
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Dodawanie ramki grupowego kształtu
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Zapis pliku PPTX na dysku
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nowo utworzony [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Tworzy nowy kształt grupy, konwertuje podany obraz SVG na poszczególne kształty i dodaje wynikową grupę na koniec kolekcji kształtów.

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
public final IGroupShape insertGroupShape(int index)
```

Tworzy nowy pusty kształt grupy i wstawia go do kolekcji kształtów w podanym indeksie. Ramka grupy automatycznie dostosowuje się do zawartych w niej kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić kształt grupy. |

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Nowo utworzony [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Tworzy nowy kształt łącznika z domyślnym stylowaniem szablonu i dodaje go na koniec kolekcji kształtów.

--------------------

> ```
> Poniższy przykład pokazuje, jak dodać łącznik (zagięty łącznik) między dwoma kształtami (elipsą i prostokątem) w prezentacji PowerPoint.
>  
>  // Tworzy instancję klasy prezentacji reprezentującej plik PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Uzyskuje dostęp do kolekcji kształtów dla konkretnego slajdu
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Dodaje autokształt elipsy
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Dodaje autokształt prostokąta
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Dodaje kształt łącznika do kolekcji kształtów slajdu
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Łączy kształty za pomocą łącznika
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Wywołuje metodę reroute, która ustawia automatyczną najkrótszą ścieżkę między kształtami
>      connector.reroute();
>      // Zapisuje prezentację
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nowego łącznika. |
| x | float | Współrzędna x ramki łącznika, w punktach. |
| y | float | Współrzędna y ramki łącznika, w punktach. |
| width | float | Szerokość ramki łącznika, w punktach. |
| height | float | Wysokość ramki łącznika, w punktach. |

**Zwraca:**
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy kształt łącznika i dodaje go na koniec kolekcji kształtów, opcjonalnie stosując domyślne stylowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nowego łącznika. |
| x | float | Współrzędna x ramki łącznika, w punktach. |
| y | float | Współrzędna y ramki łącznika, w punktach. |
| width | float | Szerokość ramki łącznika, w punktach. |
| height | float | Wysokość ramki łącznika, w punktach. |
| createFromTemplate | boolean | True, aby zastosować domyślne stylowanie szablonu (niepusta nazwa, prosty styl); false, aby utworzyć łącznik z domyślnymi wartościami właściwości. |

**Zwraca:**
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w podanym indeksie, stosując domyślne stylowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić łącznik. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nowego łącznika. |
| x | float | Współrzędna x ramki łącznika, w punktach. |
| y | float | Współrzędna y ramki łącznika, w punktach. |
| width | float | Szerokość ramki łącznika, w punktach. |
| height | float | Wysokość ramki łącznika, w punktach. |

**Zwraca:**
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Tworzy nowy kształt łącznika i wstawia go do kolekcji kształtów w podanym indeksie, opcjonalnie stosując domyślne stylowanie szablonu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić łącznik. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) nowego łącznika. |
| x | float | Współrzędna x ramki łącznika, w punktach. |
| y | float | Współrzędna y ramki łącznika, w punktach. |
| width | float | Szerokość ramki łącznika, w punktach. |
| height | float | Wysokość ramki łącznika, w punktach. |
| createFromTemplate | boolean | True, aby zastosować domyślne stylowanie szablonu (niepusta nazwa, prosty styl); false, aby utworzyć łącznik z domyślnymi właściwościami. |

**Zwraca:**
[IConnector](../../com.aspose.slides/iconnector) - Nowo utworzony [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tworzy nową ramkę obrazu zawierającą podany obraz i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeType | int | Określa typ kształtu zawartego w [ShapeType](../../com.aspose.slides/shapetype), z wyjątkiem wszystkich rodzajów linii: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Współrzędna x ramki obrazu, w punktach. |
| y | float | Współrzędna y ramki obrazu, w punktach. |
| width | float | Szerokość ramki obrazu, w punktach. |
| height | float | Wysokość ramki obrazu, w punktach. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) do wyświetlenia w ramce obrazu. |

**Zwraca:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nowo utworzony [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Tworzy nową ramkę obrazu zawierającą podany obraz i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić ramkę obrazu. |
| shapeType | int | Określa typ kształtu zawartego w [ShapeType](../../com.aspose.slides/shapetype), z wyłączeniem wszystkich rodzajów linii: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Współrzędna x ramki obrazu, w punktach. |
| y | float | Współrzędna y ramki obrazu, w punktach. |
| width | float | Szerokość ramki obrazu, w punktach. |
| height | float | Wysokość ramki obrazu, w punktach. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) do wyświetlenia w ramce obrazu. |

**Zwraca:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Nowo utworzony [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Tworzy nową tabelę i dodaje ją na koniec kolekcji kształtów.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // Tworzy instancję klasy Presentation reprezentującej plik PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Uzyskuje dostęp do pierwszego slajdu
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Definiuje kolumny o określonych szerokościach i wiersze o określonych wysokościach
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Dodaje kształt tabeli do slajdu
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Ustawia format obramowania dla każdej komórki
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
>      // Łączy komórki 1 i 2 wiersza 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Dodaje tekst do połączonej komórki
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Zapisuje plik PPTX na dysku
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| x | float | Współrzędna x tabeli, w punktach. |
| y | float | Współrzędna y tabeli, w punktach. |
| columnWidths | double[] | Tablica podająca szerokości kolumn tabeli, w punktach. |
| rowHeights | double[] | Tablica podająca wysokości wierszy tabeli, w punktach. |

**Zwraca:**
[ITable](../../com.aspose.slides/itable) - Nowo utworzona [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Tworzy nową tabelę i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić tabelę. |
| x | float | Współrzędna x tabeli, w punktach. |
| y | float | Współrzędna y tabeli, w punktach. |
| columnWidths | double[] | Tablica podająca szerokości kolumn tabeli, w punktach. |
| rowHeights | double[] | Tablica podająca wysokości wierszy tabeli, w punktach. |

**Zwraca:**
[ITable](../../com.aspose.slides/itable) - Nowo utworzona [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa kształt o podanym indeksie z kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks kształtu do usunięcia. |
### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Usuwa pierwsze wystąpienie podanego kształtu z kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do usunięcia. |
### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie kształty z kolekcji kształtów.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - IGenericEnumerator umożliwiający iterację po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - java.util.Iterator dla całej kolekcji.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Pobiera obiekt grupy rodzica dla kolekcji kształtów. **Tylko do odczytu** [IGroupShape](../../com.aspose.slides/igroupshape).

**Zwraca:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Tworzy kopię podanego kształtu i dodaje ją na koniec kolekcji kształtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kształt do sklonowania. |
| x | float | Współrzędna x nowej ramki kształtu, w punktach. |
| y | float | Współrzędna y nowej ramki kształtu, w punktach. |
| width | float | Szerokość nowej ramki kształtu, w punktach. |
| height | float | Wysokość nowej ramki kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Tworzy kopię podanego kształtu i dodaje ją na koniec kolekcji kształtów. Nowy kształt zachowuje szerokość i wysokość źródłowego kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kształt do sklonowania. |
| x | float | Współrzędna x nowej ramki kształtu, w punktach. |
| y | float | Współrzędna y nowej ramki kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Tworzy kopię podanego kształtu i dodaje ją na koniec kolekcji kształtów. Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Tworzy kopię podanego kształtu i wstawia ją do kolekcji kształtów w podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |
| x | float | Współrzędna x sklonowanego kształtu, w punktach. |
| y | float | Współrzędna y sklonowanego kształtu, w punktach. |
| width | float | Szerokość sklonowanego kształtu, w punktach. |
| height | float | Wysokość sklonowanego kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Tworzy kopię podanego kształtu i wstawia ją do kolekcji kształtów w podanym indeksie. Nowy kształt zachowuje szerokość i wysokość źródłowego kształtu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |
| x | float | Współrzędna x sklonowanego kształtu, w punktach. |
| y | float | Współrzędna y sklonowanego kształtu, w punktach. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Tworzy kopię podanego kształtu i wstawia ją do kolekcji kształtów w podanym indeksie. Sklonowany kształt zachowuje pozycję i rozmiar oryginału.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-based indeks, w którym wstawić sklonowany kształt. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) do sklonowania. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - Nowo utworzony [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do podanej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Indeks początkowy w tablicy docelowej. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo-bezpieczny). **Tylko do odczytu**  boolean .

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. **Tylko do odczytu**  Object .

**Zwraca:**
java.lang.Object