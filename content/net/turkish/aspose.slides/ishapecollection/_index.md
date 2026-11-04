---
title: IShapeCollection
second_title: Aspose.Sildes için .NET API Referansı
description: Şekiller koleksiyonunu temsil eder.
type: docs
weight: 7000
url: /tr/aspose.slides/ishapecollection/
---
## IShapeCollection arayüzü

Şekiller koleksiyonunu temsil eder.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Belirtilen dizindeki öğeyi alır. Yalnızca okuma [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Şekiller koleksiyonunun üst grup şekli nesnesini alır. Yalnızca okuma [`IGroupShape`](../igroupshape). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Bir CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak şekil koleksiyonunun sonuna ekler. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Varsayılan biçimlendirme ile yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatılabilir. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Kopyalanan şekil, orijinalin konum ve boyutunu korur. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Yeni şekil, *sourceShape*'in genişlik ve yüksekliğini korur. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Varsayılan şablon stilinde yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon stili uygulanabilir. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Yeni bir boş grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grubun çerçevesi, eklenen şekillere otomatik olarak uyum sağlayacak şekilde ayarlanır. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Yeni bir grup şekli oluşturur, belirtilen SVG görüntüsünü ayrı ayrı şekillere dönüştürür ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Matematiksel içerik barındırmak için yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Önceden tanımlı bir görüntü ile yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Yeni bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Şekil koleksiyonundaki tüm şekilleri kaldırır. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Belirtilen şeklin koleksiyondaki ilk oluşumunun sıfır tabanlı dizinini döndürür. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Bir CD parçasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Yeni bir otomatik şekil oluşturur ve belirtilen dizine şekil koleksiyonuna ekler, varsayılan şablon biçimlendirmesini uygular. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Yeni bir otomatik şekil oluşturur ve belirtilen dizine şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stiliyle başlatılabilir. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. Kopyalanan şekil, orijinalin konum ve boyutunu korur. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. Yeni şekil, *sourceShape*'in genişlik ve yüksekliğini korur. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizine şekil koleksiyonuna ekler, varsayılan şablon stilini uygular. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen dizine şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stili uygulanabilir. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Yeni bir boş grup şekli oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. Grubun çerçevesi, eklenen şekillere otomatik olarak uyum sağlayacak şekilde ayarlanır. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Önceden tanımlı bir görüntü ile yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Yeni bir tablo oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Yeni bir video çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Önceden tanımlı bir görüntü ile yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen dizine şekil koleksiyonuna ekler. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Belirtilen şeklin grup koleksiyonundaki ilk oluşumunu kaldırır. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Belirtilen dizindeki şekli grup koleksiyonundan kaldırır. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Belirtilen şekli grup koleksiyonunda yeni bir konuma taşır. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Belirtilen şekilleri grup koleksiyonunda taşır, verilen dizinden başlayarak yerleştirir. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür. |

### Bakınız

* arayüz [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* arayüz [IShape](../ishape)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->