---
title: Presentation
second_title: Aspose.Sildes for .NET API Referansı
description: Microsoft PowerPoint sunumunu temsil eder.
type: docs
weight: 9570
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
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Sunumda tüm özel veri parçalarını döndürür. Yalnızca okunur [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Sunumda yerleşik tüm ses dosyalarının koleksiyonunu döndürür. Yalnızca okunur [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Yorum yazarlarının koleksiyonunu döndürür. Yalnızca okunur [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Tarih ve saat alanlarının içeriğini değiştirecek tarih ve zamanı döndürür veya ayarlar. Varsayılan olarak bu Presentation nesnesinin oluşturulma zamanı. Okunur/Yazılabilir DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Sunumun özel verilerini döndürür. Yalnızca okunur [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Şekiller için varsayılan metin stilini döndürür. Yalnızca okunur [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Sunumu imzalamak için kullanılan imzaların koleksiyonunu döndürür. Yalnızca okunur [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Standart ve özel belge özelliklerini içeren DocumentProperties nesnesini döndürür. Yalnızca okunur [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Sunumdaki ilk slayt numarasını temsil eder |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Yazı tipi yöneticisini döndürür. Yalnızca okunur [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Gerçek HeaderFooter yöneticisini döndürür. Yalnızca okunur [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Tüm sunum slaytlarında (master, yerleşim, not slaytları hariç) bulunan tüm hiperlinklere kolay erişim sağlar. Yalnızca okunur [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Sunumdaki tüm görsellerin koleksiyonunu döndürür. Yalnızca okunur [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Sunumda tanımlı tüm yerleşim slaytlarının bir listesini döndürür. Yalnızca okunur [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Handout master yöneticisini döndürür. Yalnızca okunur [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Not master yöneticisini döndürür. Yalnızca okunur [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Sunumda tanımlı tüm ana slaytların bir listesini döndürür. Yalnızca okunur [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Ana temayı döndürür. Yalnızca okunur [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Not slayt boyutu nesnesini döndürür. Yalnızca okunur [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Bu sunum için izin yöneticisini alır. Yalnızca okunur [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Sunumda tanımlı tüm slayt bölümlerinin bir listesini döndürür. Yalnızca okunur [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Sunum belgesine uygulanan duyarlılık etiketlerinin koleksiyonunu döndürür. Yalnızca okunur [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Sunumda tanımlı tüm slaytların bir listesini döndürür. Yalnızca okunur [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Sunum için slayt gösterisi ayarlarını döndürür. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Slayt boyutu nesnesini döndürür. Yalnızca okunur [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Sunumun hangi formatta yüklendiği hakkında bilgi döndürür. Yalnızca okunur [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Sunum makrolarıyla VBA projesini alır veya ayarlar. Okunur/Yazılabilir [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Sunumda yerleşik tüm video dosyalarının koleksiyonunu döndürür. Yalnızca okunur [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Sunum genelindeki görünüm özelliklerini alır. Yalnızca okunur [`IViewProperties`](../iviewproperties). |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Bu Presentation nesnesi tarafından kullanılan tüm kaynakları serbest bırakır. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Bir sunumun tüm slaytları için Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Belirtilen slaytlar için Thumbnail Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Belirtilen boyutta, bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Özel ölçekleme ile bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Belirtilen boyutta, bir sunumun belirtilen slaytları için Thumbnail Image nesnelerini döndürür. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Özel ölçekleme ile bir sunumun belirtilen slaytları için Thumbnail Image nesnelerini döndürür. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Id ile bir Slide, MasterSlide veya LayoutSlide döndürür. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Düzenli ifadenin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Örnek metnin tüm eşleşmelerini belirtilen renk ile vurgular. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Tüm slaytlardaki tüm geçerli şekillerdeki tüm paragraflarda aynı formatta olan run'ları birleştirir. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Düzenli ifadenin tüm eşleşmelerini belirtilen string ile değiştirir. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Belirtilen metnin tüm görünümlerini başka bir belirtilen metin ile değiştirir. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Bir sunumun tüm slaytlarını XAML işaretlemesini temsil eden bir dosya kümesine kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Bir sunumun tüm slaytlarını belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Belirtilen slaytları sayfa numaraları korunarak belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Bir sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir akıma kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Belirtilen slaytları sayfa numaraları korunarak belirtilen formatta bir dosyaya kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Belirtilen slaytları sayfa numaraları korunarak belirtilen formatta bir akıma kaydeder. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Belirtilen slaytları sayfa numaraları korunarak belirtilen formatta bir dosyaya kaydeder. |

### Örnekler

Aşağıdaki örnek, PowerPoint Presentation oluşturmanın nasıl yapılacağını gösterir.

```csharp
[C#]
// Bir sunum dosyasını temsil eden Presentation nesnesi oluşturun
using (Presentation presentation = new Presentation())
{
    // İlk slaytı al
    ISlide slide = presentation.Slides[0];
    // Çizgi tipinde bir autoshape ekle
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Sunum dosyasını kaydet.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Aşağıdaki örnek, Presentation'ı açma ve kaydetme işlemini gösterir.

```csharp
[C#]
// Presentation içinde desteklenen herhangi bir dosyayı yükleyin, örn. ppt, pptx, odp vb.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Sunum dosyasını kaydet.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Ayrıca Bakınız

* arayüz [IPresentation](../ipresentation)
* ad alanı [Aspose.Slides](../../aspose.slides)
* derleme [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->