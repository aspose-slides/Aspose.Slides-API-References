---
title: IPresentation
second_title: Aspose.Sildes için .NET API Referansı
description: Sunum belgesi
type: docs
weight: 6750
url: /tr/aspose.slides/ipresentation/
---
## IPresentation arayüz

Sunum belgesi

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Sunum içindeki tüm özel veri bölümlerini döndürür. Salt okunur [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | IDisposable arabirimini döndürür. Salt okunur IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimini almayı sağlar. Salt okunur [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Sunumdaki tüm gömülü ses dosyalarının koleksiyonunu döndürür. Salt okunur [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Yorum yazarlarının koleksiyonunu döndürür. Salt okunur [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Tarih ve saat alanının içeriğini değiştirecek tarih ve saati döndürür veya ayarlar. Varsayılan olarak bu Presentation nesnesinin oluşturulma zamanı. Okunur/yazılır DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Sunumun özel verilerini döndürür. Salt okunur [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Şekiller için varsayılan metin stilini döndürür. Salt okunur [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Sunumu imzalamak için kullanılan imzaların koleksiyonunu döndürür. Salt okunur [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Standart ve özel belge özelliklerini içeren DocumentProperties nesnesini döndürür. Salt okunur [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Sunumdaki ilk slayt numarasını temsil eder. Okunur/yazılır Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Yazı tipleri yöneticisini döndürür. Salt okunur [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Sunumun HeaderFooter yöneticisini döndürür. Salt okunur [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Tüm sunum slaytlarında (master, düzen, not slaytları hariç) bulunan tüm köprülerin kolay erişimini sağlar. Salt okunur [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Sunumdaki tüm görsellerin koleksiyonunu döndürür. Salt okunur [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Sunumda tanımlı tüm düzen slaytlarının listesini döndürür. Salt okunur [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | El kitapçığı master yöneticisini döndürür. Salt okunur [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Not master yöneticisini döndürür. Salt okunur [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Sunumda tanımlı tüm master slaytlarının listesini döndürür. Salt okunur [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Sunumun master temasını döndürür. Salt okunur [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Not slayt boyut nesnesini döndürür. Salt okunur [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Bu sunum için izin yöneticisini alır. Salt okunur [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Sunumda tanımlı tüm slayt bölümlerinin listesini döndürür. Salt okunur [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Sunum belgesine uygulanan duyarlılık etiketlerinin koleksiyonunu döndürür. Salt okunur [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Sunumda tanımlı tüm slaytların listesini döndürür. Salt okunur [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Slayt boyut nesnesini döndürür. Salt okunur [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Sunumun yüklendiği format hakkında bilgi döndürür. Salt okunur [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Sunum makrolarıyla VBA projesini alır. Okunur/yazılır [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Sunumdaki tüm gömülü video dosyalarının koleksiyonunu döndürür. Salt okunur [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Sunuma geniş görüş özelliklerini alır. Salt okunur [`IViewProperties`](../iviewproperties). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Sunumdaki tüm slaytlar için Thumbnail Image nesneleri döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Sunumdaki belirtilen slaytlar için Thumbnail Bitmap nesneleri döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Belirtilen boyutta sunumdaki tüm slaytlar için Thumbnail Image nesneleri döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Özel ölçekleme ile sunumdaki tüm slaytlar için Thumbnail Image nesneleri döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Belirtilen boyutta sunumdaki belirtilen slaytlar için Thumbnail Image nesneleri döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Özel ölçekleme ile sunumdaki belirtilen slaytlar için Thumbnail Image nesneleri döndürür. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Id ile bir Slide, MasterSlide veya LayoutSlide döndürür. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Düzenli ifadeye ait tüm eşleşmeleri belirtilen renk ile vurgular. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Tüm slaytlardaki kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Düzenli ifadenin tüm eşleşmelerini belirtilen string ile değiştirir. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Belirtilen metnin tüm oluşumlarını başka bir belirtilen metinle değiştirir. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Sunumdaki tüm slaytları XAML işaretlemesini temsil eden bir dosya setine kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Sunumdaki tüm slaytları belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Sunumdaki tüm slaytları belirtilen formatta bir dosyaya kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Sunumdan belirtilen slaytları belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Sunumdaki tüm slaytları belirtilen formatta ve ek seçeneklerle bir akıma kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Sunumdan belirtilen slaytları belirtilen formatta bir dosyaya kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Sunumdaki tüm slaytları belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Sunumdan belirtilen slaytları belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Sunumdan belirtilen slaytları belirtilen formatta bir dosyaya kaydeder. |

### Ayrıca Bakınız

* arayüz [IPresentationComponent](../ipresentationcomponent)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->