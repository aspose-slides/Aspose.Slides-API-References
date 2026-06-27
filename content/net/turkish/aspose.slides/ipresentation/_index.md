---
title: IPresentation
second_title: Aspose.Slides için .NET API Referansı
description: Sunum belgesi
type: docs
weight: 6730
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
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Sunumda bulunan tüm özelleştirilmiş veri bölümlerini döndürür. Yalnızca okuma [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | IDisposable arabirimini döndürür. Yalnızca okuma IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Temel IPresentationComponent arabirimine erişim sağlar. Yalnızca okuma [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Sunumdaki tüm gömülü ses dosyalarının koleksiyonunu döndürür. Yalnızca okuma [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Yorum yazarlarının koleksiyonunu döndürür. Yalnızca okuma [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Tarih ve saat alanlarının içeriğini değiştirecek tarih ve saat değerini döndürür veya ayarlar. Varsayılan olarak bu Presentation nesnesinin oluşturulma zamanı. Okuma/Yazma DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Sunumun özelleştirilmiş verilerini döndürür. Yalnızca okuma [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Şekiller için varsayılan metin stilini döndürür. Yalnızca okuma [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Sunumu imzalamak için kullanılan imzaların koleksiyonunu döndürür. Yalnızca okuma [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Standart ve özelleştirilmiş belge özelliklerini içeren DocumentProperties nesnesini döndürür. Yalnızca okuma [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Sunumdaki ilk slayt numarasını temsil eder. Okuma/Yazma Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Yazı tipleri yöneticisini döndürür. Yalnızca okuma [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Sunumun HeaderFooter yöneticisini döndürür. Yalnızca okuma [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Tüm sunum slaytlarında (master, layout, not slaytları hariç) bulunan tüm köprüleri kolay erişimle sağlar. Yalnızca okuma [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Sunumdaki tüm görüntülerin koleksiyonunu döndürür. Yalnızca okuma [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Sunumda tanımlı tüm düzen slaytlarının listesini döndürür. Yalnızca okuma [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | El ilanı master yöneticisini döndürür. Yalnızca okuma [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Not master yöneticisini döndürür. Yalnızca okuma [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Sunumda tanımlı tüm master slaytlarının listesini döndürür. Yalnızca okuma [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Sunumun master temasını döndürür. Yalnızca okuma [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Not slayt boyutu nesnesini döndürür. Yalnızca okuma [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Bu sunumun izin yöneticisini alır. Yalnızca okuma [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Sunumda tanımlı tüm slayt bölümlerinin listesini döndürür. Yalnızca okuma [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür. Yalnızca okuma [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Sunumda tanımlı tüm slaytların listesini döndürür. Yalnızca okuma [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Slayt boyutu nesnesini döndürür. Yalnızca okuma [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Sunumun hangi formatta yüklendiği bilgisini döndürür. Yalnızca okuma [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Sunum makrolarıyla VBA projesini alır. Okuma/Yazma [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Sunumda gömülü tüm video dosyalarının koleksiyonunu döndürür. Yalnızca okuma [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Sunum genel görünüm özelliklerini alır. Yalnızca okuma [`IViewProperties`](../iviewproperties). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Sunumun tüm slaytları için Küçük Resim Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Belirtilen slaytlar için Küçük Resim Bitmap nesnelerini döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Belirtilen boyutta, sunumun tüm slaytları için Küçük Resim Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Özelleştirilmiş ölçekleme ile sunumun tüm slaytları için Küçük Resim Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Belirtilen slaytlar için belirtilen boyutta Küçük Resim Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Belirtilen slaytlar için özelleştirilmiş ölçekleme ile Küçük Resim Image nesnelerini döndürür. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Id ile bir Slide, MasterSlide veya LayoutSlide döndürür. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Tüm slaytlardaki, tüm kabul edilebilir şekillerdeki tüm paragraflarda aynı biçimlendirmeye sahip run'ları birleştirir. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Düzenli ifadenin tüm eşleşmelerini belirtilen metinle değiştirir. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Belirtilen metnin tüm görünümlerini başka bir belirtilen metinle değiştirir. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Sunumun tüm slaytlarını XAML işaretlemesini temsil eden dosyalar kümesine kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Sunumun tüm slaytlarını belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Belirtilen slaytları belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir akıma kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Belirtilen slaytları belirtilen formatta bir dosyaya kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Belirtilen slaytları belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Belirtilen slaytları belirtilen formatta bir dosyaya kaydeder. |

### İlgili

* interface [IPresentationComponent](../ipresentationcomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->