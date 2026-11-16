---
title: Presentation
second_title: Aspose.Sildes for .NET API Referansı
description: Microsoft PowerPoint sunumunu temsil eder.
type: docs
weight: 9610
url: /tr/aspose.slides/presentation/
---
## Presentation sınıfı

Microsoft PowerPoint sunumunu temsil eder.

```csharp
public sealed class Presentation : IPresentation
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Presentation](presentation#constructor)() | Bu yapıcı, sıfırdan yeni bir sunum oluşturur. Oluşturulan sunumda bir boş slayt bulunur. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Bu yapıcı, sıfırdan yeni bir sunum oluşturur. Oluşturulan sunumda bir boş slayt bulunur. |
| [Presentation](presentation#constructor_2)(Stream) | Bu yapıcı, mevcut bir Presentation'ı okumanın birincil mekanizmasıdır. |
| [Presentation](presentation#constructor_4)(string) | Bu yapıcı, Presentation içeriğinin okunduğu kaynak dosya yolunu alır. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Bu yapıcı, mevcut bir Presentation'ı okumanın birincil mekanizmasıdır. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Bu yapıcı, Presentation içeriğinin okunduğu kaynak dosya yolunu alır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Sunumdaki tüm özel veri bölümlerini döndürür. Salt okunur [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Sunumdaki tüm gömülü ses dosyalarının koleksiyonunu döndürür. Salt okunur [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Yorum yazarlarının koleksiyonunu döndürür. Salt okunur [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Datetime alanlarının içeriğini değiştirecek tarih ve saati döndürür veya ayarlar. Varsayılan olarak bu Presentation nesnesinin oluşturulma zamanı. Okunur/yazılır DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Sunumun özel verilerini döndürür. Salt okunur [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Şekiller için varsayılan metin stilini döndürür. Salt okunur [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Sunumu imzalamak için kullanılan imzaların koleksiyonunu döndürür. Salt okunur [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Standart ve özel belge özelliklerini içeren DocumentProperties nesnesini döndürür. Salt okunur [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Sunumdaki ilk slayt numarasını temsil eder. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Yazı tipleri yöneticisini döndürür. Salt okunur [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Gerçek HeaderFooter yöneticisini döndürür. Salt okunur [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Tüm sunum slaytlarında (ana, düzen, not slaytlarında değil) bulunan tüm hiperlinklere kolay erişim sağlar. Salt okunur [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Sunumdaki tüm görsellerin koleksiyonunu döndürür. Salt okunur [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Sunumda tanımlı tüm düzen slaytlarının bir listesini döndürür. Salt okunur [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Elirama ana yöneticisini döndürür. Salt okunur [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Not ana yöneticisini döndürür. Salt okunur [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Sunumda tanımlı tüm ana slaytların bir listesini döndürür. Salt okunur [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Ana temayı döndürür. Salt okunur [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Not slaytı boyut nesnesini döndürür. Salt okunur [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Bu sunumun izin yöneticisini alır. Salt okunur [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Sunumda tanımlı tüm slayt bölümlerinin bir listesini döndürür. Salt okunur [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür. Salt okunur [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Sunumda tanımlı tüm slaytların bir listesini döndürür. Salt okunur [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Sunum için slayt gösterisi ayarlarını döndürür. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Slayt boyut nesnesini döndürür. Salt okunur [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Sunumun yüklendiği format hakkında bilgiyi döndürür. Salt okunur [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Sunum makrolarıyla VBA projesini alır veya ayarlar. Okunur/yazılır [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Sunumdaki tüm gömülü video dosyalarının koleksiyonunu döndürür. Salt okunur [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Sunum genel görünüm özelliklerini alır. Salt okunur [`IViewProperties`](../iviewproperties). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Bu Presentation nesnesi tarafından kullanılan tüm kaynakları serbest bırakır. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Bir sunumun tüm slaytları için Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Belirtilen slaytlar için Thumbnail Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Belirtilen boyutta bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Özel ölçekleme ile bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Belirtilen boyutta, belirtilen slaytlar için Thumbnail Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Özel ölçekleme ile belirtilen slaytlar için Thumbnail Image nesnelerini döndürür. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Id ile bir Slide, MasterSlide veya LayoutSlide döndürür. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Tüm slaytlardaki tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | Sunumdaki tüm grafiklerin verilerini kaynak çalışma kitaplarından yeniden yükler. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Düzenli ifadenin tüm eşleşmelerini belirtilen string ile değiştirir. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Bir sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dosya setine kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Bir sunumun tüm slaytlarını belirtilen formatta bir akışa kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Belirtilen slaytları sayfa numarası korunarak belirtilen formatta bir akışa kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Bir sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir akışa kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Belirtilen slaytları sayfa numarası korunarak belirtilen formatta bir dosyaya kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Belirtilen slaytları sayfa numarası korunarak belirtilen formatta bir akışa kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Belirtilen slaytları sayfa numarası korunarak belirtilen formatta bir dosyaya kaydeder. |

### Örnekler

Aşağıdaki örnek, PowerPoint Presentation oluşturmayı gösterir.

```csharp
[C#]
// Sunum dosyasını temsil eden bir Presentation nesnesi oluşturur
using (Presentation presentation = new Presentation())
{
    // İlk slaytı al
    ISlide slide = presentation.Slides[0];
    // Satır tipi bir otomatik şekil ekle
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Sunum dosyasını kaydet.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Aşağıdaki örnek, Presentation'ı açıp kaydetmeyi gösterir.

```csharp
[C#]
// Presentation içinde desteklenen herhangi bir dosyayı yükle, ör. ppt, pptx, odp vb.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Sunum dosyasını kaydet.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Diğer Bağlantılar

* arayüz [IPresentation](../ipresentation)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->