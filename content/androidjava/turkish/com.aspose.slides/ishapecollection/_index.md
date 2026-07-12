---
title: IShapeCollection
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Şekiller koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ishapecollection/
---
**Uygulanan Tüm Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Şekiller koleksiyonunu temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [getParentGroup()](#getParentGroup--) | Şekiller koleksiyonu için üst grup şekil nesnesini alır. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Yeni bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntü ile yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntü ile yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntü ile yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Yeni bir video çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Gömülü bir WAV dosyası ile yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios listesinde mevcut bir ses nesnesi kullanarak yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Gömülü bir WAV dosyası ile yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios listesinde mevcut bir ses nesnesi kullanarak yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Belirtilen şeklin koleksiyondaki ilk oluşumunun sıfır tabanlı indeksini döndürür. |
| [toArray()](#toArray--) | Tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Belirtilen şekli şekil koleksiyonunda yeni bir konuma taşır. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Belirtilen şekilleri şekil koleksiyonunda taşır ve verilen indeksten başlayarak yerleştirir. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Varsayılan biçimlendirme ile yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Matematiksel içeriği barındırmak için yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Yeni bir otomatik şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler; varsayılan şablon biçimlendirmesini uygular. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Yeni bir otomatik şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stilini başlatır. |
| [addGroupShape()](#addGroupShape--) | Boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü ayrı ayrı şekillere dönüştürür ve oluşan grubu şekil koleksiyonunun sonuna ekler. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Boş bir grup şekli oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Varsayılan şablon stilinde yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler; varsayılan şablon stilini uygular. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Yeni bir tablo oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki şekli şekil koleksiyonundan kaldırır. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Şekil koleksiyonundaki tüm şekilleri kaldırır. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Belirtilen dizindeki öğeyi alır. Yalnızca okunabilir [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Dönüş Değeri:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Şekiller koleksiyonu için üst grup şekil nesnesini alır. Yalnızca okunabilir [IGroupShape](../../com.aspose.slides/igroupshape).

**Dönüş Değeri:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Eklenecek grafik türü. |
| x | float | Yeni grafiğin x koordinatı (puan cinsinden). |
| y | float | Yeni grafiğin y koordinatı (puan cinsinden). |
| width | float | Grafiğin genişliği (puan cinsinden). |
| height | float | Grafiğin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Eklenecek grafik türü. |
| x | float | Yeni grafiğin x koordinatı (puan cinsinden). |
| y | float | Yeni grafiğin y koordinatı (puan cinsinden). |
| width | float | Grafiğin genişliği (puan cinsinden). |
| height | float | Grafiğin yüksekliği (puan cinsinden). |
| initWithSample | boolean | True ise yeni grafik örnek seri verileri ve ayarlarıyla başlatılır; false ise grafik, seri olmadan ve yalnızca minimum ayarlarla oluşturulur, bu da oluşturmayı hızlandırır. |

**Dönüş Değeri:**
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Yeni bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler.

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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Diyagram çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Diyagram çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Diyagram çerçevesinin genişliği (puan cinsinden). |
| height | float | Diyagram çerçevesinin yüksekliği (puan cinsinden). |
| layoutType | int | SmartArt yerleşim türü. |

**Dönüş Değeri:**
[ISmartArt](../../com.aspose.slides/ismartart) - Yeni oluşturulan [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Oluşturulacak grafik türü. |
| x | float | Yeni grafiğin x koordinatı (puan cinsinden). |
| y | float | Yeni grafiğin y koordinatı (puan cinsinden). |
| width | float | Yeni grafiğin genişliği (puan cinsinden). |
| height | float | Yeni grafiğin yüksekliği (puan cinsinden). |
| index | int | Yeni grafiğin şekil koleksiyonunda ekleneceği sıfır tabanlı indeks. |

**Dönüş Değeri:**
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Oluşturulacak grafik türü. |
| x | float | Yeni grafiğin x koordinatı (puan cinsinden). |
| y | float | Yeni grafiğin y koordinatı (puan cinsinden). |
| width | float | Yeni grafiğin genişliği (puan cinsinden). |
| height | float | Yeni grafiğin yüksekliği (puan cinsinden). |
| index | int | Yeni grafiğin şekil koleksiyonunda ekleneceği sıfır tabanlı indeks. |
| initWithSample | boolean | True ise yeni grafik örnek seri verileri ve ayarlarıyla başlatılır; false ise grafik, seri olmadan ve yalnızca minimum ayarlarla oluşturulur, bu da oluşturmayı hızlandırır. |

**Dönüş Değeri:**
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni OLE çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni OLE çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni OLE çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni OLE çerçevesinin yüksekliği (puan cinsinden). |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Gömülü OLE veri bilgisi ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Dönüş Değeri:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni OLE çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni OLE çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni OLE çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni OLE çerçevesinin yüksekliği (puan cinsinden). |
| className | java.lang.String | OLE nesnesinin sınıf adı. |
| path | java.lang.String | Bağlantılı dosyanın yolu.

Bu yol sunumda olduğu gibi saklanır. Göreli bir yol belirtilirse, sunum farklı bir dizinden açıldığında dosyaya erişilemez. |

**Dönüş Değeri:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni OLE çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni OLE çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni OLE çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni OLE çerçevesinin yüksekliği (puan cinsinden). |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Gömülü OLE veri bilgisi ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Dönüş Değeri:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni OLE çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni OLE çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni OLE çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni OLE çerçevesinin yüksekliği (puan cinsinden). |
| className | java.lang.String | OLE nesnesinin sınıf adı. |
| path | java.lang.String | Bağlantılı dosyanın yolu.

Bu yol sunumda olduğu gibi saklanır. Göreli bir yol belirtilirse, sunum farklı bir dizinden açıldığında dosyaya erişilemez. |

**Dönüş Değeri:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |
| slide | [ISlide](../../com.aspose.slides/islide) | Yakınlaştırma çerçevesinin referans verdiği [ISlide](../../com.aspose.slides/islide); aynı sunuma ait olmalıdır. |

**Dönüş Değeri:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |
| slide | [ISlide](../../com.aspose.slides/islide) | Yakınlaştırma çerçevesinin referans verdiği [ISlide](../../com.aspose.slides/islide); aynı sunuma ait olmalıdır. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Referans verilen slayt [IPPImage](../../com.aspose.slides/ippimage) için görüntü. |

**Dönüş Değeri:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Yakınlaştırma çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |
| slide | [ISlide](../../com.aspose.slides/islide) | Yakınlaştırma çerçevesinin referans verdiği [ISlide](../../com.aspose.slides/islide). |

**Dönüş Değeri:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Yeni bir Yakınlaştırma çerçevesi, önceden tanımlı bir görüntü ile oluşturulur ve belirtilen dizinde şekil koleksiyonuna eklenir.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki slayt olduğunu varsayın):
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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Yakınlaştırma çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |
| slide | [ISlide](../../com.aspose.slides/islide) | Yakınlaştırma çerçevesinin referans verdiği [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Referans verilen slayt [IPPImage](../../com.aspose.slides/ippimage) için görüntü. |

**Dönüş Değeri:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun sonuna bir Section Zoom nesnesi eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayın):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni Bölüm Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Bölüm Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Bölüm Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Bölüm Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |
| section | [ISection](../../com.aspose.slides/isection) | Yakınlaştırma çerçevesinin referans verdiği [ISection](../../com.aspose.slides/isection); aynı sunuma ait olmalı ve en az bir slayt içermelidir. |

**Dönüş Değeri:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Yeni bir Bölüm Yakınlaştırma çerçevesi, önceden tanımlı bir görüntü ile oluşturulur ve şekil koleksiyonunun sonuna eklenir.

--------------------

> ```
> Bu örnek, bir koleksiyonun sonuna bir Section Zoom nesnesi eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayın):
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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni Bölüm Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Bölüm Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Bölüm Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Bölüm Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |
| section | [ISection](../../com.aspose.slides/isection) | Yakınlaştırma çerçevesinin referans verdiği [ISection](../../com.aspose.slides/isection); aynı sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bölüm Yakınlaştırma çerçevesi içinde gösterilecek [IPPImage](../../com.aspose.slides/ippimage). |

**Dönüş Değeri:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna eklenir.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Section Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayın):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Bölüm Yakınlaştırma çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Bölüm Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Bölüm Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Bölüm Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Bölüm Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |
| section | [ISection](../../com.aspose.slides/isection) | Yakınlaştırma çerçevesinin referans verdiği [ISection](../../com.aspose.slides/isection); aynı sunuma ait olmalı ve en az bir slayt içermelidir. |

**Dönüş Değeri:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Yeni bir Bölüm Yakınlaştırma çerçevesi, önceden tanımlı bir görüntü ile oluşturulur ve belirtilen dizinde şekil koleksiyonuna eklenir.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Section Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayın):
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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Bölüm Yakınlaştırma çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Bölüm Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Bölüm Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Bölüm Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Bölüm Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |
| section | [ISection](../../com.aspose.slides/isection) | Yakınlaştırma çerçevesinin referans verdiği [ISection](../../com.aspose.slides/isection); aynı sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bölüm Yakınlaştırma çerçevesi içinde gösterilecek görüntü. |

**Dönüş Değeri:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni Özet Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Özet Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Özet Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Özet Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |

Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Özet Yakınlaştırma çerçevesi oluşturur. |

**Dönüş Değeri:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Yeni oluşturulan [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Summary Zoom nesnesi oluşturmayı ve eklemeyi gösterir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayın):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Özet Yakınlaştırma çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Özet Yakınlaştırma çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni Özet Yakınlaştırma çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni Özet Yakınlaştırma çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni Özet Yakınlaştırma çerçevesinin yüksekliği (puan cinsinden). |

Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Özet Yakınlaştırma çerçevesi oluşturur. |

**Dönüş Değeri:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Yeni oluşturulan [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni video çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni video çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni video çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni video çerçevesinin yüksekliği (puan cinsinden). |
| fname | java.lang.String | Gömülecek video dosyasının yolu veya adı. |

**Dönüş Değeri:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni video çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni video çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni video çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni video çerçevesinin yüksekliği (puan cinsinden). |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video çerçevesine gömülecek [IVideo](../../com.aspose.slides/ivideo). |

**Dönüş Değeri:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Yeni bir video çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Video çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni video çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni video çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni video çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni video çerçevesinin yüksekliği (puan cinsinden). |
| fname | java.lang.String | Gömülecek video dosyasının yolu veya adı. |

**Dönüş Değeri:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni ses çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni ses çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni ses çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ses çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni ses çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni ses çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni ses çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni ses çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni ses çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni ses çerçevesinin yüksekliği (puan cinsinden). |
| fname | java.lang.String | Bağlantılı harici ses dosyasının yolu veya adı. |

**Dönüş Değeri:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ses çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni ses çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni ses çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni ses çerçevesinin yüksekliği (puan cinsinden). |
| fname | java.lang.String | Bağlantılı harici ses dosyasının yolu veya adı. |

**Dönüş Değeri:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni ses çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni ses çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni ses çerçevesinin yüksekliği (puan cinsinden). |
| audio_stream | java.io.InputStream | Gömülecek WAV ses verisini içeren girdi akışı. |

**Dönüş Değeri:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni ses çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni ses çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni ses çerçevesinin yüksekliği (puan cinsinden). |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios koleksiyonundan bir [IAudio](../../com.aspose.slides/iaudio) örneği. |

**Dönüş Değeri:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ses çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni ses çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni ses çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni ses çerçevesinin yüksekliği (puan cinsinden). |
| audio_stream | java.io.InputStream | Gömülecek WAV ses verisini içeren girdi akışı. |

**Dönüş Değeri:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Ses çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Yeni ses çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Yeni ses çerçevesinin genişliği (puan cinsinden). |
| height | float | Yeni ses çerçevesinin yüksekliği (puan cinsinden). |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios koleksiyonundan gömülecek bir [IAudio](../../com.aspose.slides/iaudio) örneği. |

**Dönüş Değeri:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Koleksiyondaki belirtilen şeklin ilk oluşumunun sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Koleksiyonda bulunacak şekil. |

**Dönüş Değeri:**
int - Şekil koleksiyonunda ilk bulunma durumunda sıfır tabanlı indeks; bulunamazsa \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Tüm şekilleri içeren bir dizi oluşturur ve döndürür.

**Dönüş Değeri:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) nesnelerinden oluşan bir dizi.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Döndürülecek ilk şeklin indeksi. |
| count | int | Döndürülecek şekil sayısı. |

**Dönüş Değeri:**
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) nesnelerinden oluşan bir dizi.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Belirtilen şekli şekil koleksiyonunda yeni bir konuma taşır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Şeklin yerleştirileceği sıfır tabanlı hedef indeks. |
| shape | [IShape](../../com.aspose.slides/ishape) | Koleksiyonda taşınacak [IShape](../../com.aspose.slides/ishape). |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Belirtilen şekilleri şekil koleksiyonunda taşır ve verilen indeksten başlayarak yerleştirir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | İlk belirtilen şeklin yerleştirileceği sıfır tabanlı hedef indeks; sonraki şekiller verilen sırayla eklenir. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Koleksiyonda taşınacak bir veya daha fazla [IShape](../../com.aspose.slides/ishape) örneği. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Varsayılan biçimlendirme ile yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Eklenecek otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Şeklin çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Şeklin çerçevesinin genişliği (puan cinsinden). |
| height | float | Şeklin çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Eklenecek otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Şeklin çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Şeklin çerçevesinin genişliği (puan cinsinden). |
| height | float | Şeklin çerçevesinin yüksekliği (puan cinsinden). |
| createFromTemplate | boolean | True ise yeni şekle varsayılan şablon stili (basit stil, ortalanmış metin, boş olmayan ad) uygulanır; false ise şekil tüm özellikleri varsayılan değerlerle oluşturulur. |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Matematiksel içeriği barındırmak için yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Şeklin çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Şeklin çerçevesinin genişliği (puan cinsinden). |
| height | float | Şeklin çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Yeni bir otomatik şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler; varsayılan şablon biçimlendirmesini uygular.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Otomatik şeklin ekleneceği sıfır tabanlı indeks. |
| shapeType | int | Eklenecek otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Şeklin çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Şeklin çerçevesinin genişliği (puan cinsinden). |
| height | float | Şeklin çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir otomatik şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stilini başlatır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Otomatik şeklin ekleneceği sıfır tabanlı indeks. |
| shapeType | int | Eklenecek otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Şeklin çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Şeklin çerçevesinin genişliği (puan cinsinden). |
| height | float | Şeklin çerçevesinin yüksekliği (puan cinsinden). |
| createFromTemplate | boolean | True ise yeni şekle varsayılan şablon stili (boş olmayan ad, basit stil, ortalanmış metin) uygulanır; false ise şekil tüm özellikleri varsayılan değerlerle oluşturulur. |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grubun çerçevesi, eklenen tüm şekillere otomatik olarak uyum sağlar.

**Dönüş Değeri:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public  abstract  I Group Shape add Group Shape(ISvgImage svgImage, float x, float y, float width, float height)
```

Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü ayrı şekillere dönüştürür ve oluşan grubu şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Vektör içeriği içeren ve şekillere dönüştürülecek [ISvgImage](../../com.aspose.slides/isvgimage). |
| x | float | Grubun çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Grubun çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Grubun çerçevesinin genişliği (puan cinsinden). |
| height | float | Grubun çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Boş bir grup şekli oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Grubun çerçevesi, eklenen tüm şekillere otomatik olarak uyum sağlar.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Grup şeklinin ekleneceği sıfır tabanlı indeks. |

**Dönüş Değeri:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Varsayılan şablon stiliyle yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Eklenecek bağlayıcı şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Bağlayıcının çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Bağlayıcının çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Bağlayıcının çerçevesinin genişliği (puan cinsinden). |
| height | float | Bağlayıcının çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon stili uygulanır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Oluşturulacak bağlayıcı şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Bağlayıcının çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Bağlayıcının çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Bağlayıcının çerçevesinin genişliği (puan cinsinden). |
| height | float | Bağlayıcının çerçevesinin yüksekliği (puan cinsinden). |
| createFromTemplate | boolean | True ise varsayılan şablon stili (boş olmayan ad, basit stil) uygulanır; false ise bağlayıcı varsayılan özellik değerleriyle oluşturulur. |

**Dönüş Değeri:**
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler; varsayılan şablon stilini uygular.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Bağlayıcı şeklin ekleneceği sıfır tabanlı indeks. |
| shapeType | int | Eklenecek bağlayıcı şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Bağlayıcının çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Bağlayıcının çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Bağlayıcının çerçevesinin genişliği (puan cinsinden). |
| height | float | Bağlayıcının çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stili uygulanır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Bağlayıcı şeklin ekleneceği sıfır tabanlı indeks. |
| shapeType | int | Eklenecek bağlayıcı şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Bağlayıcının çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Bağlayıcının çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Bağlayıcının çerçevesinin genişliği (puan cinsinden). |
| height | float | Bağlayıcının çerçevesinin yüksekliği (puan cinsinden). |
| createFromTemplate | boolean | True ise varsayılan şablon stili (boş olmayan ad, basit stil) uygulanır; false ise bağlayıcı varsayılan özellik değerleriyle oluşturulur. |

**Dönüş Değeri:**
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) içinde yer alan şekil türünü belirtir; tüm çizgi türleri dışındadır:

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
| x | float | Resim çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Resim çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Resim çerçevesinin genişliği (puan cinsinden). |
| height | float | Resim çerçevesinin yüksekliği (puan cinsinden). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Çerçevede gösterilecek [IPPImage](../../com.aspose.slides/ippimage). |

**Dönüş Değeri:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Yeni oluşturulan [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public  abstract  IP  picture  frame  insert  picture  frame(int  index,  int  shapeType,  float  x,  float  y,  float  width,  float  height,  IPPImage  image)
```

Belirtilen resmi içeren yeni bir resim çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Resim çerçevesinin ekleneceği sıfır tabanlı indeks. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) içinde yer alan şekil türünü belirtir; tüm çizgi türleri dışındadır:

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
| x | float | Resim çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Resim çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Resim çerçevesinin genişliği (puan cinsinden). |
| height | float | Resim çerçevesinin yüksekliği (puan cinsinden). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Çerçevede gösterilecek [IPPImage](../../com.aspose.slides/ippimage). |

**Dönüş Değeri:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Yeni oluşturulan [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | Tablonun x koordinatı (puan cinsinden). |
| y | float | Tablonun y koordinatı (puan cinsinden). |
| columnWidths | double[] | Tablo sütunlarının genişliklerini temsil eden double dizisi (puan cinsinden). |
| rowHeights | double[] | Tablo satırlarının yüksekliklerini temsil eden double dizisi (puan cinsinden). |

**Dönüş Değeri:**
[ITable](../../com.aspose.slides/itable) - Yeni oluşturulan [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Yeni bir tablo oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Tabloyun ekleneceği sıfır tabanlı indeks. |
| x | float | Tablonun x koordinatı (puan cinsinden). |
| y | float | Tablonun y koordinatı (puan cinsinden). |
| columnWidths | double[] | Tablo sütunlarının genişliklerini temsil eden double dizisi (puan cinsinden). |
| rowHeights | double[] | Tablo satırlarının yüksekliklerini temsil eden double dizisi (puan cinsinden). |

**Dönüş Değeri:**
[ITable](../../com.aspose.slides/itable) - Yeni oluşturulan [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen dizindeki şekli şekil koleksiyonundan kaldırır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Kaldırılacak şeklin sıfır tabanlı indeksi. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Kaldırılacak [IShape](../../com.aspose.slides/ishape). |

### clear() {#clear--}
```
public abstract void clear()
```

Şekil koleksiyonundaki tüm şekilleri kaldırır.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak şekil. |
| x | float | Kopyalanan şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Kopyalanan şeklin çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Kopyalanan şeklin çerçevesinin genişliği (puan cinsinden). |
| height | float | Kopyalanan şeklin çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Yeni şekil, sourceShape’ın genişlik ve yüksekliğini korur.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |
| x | float | Kopyalanan şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Kopyalanan şeklin çerçevesinin y koordinatı (puan cinsinden). |

**Dönüş Değeri:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Kopyalanan şekil, orijinalin konum ve boyutunu korur.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |

**Dönüş Değeri:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Kopyalanan şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |
| x | float | Kopyalanan şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Kopyalanan şeklin çerçevesinin y koordinatı (puan cinsinden). |
| width | float | Kopyalanan şeklin çerçevesinin genişliği (puan cinsinden). |
| height | float | Kopyalanan şeklin çerçevesinin yüksekliği (puan cinsinden). |

**Dönüş Değeri:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Yeni şekil, sourceShape’ın genişlik ve yüksekliğini korur.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Kopyalanan şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |
| x | float | Kopyalanan şeklin çerçevesinin x koordinatı (puan cinsinden). |
| y | float | Kopyalanan şeklin çerçevesinin y koordinatı (puan cinsinden). |

**Dönüş Değeri:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Kopyalanan şekil, orijinalin konum ve boyutunu korur.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Kopyalanan şeklin ekleneceği sıfır tabanlı indeks. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Kopyalanacak [IShape](../../com.aspose.slides/ishape). |

**Dönüş Değeri:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).