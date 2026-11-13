---
title: ShapeCollection
second_title: Aspose.Sildes için .NET API Referansı
description: Şekillerin bir koleksiyonunu temsil eder.
type: docs
weight: 9880
url: /tr/aspose.slides/shapecollection/
---
## ShapeCollection sınıfı

Şekillerin bir koleksiyonunu temsil eder.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Koleksiyon içinde gerçekte bulunan öğe sayısını alır. Salt-okunur Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Koleksiyona erişimin senkronize (çoklu iş parçacıklı) olup olmadığını belirten bir değer döndürür. Salt-okunur Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Belirtilen indeksteki öğeyi alır. Salt-okunur [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Şekiller koleksiyonu için ana grup şekil nesnesini alır. Salt-okunur [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Bir senkronizasyon kökü döndürür. Salt-okunur Object. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Yeni bir ses çerçevesi oluşturur, CD parçasına bağlar ve şekil koleksiyonunun sonuna ekler. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak şekil koleksiyonunun sonuna ekler. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Varsayılan biçimlendirmeye sahip yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Yeni bir otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon biçimlendirmesiyle başlatılabilir. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve şekil koleksiyonunun sonuna ekler. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Kopyalanan şekil, orijinalin konumunu ve boyutunu korur. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. Yeni şekil, *sourceShape*'in genişlik ve yüksekliğini korur. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Belirtilen şeklin bir kopyasını oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Varsayılan şablon stiline sahip yeni bir bağlayıcı şekli oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Yeni bir bağlayıcı şekil oluşturur ve şekil koleksiyonunun sonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Yeni boş bir grup şekli oluşturur ve şekil koleksiyonunun sonuna ekler. Grup çerçevesi, eklenen şekillere otomatik olarak uyum sağlayacak şekilde ayarlanır. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Yeni bir grup şekli oluşturur, belirtilen SVG görüntüyü ayrı ayrı şekillere dönüştürür ve ortaya çıkan grubu şekil koleksiyonunun sonuna ekler. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Matematiksel içeriği barındırmak üzere yeni bir dikdörtgen otomatik şekil oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Yeni bir OLE nesne çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Önceden tanımlı bir görüntüyle yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Yeni bir tablo oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Yeni bir video çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Şekil koleksiyonundaki tüm şekilleri kaldırır. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Koleksiyondaki tüm öğeleri belirtilen diziye kopyalar. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Koleksiyon içinde döngü yapan bir yineleyici döndürür. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Koleksiyonda belirtilen şeklin ilk oluşumunun sıfır tabanlı indeksini döndürür. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Yeni bir ses çerçevesi oluşturur, CD parçasına bağlar ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Harici bir ses dosyasına bağlı yeni bir ses çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Yeni bir otomatik şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler; varsayılan şablon biçimlendirmesini uygular. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Yeni bir otomatik şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stilini başlatır. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Yeni bir grafik oluşturur, örnek seri verileri ve ayarlarıyla başlatır ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. Kopyalanan şekil, orijinalin konumunu ve boyutunu korur. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. Yeni şekil, *sourceShape*'in genişlik ve yüksekliğini korur. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Belirtilen şeklin bir kopyasını oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler; varsayılan şablon stilini uygular. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Yeni bir bağlayıcı şekil oluşturur ve belirtilen indekste şekil koleksiyonuna ekler; isteğe bağlı olarak varsayılan şablon stilini uygular. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Yeni boş bir grup şekli oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. Grup çerçevesi, eklenen şekillere otomatik olarak uyum sağlayacak şekilde ayarlanır. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Yeni bir OLE nesne çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Belirtilen görüntüyü içeren yeni bir resim çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Önceden tanımlı bir görüntüyle yeni bir Bölüm Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Yeni bir Özet Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Yeni bir tablo oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Yeni bir video çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Önceden tanımlı bir görüntüyle yeni bir Yakınlaştırma çerçevesi oluşturur ve belirtilen indekste şekil koleksiyonuna ekler. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Belirtilen şeklin koleksiyondaki ilk oluşumunu kaldırır. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Belirtilen indeksteki şekli koleksiyondan kaldırır. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Belirtilen şekli koleksiyon içinde yeni bir konuma taşır. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Belirtilen şekilleri koleksiyon içinde taşır, verilen indeksden itibaren yerleştirir. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Tüm şekilleri içeren bir dizi oluşturur ve döndürür. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Belirtilen aralıktaki tüm şekilleri içeren bir dizi oluşturur ve döndürür. |

### Ayrıca Bakınız

* sınıf [DomObject&lt;TParent&gt;](../domobject-1)
* sınıf [GroupShape](../groupshape)
* arayüz [IShapeCollection](../ishapecollection)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->