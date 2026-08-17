---
title: ShapeCollection
second_title: Aspose.Slides için Java API Referansı
description: Şekillerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/shapecollection/
---
**Kalıtım:**
java.lang.Object, com.aspose.slides.DomObject

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Şekillerin bir koleksiyonunu temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [size()](#size--) | Koleksiyonda gerçekte bulunan eleman sayısını alır. |
| [get_Item(int index)](#get-Item-int-) | Belirtilen indeksteki öğeyi alır. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Yeni bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen indekste şekil koleksiyonuna ekler. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntüyle yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntüyle yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntüyle yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Yeni bir video çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Belirtilen şeklin koleksiyondaki ilk oluşumunun sıfır tabanlı indeksini döndürür. |
| [toArray()](#toArray--) | Tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Belirtilen şekli şekil koleksiyonunda yeni bir konuma taşır. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Belirtilen şekilleri şekil koleksiyonunda, verilen indeksten başlayarak yerleştirir. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Varsayılan biçimlendirmeye sahip yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Matematiksel içeriği barındıracak yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Yeni bir otomatik şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Yeni bir otomatik şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stiliyle başlatır. |
| [addGroupShape()](#addGroupShape--) | Boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü ayrı ayrı şekillere dönüştürür ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Boş bir grup şekli oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Varsayılan şablon stiline sahip yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler, varsayılan şablon stilini uygular. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Yeni bir tablo oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen indeksteki şekli şekil koleksiyonundan kaldırır. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Tüm şekilleri şekil koleksiyonundan kaldırır. |
| [iterator()](#iterator--) | Koleksiyon üzerinde yineleyebilen bir enumerator döndürür. |
| [iteratorJava()](#iteratorJava--) | Tüm koleksiyon için bir java iterator döndürür. |
| [getParentGroup()](#getParentGroup--) | Şekil koleksiyonu için üst grup şekli nesnesini alır. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Tüm elemanları koleksiyondan belirtilen diziye kopyalar. |
| [isSynchronized()](#isSynchronized--) | Koleksiyona erişimin senkronize (thread-safe) olup olmadığını belirten bir değer döndürür. |
| [getSyncRoot()](#getSyncRoot--) | Bir senkronizasyon kökü döndürür. |
### size() {#size--}
```
public final int size()
```

Koleksiyonda gerçekte bulunan eleman sayısını alır. **Salt okunur** int .

**Döndürür:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Belirtilen indeksteki öğeyi alır. **Salt okunur** [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // PPTX dosyasını temsil eden Presentation sınıfını örnekler
>  Presentation pres = new Presentation();
>  try {
>      // İlk slayta erişir
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Varsayılan verileriyle bir grafik ekler
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Grafik başlığını ayarlar
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // İlk serinin değerleri göstermesini ayarlar
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Grafik veri sayfası için indeksi ayarlar
>      int defaultWorksheetIndex = 0;
>      // Grafik veri çalışma sayfasını alır
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Varsayılan oluşturulan serileri ve kategorileri siler
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Yeni seriler ekler
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Yeni kategoriler ekler
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // İlk grafik serisini alır
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Seri verilerini doldurur
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Serinin doldurma rengini ayarlar
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // İkinci grafik serisini alır
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Seri verilerini doldurur
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Serinin doldurma rengini ayarlar
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // İlk etiketi Kategori adını gösterecek şekilde ayarlar
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Üçüncü etiket için serinin değeri göstermesini ayarlar
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // PPTX dosyasını diske kaydeder
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Eklenecek grafiğin türü. |
| x | float | Yeni grafiğin x koordinatı, point cinsinden. |
| y | float | Yeni grafiğin y koordinatı, point cinsinden. |
| width | float | Grafiğin genişliği, point cinsinden. |
| height | float | Grafiğin yüksekliği, point cinsinden. |

**Döndürür:**
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Eklenecek grafiğin türü. |
| x | float | Yeni grafiğin x koordinatı, point cinsinden. |
| y | float | Yeni grafiğin y koordinatı, point cinsinden. |
| width | float | Grafiğin genişliği, point cinsinden. |
| height | float | Grafiğin yüksekliği, point cinsinden. |
| initWithSample | boolean | Yeni grafiği örnek seri verileri ve ayarlarıyla başlatmak için true; serisiz ve sadece minimum ayarlarla oluşturmak ve daha hızlı oluşturmak için false. |

**Döndürür:**
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Yeni bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Aşağıdaki örnek, PowerPoint Sunumunda akıllı şekil eklemenin nasıl yapılacağını gösterir.
>  
  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Diyagram çerçevesinin x koordinatı, point cinsinden. |
| y | float | Diyagram çerçevesinin y koordinatı, point cinsinden. |
| width | float | Diyagram çerçevesinin genişliği, point cinsinden. |
| height | float | Diyagram çerçevesinin yüksekliği, point cinsinden. |
| layoutType | int | SmartArt yerleşim türü. |

**Döndürür:**
[ISmartArt](../../com.aspose.slides/ismartart) - Yeni oluşturulan [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen indekste şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Oluşturulacak grafiğin türü. |
| x | float | Yeni grafiğin x koordinatı, point cinsinden. |
| y | float | Yeni grafiğin y koordinatı, point cinsinden. |
| width | float | Yeni grafiğin genişliği, point cinsinden. |
| height | float | Yeni grafiğin yüksekliği, point cinsinden. |
| index | int | Yeni grafiğin şekil koleksiyonuna ekleneceği sıfır tabanlı indeks. |

**Döndürür:**
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen indekste şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Oluşturulacak grafiğin türü. |
| x | float | Yeni grafiğin x koordinatı, point cinsinden. |
| y | float | Yeni grafiğin y koordinatı, point cinsinden. |
| width | float | Yeni grafiğin genişliği, point cinsinden. |
| height | float | Yeni grafiğin yüksekliği, point cinsinden. |
| index | int | Yeni grafiğin şekil koleksiyonunda ekleneceği sıfır tabanlı indeks. |
| initWithSample | boolean | Yeni grafiği örnek seri verileri ve ayarlarıyla başlatmak için true; serisiz ve sadece minimal ayarlarla oluşturmak için false. |
| x | float | Yeni grafiğin x koordinatı, nokta cinsinden. |
| y | float | Yeni grafiğin y koordinatı, nokta cinsinden. |
| width | float | Yeni grafiğin genişliği, nokta cinsinden. |
| height | float | Yeni grafiğin yüksekliği, nokta cinsinden. |
| index | int | Şekil koleksiyonuna yeni grafiği ekleyeceğiniz sıfır tabanlı indeks. |
| initWithSample | boolean | Yeni grafiği örnek seri verileri ve ayarlarıyla başlatmak için true; seri olmadan ve sadece minimum ayarlarla grafik oluşturmak, böylece oluşturma daha hızlı olur için false. |

**Döndürür:**
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir Zoom nesnesinin bir koleksiyonun sonuna eklenmesini gösterir
>  ("Presentation.pptx" sunusunda en az iki slayt olduğunu varsayarak):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | float | Yeni Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom çerçevesi tarafından başvurulan [ISlide](../../com.aspose.slides/islide); bu sunuma ait olmalıdır. |

**Döndürür:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir Zoom nesnesinin bir koleksiyonun sonuna eklenmesini gösterir
>  ("Presentation.pptx" sunusunda en az iki slayt olduğunu varsayarak):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | float | Yeni Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom çerçevesi tarafından başvurulan [ISlide](../../com.aspose.slides/islide); bu sunuma ait olmalıdır. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Başvurulan slayt [IPPImage](../../com.aspose.slides/ippimage) için görsel. |

**Döndürür:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Yeni bir Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirli bir indeksine Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki slayt olduğunu varsayarak):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom çerçevesi tarafından başvurulan [ISlide](../../com.aspose.slides/islide). |

**Döndürür:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Yeni bir Zoom çerçevesi, önceden tanımlı bir görsel ile oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirli bir indeksine Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki slayt olduğunu varsayarak):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom çerçevesi tarafından başvurulan [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Başvurulan slayt [IPPImage](../../com.aspose.slides/ippimage) için görsel. |

**Döndürür:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Yeni bir Section Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun sonuna Section Zoom nesnesi eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayarak):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | float | Yeni Section Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Section Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Section Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Section Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom çerçevesi tarafından başvurulan [ISection](../../com.aspose.slides/isection); bu sunuma ait olmalı ve en az bir slayt içermelidir. |

**Döndürür:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Yeni bir Section Zoom çerçevesi, önceden tanımlı bir görsel ile oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun sonuna Section Zoom nesnesi eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayarak):
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


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | float | Yeni Section Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Section Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Section Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Section Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom çerçevesi tarafından başvurulan [ISection](../../com.aspose.slides/isection); bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom çerçevesinde görüntülenecek [IPPImage](../../com.aspose.slides/ippimage). |

**Döndürür:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Yeni bir Section Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine Section Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayarak):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Section Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Section Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Section Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Section Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Section Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom çerçevesi tarafından başvurulan [ISection](../../com.aspose.slides/isection); bu sunuma ait olmalı ve en az bir slayt içermelidir. |

**Döndürür:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Yeni bir Section Zoom çerçevesi, önceden tanımlı bir görsel ile oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine Section Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayarak):
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


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Section Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Section Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Section Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Section Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Section Zoom çerçevesinin yüksekliği, nokta cinsinden. |
| section | [ISection](../../com.aspose.slides/isection) | Section Zoom çerçevesi tarafından başvurulan [ISection](../../com.aspose.slides/isection); bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Section Zoom çerçevesinde görüntülenecek görsel. |

**Döndürür:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Yeni bir Summary Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun sonuna Summary Zoom nesnesi eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayarak):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | float | Yeni Summary Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Summary Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Summary Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Summary Zoom çerçevesinin yüksekliği, nokta cinsinden. |

Bu yöntem yeni bir Summary Zoom oluşturur ve bu sunumdaki tüm bölümler için bir nesne koleksiyonu ekler.

**Döndürür:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Yeni oluşturulan [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Yeni bir Summary Zoom çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine Summary Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayarak):
>  
  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | Summary Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Summary Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Summary Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Summary Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Summary Zoom çerçevesinin yüksekliği, nokta cinsinden. |

Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını birleştiren bir Summary Zoom çerçevesi oluşturur.

**Döndürür:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Yeni oluşturulan [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Aşağıdaki örnekler, PowerPoint Sunumu slaytlarına OLE Nesne Çerçeveleri eklemenin nasıl yapılacağını gösterir.
>  
>  // PPTX'yi temsil eden Presentation sınıfını örnekler
>  Presentation pres = new Presentation();
>  try
>  {
>      // İlk slayta erişir
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Cel dosyasını akışa yükler
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
>      // Gömme için veri nesnesi oluşturur
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Bir Ole Nesne Çerçevesi şekli ekler
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //PPTX'yi diske yazar
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | float | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Gömülü OLE verileriyle ilgili bilgi ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Döndürür:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | float | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| className | java.lang.String | OLE nesnesinin sınıf adı. |
| path | java.lang.String | Bağlantılı dosyanın yolu.

Bu yol sunum içinde olduğu gibi kaydedilir. Göreli bir yol belirtilirse, sunum farklı bir dizinden açıldığında dosya erişilemez olur. |

**Döndürür:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, ikinci indekste bir OLE nesnesi eklemeyi gösterir:
>  
  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| index | int | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni OLE çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni OLE çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni OLE çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni OLE çerçevesinin yüksekliği, puan cinsinden. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Gömülü OLE veri bilgisi ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Döndürür:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | OLE nesne çerçevesinin ekleneceği sıfır-bazlı indeks. |
| x | float | Yeni OLE çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni OLE çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni OLE çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni OLE çerçevesinin yüksekliği, puan cinsinden. |
| className | java.lang.String | OLE nesnesinin sınıf adı. |
| path | java.lang.String | Bağlantılı dosyanın yolu. Bu yol sunum içinde olduğu gibi saklanır. Göreli bir yol belirtilirse, sunum farklı bir dizinden açıldığında dosya erişilemez olacaktır. |

**Döndürür:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan OLE nesne çerçevesi.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| fname | java.lang.String | Gömülecek video dosyasının yolu veya adı. |

**Döndürür:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video çerçevesine gömülecek [IVideo](../../com.aspose.slides/ivideo). |

**Döndürür:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Yeni bir video çerçevesi oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Video çerçevesinin ekleneceği sıfır-bazlı indeks. |
| x | float | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| fname | java.lang.String | Gömülecek video dosyasının yolu veya adı. |

**Döndürür:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

CD parçasına bağlanan yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

CD parçasına bağlanan yeni bir ses çerçevesi oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ses çerçevesinin ekleneceği sıfır-bazlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Harici bir ses dosyasına bağlanan yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| fname | java.lang.String | Bağlantı oluşturulacak harici ses dosyasının yolu veya adı. |

**Döndürür:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Harici bir ses dosyasına bağlanan yeni bir ses çerçevesi oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ses çerçevesinin ekleneceği sıfır-bazlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| fname | java.lang.String | Bağlantı oluşturulacak harici ses dosyasının yolu veya adı. |

**Döndürür:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

--------------------

> ```
> Aşağıdaki örnekler Audio Frame oluşturmayı gösterir.
>  
  
>  // Sunum dosyasını temsil eden bir presentation sınıfını örnekler
>  Presentation pres = new Presentation();
>  try {
>      // İlk slaytı alır
>      ISlide sld = pres.getSlides().get_Item(0);
>      // wav ses dosyasını akışa yükler
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Audio Frame'i ekler
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Sesin Çalma Modunu ve Ses Seviyesini ayarlar
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // PowerPoint dosyasını diske yazar
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio_stream | java.io.InputStream | Gömülecek WAV ses verisini içeren giriş akışı. |

**Döndürür:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ses çerçevesinin ekleneceği sıfır-bazlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio_stream | java.io.InputStream | Gömülecek WAV ses verisini içeren giriş akışı. |

**Döndürür:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Ses nesnesi Presentation.Audios listesinden alınır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios koleksiyonundan bir [IAudio](../../com.aspose.slides/iaudio) örneği. |

**Döndürür:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve belirtilen indeks'te şekil koleksiyonuna ekler. Ses nesnesi Presentation.Audios listesinden alınır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ses çerçevesinin ekleneceği sıfır-bazlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios koleksiyonundan gömülecek bir [IAudio](../../com.aspose.slides/iaudio) örneği. |

**Döndürür:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Belirtilen şeklin koleksiyondaki ilk oluşumunun sıfır-bazlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Koleksiyonda aranacak şekil. |

**Döndürür:**  
int - Şekil koleksiyonunda bulunursa ilk oluşumun sıfır-bazlı indeksi; aksi takdirde \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Tüm şekilleri içeren bir dizi oluşturur ve döndürür.

**Döndürür:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) nesnelerinden oluşan bir dizi.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Döndürülecek ilk şeklin indeksi. |
| count | int | Döndürülecek şekil sayısı. |

**Döndürür:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) nesnelerinden oluşan bir dizi.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Belirtilen şekli, şekil koleksiyonunda yeni bir konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Şeklin yerleştirileceği sıfır-bazlı hedef indeks. |
| shape | [IShape](../../com.aspose.slides/ishape) | Koleksiyon içinde taşınacak [IShape](../../com.aspose.slides/ishape). |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Belirtilen şekilleri, şekil koleksiyonunda verilen indeks'ten başlayarak yerleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İlk belirtilen şeklin yerleştirileceği sıfır-bazlı hedef indeks; sonraki şekiller belirtilen sırayla eklenir. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Koleksiyon içinde taşınacak bir veya daha fazla [IShape](../../com.aspose.slides/ishape) örneği. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Yeni bir otomatik şekil oluşturur, varsayılan biçimlendirmeyi uygular ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | Eklenmek istenen otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | float | Şeklin çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | Eklenmek istenen otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | float | Şeklin çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | boolean | Yeni şekle varsayılan şablon stilini (basit stil, ortalanmış metin ve boş olmayan ad) uygulamak için true; tüm özellikleri varsayılan değerlere ayarlayarak şekli oluşturmak için false. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Matematiksel içerik barındıracak yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Aşağıdaki örnek, PowerPoint Sunumuna Matematiksel Denklem eklemenin nasıl yapılacağını gösterir.
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


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | float | Şeklin çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Yeni bir otomatik şekil oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler; varsayılan şablon biçimlendirmesini uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni otomatik şeklin ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | Eklenecek otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | float | Şeklin çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir otomatik şekil oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Otomatik şeklin ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | Eklenecek otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Şeklin çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Şeklin çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Şeklin çerçevesinin genişliği, puan cinsinden. |
| height | float | Şeklin çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | boolean | Varsayılan şablon stilini (boş olmayan ad, basit stil ve ortalanmış metin) uygulamak için true; tüm özellikleri varsayılan değerlerine ayarlayarak şekli oluşturmak için false. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Yeni boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grubun çerçevesi, içine eklenen şekillere otomatik olarak uyum sağlar.

--------------------

> ```
> Aşağıdaki örnek, PowerPoint Sunumu bir slaytına grup şekli eklemenin nasıl yapılacağını gösterir.
>  
  
>  // Presentation sınıfını örnekler
>  Presentation pres = new Presentation();
>  try {
>      // İlk slayta erişir
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Slaytların şekil koleksiyonuna erişir
>      IShapeCollection slideShapes = sld.getShapes();
>      // Slayta bir grup şekli ekler
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Eklenen grup şekli içine şekiller ekler
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Grup şekli çerçevesi ekler
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // PPTX dosyasını diske yazar
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Belirtilen SVG görüntüsünü ayrı şekillere dönüştürür, yeni bir grup şekil oluşturur ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Şekillere dönüştürülecek vektör içeriği barındıran [ISvgImage](../../com.aspose.slides/isvgimage). |
| x | float | Grubun çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Grubun çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Grubun çerçevesinin genişliği, puan cinsinden. |
| height | float | Grubun çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Yeni boş bir grup şekli oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler. Grubun çerçevesi, içine eklenen şekillere otomatik olarak uyum sağlar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Grup şeklinin ekleneceği sıfır-tabanlı indeks. |

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Varsayılan şablon stilini kullanan yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | Eklenmek istenen bağlayıcı şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Bağlayıcının çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Bağlayıcının çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Bağlayıcının çerçevesinin genişliği, puan cinsinden. |
| height | float | Bağlayıcının çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | Oluşturulacak bağlayıcı şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Bağlayıcının çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Bağlayıcının çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Bağlayıcının çerçevesinin genişliği, puan cinsinden. |
| height | float | Bağlayıcının çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | boolean | Varsayılan şablon stilini (boş olmayan ad, basit stil) uygulamak için true; bağlayıcıyı varsayılan özellik değerleriyle oluşturmak için false. |

**Döndürür:**
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Yeni bir bağlayıcı şekil oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler; varsayılan şablon stilini uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Bağlayıcı şeklin ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | Eklenecek bağlayıcı şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Bağlayıcının çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Bağlayıcının çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Bağlayıcının çerçevesinin genişliği, puan cinsinden. |
| height | float | Bağlayıcının çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir bağlayıcı şekil oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Bağlayıcı şeklin ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | Eklenecek bağlayıcı şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Bağlayıcının çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Bağlayıcının çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Bağlayıcının çerçevesinin genişliği, puan cinsinden. |
| height | float | Bağlayıcının çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | boolean | Varsayılan şablon stilini (boş olmayan ad, basit stil) uygulamak için true; bağlayıcıyı varsayılan özellik değerleriyle oluşturmak için false. |

**Döndürür:**
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) içinde bulunan şekil tipini belirtir, aşağıdaki çizgi türleri hariç:

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
| x | float | Resim çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Resim çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Resim çerçevesinin genişliği, puan cinsinden. |
| height | float | Resim çerçevesinin yüksekliği, puan cinsinden. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Resim çerçevesinde gösterilecek [IPPImage](../../com.aspose.slides/ippimage). |

**Döndürür:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Yeni oluşturulan [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Yeni bir resim çerçevesi oluşturur ve belirtilen görüntüyü içerir; ardından çerçeveyi belirtilen indeksde şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Resim çerçevesinin ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) içinde bulunan şekil tipini belirtir, aşağıdaki çizgi türleri hariç:

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
| x | float | Resim çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Resim çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Resim çerçevesinin genişliği, puan cinsinden. |
| height | float | Resim çerçevesinin yüksekliği, puan cinsinden. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Resim çerçevesinde gösterilecek [IPPImage](../../com.aspose.slides/ippimage). |

**Döndürür:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Yeni oluşturulan [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Aşağıdaki örnekler, PowerPoint Sunumuna tablo eklemenin nasıl yapılacağını gösterir.
>  
  
>  // PPTX dosyasını temsil eden Presentation sınıfını oluşturur
>  Presentation pres = new Presentation();
>  try
>  {
>      // İlk slayta erişir
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Sütunları genişlikleriyle ve satırları yükseklikleriyle tanımlar
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Slayta tablo şekli ekler
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Her hücre için kenarlık formatını ayarlar
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
>      // 1. satırdaki 1. ve 2. hücreleri birleştir
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Birleştirilmiş hücreye metin ekler
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // PPTX'yi diske kaydeder
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Tablonun x koordinatı, nokta biriminde. |
| y | float | Tablonun y koordinatı, nokta biriminde. |
| columnWidths | double[] | Tablo sütunlarının genişliklerini temsil eden double dizisi, nokta biriminde. |
| rowHeights | double[] | Tablo satırlarının yüksekliklerini temsil eden double dizisi, nokta biriminde. |

**Döndürür:**
[ITable](../../com.aspose.slides/itable) - Yeni oluşturulan [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```


Yeni bir tablo oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Tablonun ekleneceği sıfır tabanlı dizin. |
| x | float | Tablonun x koordinatı, nokta biriminde. |
| y | float | Tablonun y koordinatı, nokta biriminde. |
| columnWidths | double[] | Tablo sütunlarının genişliklerini temsil eden double dizisi, nokta biriminde. |
| rowHeights | double[] | Tablo satırlarının yüksekliklerini temsil eden double dizisi, nokta biriminde. |

**Döndürür:**
[ITable](../../com.aspose.slides/itable) - Yeni oluşturulan [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Belirtilen dizindeki şekli şekil koleksiyonundan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak şeklin sıfır tabanlı dizini. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```


Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Kaldırılacak [IShape](../../com.aspose.slides/ishape). |

### clear() {#clear--}
```
public final void clear()
```


Şekil koleksiyonundaki tüm şekilleri kaldırır.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```


Koleksiyon içinde yineleme yapan bir enumerator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Koleksiyon içinde yineleme yapmak için kullanılabilen bir IGenericEnumerator.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```


Tüm koleksiyon için bir java iterator döndürür.

**Döndürür:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Tüm koleksiyon için bir java.util.Iterator.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```


Şekiller koleksiyonu için ana grup şekil nesnesini alır. Yalnızca okuma [IGroupShape](../../com.aspose.slides/igroupshape).

**Döndürür:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```java
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```


Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak şekil. |
| x | float | Yeni şeklin çerçevesinin x koordinatı, nokta biriminde. |
| y | float | Yeni şeklin çerçevesinin y koordinatı, nokta biriminde. |
| width | float | Yeni şeklin çerçevesinin genişliği, nokta biriminde. |
| height | float | Yeni şeklin çerçevesinin yüksekliği, nokta biriminde. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```


Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Yeni şekil, sourceShape'ın genişlik ve yüksekliğini korur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak şekil. |
| x | float | Yeni şeklin çerçevesinin x koordinatı, nokta biriminde. |
| y | float | Yeni şeklin çerçevesinin y koordinatı, nokta biriminde. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```


Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Kopyalanan şekil, orijinalin konum ve boyutunu korur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```


Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kopyalanan şeklin ekleneceği sıfır tabanlı dizin. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |
| x | float | Kopyalanan şeklin çerçevesinin x koordinatı, nokta biriminde. |
| y | float | Kopyalanan şeklin çerçevesinin y koordinatı, nokta biriminde. |
| width | float | Kopyalanan şeklin çerçevesinin genişliği, nokta biriminde. |
| height | float | Kopyalanan şeklin çerçevesinin yüksekliği, nokta biriminde. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```


Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. Yeni şekil, sourceShape'ın genişlik ve yüksekliğini korur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kopyalanan şeklin ekleneceği sıfır tabanlı dizin. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |
| x | float | Kopyalanan şeklin çerçevesinin x koordinatı, nokta biriminde. |
| y | float | Kopyalanan şeklin çerçevesinin y koordinatı, nokta biriminde. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```


Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. Kopyalanan şekil, orijinalin konum ve boyutunu korur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kopyalanan şeklin ekleneceği sıfır tabanlı dizin. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Hedef dizi. |
| index | int | Hedef dizideki başlangıç indeksi. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Koleksiyona erişimin senkronize (iş parçacığı güvenli) olup olmadığını gösteren bir değer döndürür. Yalnızca okuma  boolean .

**Döndürür:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Bir senkronizasyon kökü döndürür. Yalnızca okuma  Object .

**Döndürür:**
java.lang.Object