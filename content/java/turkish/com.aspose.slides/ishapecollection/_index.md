---
title: IShapeCollection
second_title: Aspose.Slides için Java API Referansı
description: Şekillerin bir koleksiyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/ishapecollection/
---
**Tüm Uygulanan Arayüzler:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Şekillerin bir koleksiyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Belirtilen dizindeki öğeyi alır. |
| [getParentGroup()](#getParentGroup--) | Şekiller koleksiyonu için üst grup şekil nesnesini alır. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizine şekil koleksiyonuna ekler. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Yeni bir Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Yeni bir Zoom çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntü ile yeni bir Zoom çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Yeni bir Bölüm Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntü ile yeni bir Bölüm Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Yeni bir Bölüm Zoom çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Önceden tanımlı bir görüntü ile yeni bir Bölüm Zoom çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Yeni bir Özet Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Yeni bir Özet Zoom çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Yeni bir video çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Belirtilen şeklin koleksiyondaki ilk oluşumunun sıfır-tabanlı dizinini döndürür. |
| [toArray()](#toArray--) | Tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Belirtilen şekli, şekil koleksiyonu içinde yeni bir konuma taşır. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Belirtilen şekilleri, şekil koleksiyonu içinde verilen dizinden başlayarak yerleştirerek taşır. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Varsayılan biçimlendirme ile yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatabilir. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Matematiksel içeriği barındırmak için yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Yeni bir otomatik şekil oluşturur ve belirtilen dizine şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Yeni bir otomatik şekil oluşturur ve belirtilen dizine şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stiliniyle başlatabilir. |
| [addGroupShape()](#addGroupShape--) | Yeni bir boş grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü bireysel şekillere dönüştürür ve elde edilen grubu şekil koleksiyonunun sonuna ekler. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Yeni bir boş grup şekli oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Varsayılan şablon stiliyle yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizine şekil koleksiyonuna ekler, varsayılan şablon stilini uygular. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizine şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Yeni bir tablo oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [removeAt(int index)](#removeAt-int-) | Belirtilen dizindeki şekli şekil koleksiyonundan kaldırır. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır. |
| [clear()](#clear--) | Şekil koleksiyonundaki tüm şekilleri kaldırır. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Belirtilen dizindeki öğeyi alır. Yalnızca-okunur [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int |  |

**Dönüş:**  
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Şekiller koleksiyonu için üst grup şekil nesnesini alır. Yalnızca-okunur [IGroupShape](../../com.aspose.slides/igroupshape).

**Dönüş:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Eklenecek grafiğin türü. |
| x | float | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | float | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | float | Grafiğin genişliği, puan cinsinden. |
| height | float | Grafiğin yüksekliği, puan cinsinden. |

**Dönüş:**  
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Eklenecek grafiğin türü. |
| x | float | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | float | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | float | Grafiğin genişliği, puan cinsinden. |
| height | float | Grafiğin yüksekliği, puan cinsinden. |
| initWithSample | boolean | Yeni grafiği örnek seri verileri ve ayarlarıyla başlatmak için true; seri olmadan ve yalnızca minimum ayarlarla oluşturmak, böylece oluşturma daha hızlı olur; false. |

**Dönüş:**  
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Örnek:
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Diyagram çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Diyagram çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Diyagram çerçevesinin genişliği, puan cinsinden. |
| height | float | Diyagram çerçevesinin yüksekliği, puan cinsinden. |
| layoutType | int | SmartArt yerleşim türü. |

**Dönüş:**  
[ISmartArt](../../com.aspose.slides/ismartart) - Yeni oluşturulan [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizine şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Oluşturulacak grafiğin türü. |
| x | float | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | float | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | float | Yeni grafiğin genişliği, puan cinsinden. |
| height | float | Yeni grafiğin yüksekliği, puan cinsinden. |
| index | int | Yeni grafiğin şekil koleksiyonuna ekleneceği sıfır-tabanlı dizin. |

**Dönüş:**  
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizine şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | int | Oluşturulacak grafiğin türü. |
| x | float | Yeni grafiğin x koordinatı, puan cinsinden. |
| y | float | Yeni grafiğin y koordinatı, puan cinsinden. |
| width | float | Yeni grafiğin genişliği, puan cinsinden. |
| height | float | Yeni grafiğin yüksekliği, puan cinsinden. |
| index | int | Yeni grafiğin şekil koleksiyonuna ekleneceği sıfır-tabanlı dizin. |
| initWithSample | boolean | Yeni grafiği örnek seri verileri ve ayarlarıyla başlatmak için true; seri olmadan ve yalnızca minimum ayarlarla oluşturmak, böylece oluşturma daha hızlı olur; false. |
| initWithSample | boolean | True yeni çizelgeyi örnek seri verileri ve ayarlarıyla başlatmak için; false çizelgeyi serisiz ve yalnızca minimal ayarlarla oluşturur, bu da oluşturmayı hızlandırır. |
**Döndürür:**  
[IChart](../../com.aspose.slides/ichart) - Yeni oluşturulan [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Gömülü OLE veri bilgisi ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Döndürür:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| className | java.lang.String | OLE nesnesinin sınıf adı. |
| path | java.lang.String | Bağlantılı dosyanın yolu.  

Bu yol sunum içinde olduğu gibi saklanır. Göreli bir yol belirtilirse, dosya sunumu farklı bir dizinden açarken erişilemez olur. |

**Döndürür:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Gömülü OLE veri bilgisi ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Döndürür:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | OLE nesne çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni OLE çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni OLE çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni OLE çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni OLE çerçevesinin yüksekliği, nokta cinsinden. |
| className | java.lang.String | OLE nesnesinin sınıf adı. |
| path | java.lang.String | Bağlantılı dosyanın yolu.  

Bu yol sunum içinde olduğu gibi saklanır. Göreli bir yol belirtilirse, dosya sunumu farklı bir dizinden açarken erişilemez olur. |

**Döndürür:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Yeni oluşturulan [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir Zoom nesnesinin koleksiyonun sonuna eklenmesini göstermektedir
>  ("Presentation.pptx" sunumunda en az iki slayt olduğunu varsayalım):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom çerçevesi tarafından referans edilen [ISlide](../../com.aspose.slides/islide); bu sunuma ait olmalıdır. |

**Döndürür:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir Zoom nesnesinin koleksiyonun sonuna eklenmesini göstermektedir
>  ("Presentation.pptx" sunumunda en az iki slayt olduğunu varsayalım):
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom çerçevesi tarafından referans edilen [ISlide](../../com.aspose.slides/islide); bu sunuma ait olmalıdır. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Referans verilen [IPPImage](../../com.aspose.slides/ippimage) slaytı için görüntü. |

**Döndürür:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Zoom nesnesi oluşturup eklemeyi göstermektedir
>  ("Presentation.pptx" sunumunda en az iki slayt olduğunu varsayalım):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom çerçevesi tarafından referans edilen [ISlide](../../com.aspose.slides/islide). |

**Döndürür:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Yeni bir Yakınlaştırma çerçevesi, önceden tanımlı bir görüntü ile oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Zoom nesnesi oluşturup eklemeyi göstermektedir
>  ("Presentation.pptx" sunumunda en az iki slayt olduğunu varsayalım):
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Zoom çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zoom çerçevesi tarafından referans edilen [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Referans verilen [IPPImage](../../com.aspose.slides/ippimage) slaytı için görüntü. |

**Döndürür:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - Yeni oluşturulan [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir Section Zoom nesnesinin koleksiyonun sonuna eklenmesini göstermektedir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayalım):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni Bölüm Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Bölüm Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Bölüm Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Bölüm Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
| section | [ISection](../../com.aspose.slides/isection) | Bölüm Yakınlaştırma çerçevesi tarafından referans edilen [ISection](../../com.aspose.slides/isection); bu sunuma ait olmalı ve en az bir slayt içermelidir. |

**Döndürür:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Yeni bir Bölüm Yakınlaştırma çerçevesi, önceden tanımlı bir görüntü ile oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir Section Zoom nesnesinin koleksiyonun sonuna eklenmesini göstermektedir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayalım):
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni Bölüm Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Bölüm Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Bölüm Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Bölüm Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
| section | [ISection](../../com.aspose.slides/isection) | Bölüm Yakınlaştırma çerçevesi tarafından referans edilen [ISection](../../com.aspose.slides/isection); bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bölüm Yakınlaştırma çerçevesi içinde gösterilecek [IPPImage](../../com.aspose.slides/ippimage). |

**Döndürür:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Section Zoom nesnesi oluşturup eklemeyi göstermektedir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayalım):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Bölüm Yakınlaştırma çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Bölüm Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Bölüm Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Bölüm Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Bölüm Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
| section | [ISection](../../com.aspose.slides/isection) | Bölüm Yakınlaştırma çerçevesi tarafından referans edilen [ISection](../../com.aspose.slides/isection); bu sunuma ait olmalı ve en az bir slayt içermelidir. |

**Döndürür:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Yeni bir Bölüm Yakınlaştırma çerçevesi, önceden tanımlı bir görüntü ile oluşturur ve belirtilen indekste şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Section Zoom nesnesi oluşturup eklemeyi göstermektedir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayalım):
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


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Bölüm Yakınlaştırma çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | float | Yeni Bölüm Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Bölüm Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Bölüm Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Bölüm Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
| section | [ISection](../../com.aspose.slides/isection) | Bölüm Yakınlaştırma çerçevesi tarafından referans edilen [ISection](../../com.aspose.slides/isection); bu sunuma ait olmalı ve en az bir slayt içermelidir. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Bölüm Yakınlaştırma çerçevesi içinde gösterilecek görüntü. |

**Döndürür:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Yeni oluşturulan [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Bu örnek, bir Summary Zoom nesnesinin koleksiyonun sonuna eklenmesini göstermektedir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayalım):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni Özet Yakınlaştırma çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Yeni Özet Yakınlaştırma çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Yeni Özet Yakınlaştırma çerçevesinin genişliği, nokta cinsinden. |
| height | float | Yeni Özet Yakınlaştırma çerçevesinin yüksekliği, nokta cinsinden. |
Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Summary Zoom frame oluşturur. |

**Dönüş:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Yeni oluşturulan [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Yeni bir Summary Zoom frame oluşturur ve belirtilen konumda şekil koleksiyonuna ekler.

--------------------

> ```
> Bu örnek, bir koleksiyonun belirtilen indeksine bir Summary Zoom nesnesi oluşturup eklemeyi göstermektedir
>  ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayalım):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Summary Zoom frame'i eklemek için kullanılan sıfır tabanlı indeks. |
| x | float | Yeni Summary Zoom frame'in x koordinatı, puan cinsinden. |
| y | float | Yeni Summary Zoom frame'in y koordinatı, puan cinsinden. |
| width | float | Yeni Summary Zoom frame'in genişliği, puan cinsinden. |
| height | float | Yeni Summary Zoom frame'in yüksekliği, puan cinsinden. |

--------------------

Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Summary Zoom frame oluşturur. |

**Dönüş:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Yeni oluşturulan [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| fname | java.lang.String | Gömülecek video dosyasının yolu ya da adı. |

**Dönüş:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
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

**Dönüş:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Yeni bir video çerçevesi oluşturur ve belirtilen konumda şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Video çerçevesini eklemek için kullanılan sıfır tabanlı indeks. |
| x | float | Yeni video çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni video çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni video çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni video çerçevesinin yüksekliği, puan cinsinden. |
| fname | java.lang.String | Gömülecek video dosyasının yolu ya da adı. |

**Dönüş:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Yeni oluşturulan [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Yeni bir CD parçasına bağlı ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |

**Dönüş:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Yeni bir CD parçasına bağlı ses çerçevesi oluşturur ve belirtilen konumda şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ses çerçevesini eklemek için kullanılan sıfır tabanlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |

**Dönüş:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Yeni bir dış ses dosyasına bağlı ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| fname | java.lang.String | Bağlantı oluşturulacak dış ses dosyasının yolu ya da adı. |

**Dönüş:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Yeni bir dış ses dosyasına bağlı ses çerçevesi oluşturur ve belirtilen konumda şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ses çerçevesini eklemek için kullanılan sıfır tabanlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| fname | java.lang.String | Bağlantı oluşturulacak dış ses dosyasının yolu ya da adı. |

**Dönüş:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Yeni bir ses çerçevesi oluşturur, gömülü bir WAV dosyası ekler ve şekil koleksiyonunun sonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio_stream | java.io.InputStream | Gömülecek WAV ses verisini içeren giriş akışı. |

**Dönüş:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Presentation.Audios koleksiyonundaki bir [IAudio](../../com.aspose.slides/iaudio) örneği. |

**Dönüş:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen konumda şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ses çerçevesini eklemek için kullanılan sıfır tabanlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio_stream | java.io.InputStream | Gömülecek WAV ses verisini içeren giriş akışı. |

**Dönüş:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve belirtilen konumda şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Ses çerçevesini eklemek için kullanılan sıfır tabanlı indeks. |
| x | float | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | float | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Gömülecek Presentation.Audios koleksiyonundaki bir [IAudio](../../com.aspose.slides/iaudio) örneği. |

**Dönüş:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Yeni oluşturulan [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Belirtilen şeklin koleksiyondaki ilk oluşumunun sıfır tabanlı indeksini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Koleksiyonda bulunacak şekil. |

**Dönüş:**  
int - Şekil koleksiyonunda bulunursa shape'in ilk oluşumunun sıfır tabanlı indeksi; bulunamazsa \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Tüm şekilleri içeren bir dizi oluşturur ve döndürür.

**Dönüş:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) nesnelerinden oluşan bir dizi.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| startIndex | int | Döndürülecek ilk şeklin indeksi. |
| count | int | Döndürülecek şekil sayısı. |

**Dönüş:**  
com.aspose.slides.IShape[] - [IShape](../../com.aspose.slides/ishape) nesnelerinden oluşan bir dizi.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Belirtilen şekli, şekil koleksiyonunda yeni bir konuma taşır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Şeklin yerleştirileceği sıfır tabanlı hedef indeks. |
| shape | [IShape](../../com.aspose.slides/ishape) | Koleksiyon içinde taşınacak [IShape](../../com.aspose.slides/ishape). |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Belirtilen şekilleri, şekil koleksiyonunda verilen indeksten başlayarak taşıyarak yerleştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | İlk belirtilen şeklin yerleştirileceği sıfır tabanlı hedef indeks; sonraki şekiller verilen sırayla izler. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Koleksiyon içinde taşınacak bir veya daha fazla [IShape](../../com.aspose.slides/ishape) örneği. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Varsayılan biçimlendirmeye sahip yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | Eklenmek istenen otomatik şeklin [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | shape'in çerçevesinin x koordinatı, puan cinsinden. |
| y | float | shape'in çerçevesinin y koordinatı, puan cinsinden. |
| width | float | shape'in çerçevesinin genişliği, puan cinsinden. |
| height | float | shape'in çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).  

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}  
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir auto shape oluşturur ve shape koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | Eklenecek auto shape'in [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | shape'in çerçevesinin x koordinatı, puan cinsinden. |
| y | float | shape'in çerçevesinin y koordinatı, puan cinsinden. |
| width | float | shape'in çerçevesinin genişliği, puan cinsinden. |
| height | float | shape'in çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | boolean | Yeni shape'e varsayılan şablon stillerini (basit stil, ortalanmış metin ve boş olmayan ad) uygulamak için true; tüm özellikler varsayılan değerlerine ayarlanmış olarak oluşturmak için false. |

**Döndürür:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).  

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}  
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Matematiksel içeriği barındıracak yeni bir dikdörtgen auto shape oluşturur ve shape koleksiyonunun sonuna ekler.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | shape'in çerçevesinin x koordinatı, puan cinsinden. |
| y | float | shape'in çerçevesinin y koordinatı, puan cinsinden. |
| width | float | shape'in çerçevesinin genişliği, puan cinsinden. |
| height | float | shape'in çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}  
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Yeni bir auto shape oluşturur ve belirtilen konumda shape koleksiyonuna ekler, varsayılan şablon biçimlendirmesi uygulanır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Yeni auto shape'in ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | Eklenecek auto shape'in [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | shape'in çerçevesinin x koordinatı, puan cinsinden. |
| y | float | shape'in çerçevesinin y koordinatı, puan cinsinden. |
| width | float | shape'in çerçevesinin genişliği, puan cinsinden. |
| height | float | shape'in çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}  
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir auto shape oluşturur ve belirtilen konumda shape koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilleriyle başlatır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Auto shape'in ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | Eklenecek auto shape'in [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | shape'in çerçevesinin x koordinatı, puan cinsinden. |
| y | float | shape'in çerçevesinin y koordinatı, puan cinsinden. |
| width | float | shape'in çerçevesinin genişliği, puan cinsinden. |
| height | float | shape'in çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | boolean | Varsayılan şablon stilini (boş olmayan ad, basit stil ve ortalanmış metin) uygulamak için true; tüm özellikler varsayılan değerlerine ayarlanmış olarak oluşturmak için false. |

**Döndürür:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Yeni oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape).  

### addGroupShape() {#addGroupShape--}  
```
public abstract IGroupShape addGroupShape()
```

Yeni boş bir grup shape oluşturur ve shape koleksiyonunun sonuna ekler. Grubun çerçevesi, içine eklenen shape'lere göre otomatik olarak ayarlanır.

**Döndürür:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).  

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}  
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Yeni bir grup shape oluşturur, belirtilen SVG görüntüyü ayrı ayrı shape'lere dönüştürür ve oluşan grup shape'i shape koleksiyonunun sonuna ekler.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Shape'lere dönüştürülecek vektör içeriğini barındıran [ISvgImage](../../com.aspose.slides/isvgimage). |
| x | float | Grubun çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Grubun çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Grubun çerçevesinin genişliği, puan cinsinden. |
| height | float | Grubun çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).  

### insertGroupShape(int index) {#insertGroupShape-int-}  
```
public abstract IGroupShape insertGroupShape(int index)
```

Yeni boş bir grup shape oluşturur ve belirtilen konumda shape koleksiyonuna ekler. Grubun çerçevesi, içine eklenen shape'lere göre otomatik olarak ayarlanır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Grup shape'in ekleneceği sıfır-tabanlı indeks. |

**Döndürür:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - Yeni oluşturulan [IGroupShape](../../com.aspose.slides/igroupshape).  

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}  
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Yeni bir connector shape oluşturur, varsayılan şablon stilini uygular ve shape koleksiyonunun sonuna ekler.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | Eklenecek connector shape'in [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Connector'ın çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Connector'ın çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Connector'ın çerçevesinin genişliği, puan cinsinden. |
| height | float | Connector'ın çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**  
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).  

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}  
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir connector shape oluşturur ve shape koleksiyonunun sonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | Oluşturulacak connector shape'in [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Connector'ın çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Connector'ın çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Connector'ın çerçevesinin genişliği, puan cinsinden. |
| height | float | Connector'ın çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | boolean | Varsayılan şablon stilini (boş olmayan ad, basit stil) uygulamak için true; connector'ı varsayılan özellik değerleriyle oluşturmak için false. |

**Döndürür:**  
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).  

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}  
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Yeni bir connector shape oluşturur ve belirtilen konumda shape koleksiyonuna ekler, varsayılan şablon stili uygulanır.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Connector shape'in ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | Eklenecek connector shape'in [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Connector'ın çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Connector'ın çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Connector'ın çerçevesinin genişliği, puan cinsinden. |
| height | float | Connector'ın çerçevesinin yüksekliği, puan cinsinden. |

**Döndürür:**  
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).  

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}  
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Yeni bir connector shape oluşturur ve belirtilen konumda shape koleksiyonuna ekler, isteğe bağlı olarak varsayılan şablon stilini uygular.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Connector shape'in ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | Eklenecek connector shape'in [ShapeType](../../com.aspose.slides/shapetype). |
| x | float | Connector'ın çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Connector'ın çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Connector'ın çerçevesinin genişliği, puan cinsinden. |
| height | float | Connector'ın çerçevesinin yüksekliği, puan cinsinden. |
| createFromTemplate | boolean | Varsayılan şablon stilini (boş olmayan ad, basit stil) uygulamak için true; connector'ı varsayılan özellik değerleriyle oluşturmak için false. |

**Döndürür:**  
[IConnector](../../com.aspose.slides/iconnector) - Yeni oluşturulan [IConnector](../../com.aspose.slides/iconnector).  

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}  
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Belirtilen görseli içeren yeni bir picture frame oluşturur ve shape koleksiyonunun sonuna ekler.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) içinde bulunacak shape tipini belirtir; aşağıdaki çizgi tipleri hariç: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Picture frame'in çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Picture frame'in çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Picture frame'in çerçevesinin genişliği, puan cinsinden. |
| height | float | Picture frame'in çerçevesinin yüksekliği, puan cinsinden. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Picture frame içinde gösterilecek [IPPImage](../../com.aspose.slides/ippimage). |

**Döndürür:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Yeni oluşturulan [IPictureFrame](../../com.aspose.slides/ipictureframe).  

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}  
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Yeni bir picture frame oluşturur, belirtilen görseli içerir ve picture frame'i belirtilen konumda shape koleksiyonuna ekler.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Picture frame'in ekleneceği sıfır-tabanlı indeks. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) içinde bulunacak shape tipini belirtir; aşağıdaki çizgi tipleri hariç: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | Picture frame'in çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Picture frame'in çerçevesinin y koordinatı, puan cinsinden. |
| width | float | Picture frame'in çerçevesinin genişliği, puan cinsinden. |
| height | float | Picture frame'in çerçevesinin yüksekliği, puan cinsinden. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Picture frame içinde gösterilecek [IPPImage](../../com.aspose.slides/ippimage). |

**Döndürür:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Yeni oluşturulan [IPictureFrame](../../com.aspose.slides/ipictureframe).  

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}  
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Yeni bir tablo oluşturur ve shape koleksiyonunun sonuna ekler.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Tablonun çerçevesinin x koordinatı, puan cinsinden. |
| y | float | Tablonun çerçevesinin y koordinatı, puan cinsinden. |
| columnWidths | double[] | Tablo sütunlarının genişliklerini puan cinsinden belirten double dizisi. |
| rowHeights | double[] | Tablo satırlarının yüksekliklerini puan cinsinden belirten double dizisi. |

**Döndürür:**  
[ITable](../../com.aspose.slides/itable) - Yeni oluşturulan [ITable](../../com.aspose.slides/itable).  

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}  
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Yeni bir tablo oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Tabloyu ekleyeceğiniz sıfır tabanlı indeks. |
| x | float | Tablonun x koordinatı, nokta cinsinden. |
| y | float | Tablonun y koordinatı, nokta cinsinden. |
| columnWidths | double[] | Tablo sütunlarının genişliklerini temsil eden double dizisi, nokta cinsinden. |
| rowHeights | double[] | Tablo satırlarının yüksekliklerini temsil eden double dizisi, nokta cinsinden. |

**Döndürür:**
[ITable](../../com.aspose.slides/itable) - Yeni oluşturulan [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Belirtilen dizindeki şekli şekil koleksiyonundan kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Kaldırılacak şeklin sıfır tabanlı dizini. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır.

**Parametreler:**
| Parametre | Tür | Açıklama |
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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Klonlanacak şekil. |
| x | float | Klonlanmış şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Klonlanmış şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Klonlanmış şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | float | Klonlanmış şeklin çerçevesinin yüksekliği, nokta cinsinden. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Yeni şekil, sourceShape'in genişliğini ve yüksekliğini korur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Klonlanacak [IShape](../../com.aspose.slides/ishape). |
| x | float | Klonlanmış şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Klonlanmış şeklin çerçevesinin y koordinatı, nokta cinsinden. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Klonlanan şekil, orijinalin konumunu ve boyutunu korur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Klonlanacak [IShape](../../com.aspose.slides/ishape). |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Klonlanmış şeklin ekleneceği sıfır tabanlı dizin. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Klonlanacak [IShape](../../com.aspose.slides/ishape). |
| x | float | Klonlanmış şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Klonlanmış şeklin çerçevesinin y koordinatı, nokta cinsinden. |
| width | float | Klonlanmış şeklin çerçevesinin genişliği, nokta cinsinden. |
| height | float | Klonlanmış şeklin çerçevesinin yüksekliği, nokta cinsinden. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Yeni şekil, sourceShape'in genişliğini ve yüksekliğini korur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Klonlanmış şeklin ekleneceği sıfır tabanlı dizin. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Klonlanacak [IShape](../../com.aspose.slides/ishape). |
| x | float | Klonlanmış şeklin çerçevesinin x koordinatı, nokta cinsinden. |
| y | float | Klonlanmış şeklin çerçevesinin y koordinatı, nokta cinsinden. |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler. Klonlanan şekil, orijinalin konumunu ve boyutunu korur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Klonlanmış şeklin ekleneceği sıfır tabanlı dizin. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Klonlanacak [IShape](../../com.aspose.slides/ishape). |

**Döndürür:**
[IShape](../../com.aspose.slides/ishape) - Yeni oluşturulan [IShape](../../com.aspose.slides/ishape).