---
title: PdfOptions
second_title: Aspose.Slides for C++ API Referansı
description: Sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
weight: 573
url: /tr/aspose.slides.export/pdfoptions/
---
## PdfOptions sınıfı

Bir sunumun PDF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir bayrak kümesi içerir. [PdfAccessPermissions](../pdfaccesspermissions/) bakın. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Kullanıcı tarafından tanımlanan font ailesi adlarının bir dizisini döndürür; [Aspose.Slides](../../aspose.slides/) bunları ortak olarak dikkate almalıdır. [System::String](../../system/string/)[] oku. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | **true** olduğunda belirtilen şeffaf rengi bir görüntüye uygular. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Her görüntü için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. **bool**.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasını sağlar. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. [PdfCompliance](../pdfcompliance/) oku. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Kaynak font bulunamadığında kullanılacak fontu döndürür. [System::String](../../system/string/) okunur. |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | **true** ise her slaytın etrafına siyah çerçeve çizer. **bool** oku. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Fontun tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi yerleştirileceğini belirler. **bool** oku. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | [Aspose.Slides](../../aspose.slides/)'nun ASCII (33..127 kod aralığı) metin için ortak fontları yerleştirip yerleştirmeyeceğini belirler. 127'den büyük karakter kodları için [Fonts](../../aspose.slides/fonts/) her zaman yerleştirilir. Ortak fontlar listesi PDF'nin temel 14 fontunu ve ek kullanıcı belirlediği fontları içerir. **bool** oku. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gradyanın görsel stilini döndürür. [GradientStyle](../../aspose.slides/gradientstyle/) oku. |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Görüntünün şeffaf rengini alır. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | **true** ise sunumdaki tüm OLE verilerini ortaya çıkan PDF'de gömülü dosyalara dönüştürür. **bool** oku. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Dışa aktarılan belgede [Ink](../../aspose.slides.ink/) nesnelerinin görünümünü kontrol eden seçenekler sağlar. Yalnızca-okunur [IInkOptions](../iinkoptions/). |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | PDF belgesindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür. **uint8_t** oku. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | PDF belgesini korumak için kullanıcı şifresi ayarlama. [System::String](../../system/string/) oku. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | İlerleme güncellemelerini yüzde olarak kaydetmek için bir geri çağırma nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakın. |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterlenip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yöntem, belirli fontlar için ortaya çıkan PDF'deki metin kalitesini artırabilir. **bool** oku. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | Sunumda kullanılan tüm metafile'ları PNG görüntülere dönüştürmek için **true**. **bool** oku. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Sunumu kaydederken JavaScript çağrılı hiperlinklerin atlanıp atlanmayacağını belirler. **bool** oku. Varsayılan değer **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Sunumu [ISlidesLayoutOptions](../islideslayoutoptions/) dışa aktarırken slaytların sayfada hangi düzende yerleştirileceğini alır. |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | PDF belgesindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Belgedeki tüm metinsel içeriğin sıkıştırma tipini belirler. [PdfTextCompression](../pdftextcompression/) oku. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) oku. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
|  [PdfOptions](./pdfoptions/)() | Varsayılan yapıcı. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nın dize ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nın dizeler durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir bayrak kümesi içerir. [PdfAccessPermissions](../pdfaccesspermissions/) bakın. |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Kullanıcı tarafından tanımlanan font aileleri adlarının bir dizisini ayarlar; [Aspose.Slides](../../aspose.slides/) bunları ortak olarak dikkate almalıdır. [System::String](../../system/string/)[] yaz. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | **true** ise belirtilen şeffaf rengi bir görüntüye uygular. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Her görüntü için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. **bool**.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasını sağlar. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Oluşturulan PDF belgesi için istenen uyumluluk seviyesini ayarlar. [PdfCompliance](../pdfcompliance/) yaz. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Kaynak font bulunamadığında kullanılacak fontu ayarlar. [System::String](../../system/string/) yazar. |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | **true** ise her slaytın etrafına siyah çerçeve çizer. **bool** yazar. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Fontun tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi yerleştirileceğini belirler. **bool** yazar. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | [Aspose.Slides](../../aspose.slides/)'nun ASCII (33..127 kod aralığı) metin için ortak fontları yerleştirip yerleştirmeyeceğini belirler. 127'den büyük karakter kodları için [Fonts](../../aspose.slides/fonts/) her zaman yerleştirilir. Ortak fontlar listesi PDF'nin temel 14 fontunu ve ek kullanıcı belirlediği fontları içerir. **bool** yazar. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Gradyanın görsel stilini ayarlar. [GradientStyle](../../aspose.slides/gradientstyle/) yazar. |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Görüntünün şeffaf rengini ayarlar. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | **true** ise sunumdaki tüm OLE verilerini ortaya çıkan PDF'de gömülü dosyalara dönüştürür. **bool** yazar. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | PDF belgesindeki JPEG görüntülerinin kalitesini belirleyen bir değeri ayarlar. **uint8_t** yazar. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | PDF belgesini korumak için kullanıcı şifresi ayarlama. [System::String](../../system/string/) yazar. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | İlerleme güncellemelerini yüzde olarak kaydetmek için bir geri çağırma nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakın. |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterlenip PDF'ye kaydedilip kaydedilmeyeceğini gösterir. Bu yöntem, belirli fontlar için ortaya çıkan PDF'deki metin kalitesini artırabilir. **bool** yazar. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | **true** ise sunumda kullanılan tüm metafile'ları PNG görüntülere dönüştürür. **bool** yazar. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Sunumu kaydederken JavaScript çağrılı hiperlinklerin atlanıp atlanmayacağını belirler. **bool** yazar. Varsayılan değer **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Sunumu [ISlidesLayoutOptions](../islideslayoutoptions/) dışa aktarırken slaytların sayfada hangi düzende yerleştirileceğini ayarlar. |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | PDF belgesindeki görüntülerin çözünürlüğünü ayarlar. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Belgedeki tüm metinsel içeriğin sıkıştırma tipini belirler. [PdfTextCompression](../pdftextcompression/) yazar. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmaya izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Açıklamalar

Aşağıdaki örnek, PowerPoint'i özel seçeneklerle PDF'ye nasıl dönüştüreceğinizi gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// PdfOptions sınıfını örnekler
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Jpeg kalitesini ayarlar
pdfOptions->set_JpegQuality(90);
// Metafile'ların davranışını ayarlar
pdfOptions->set_SaveMetafilesAsPng(true);
// Metin sıkıştırma seviyesini ayarlar
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// PDF standardını tanımlar
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Sunumu PDF olarak kaydeder
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Aşağıdaki örnek, PowerPoint'i gizli slaytlarla PDF'ye nasıl dönüştüreceğinizi gösterir. 
```cpp
// PowerPoint dosyasını temsil eden bir Presentation sınıfını örnekler
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// PdfOptions sınıfını örnekler
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Gizli slaytları ekler
pdfOptions->set_ShowHiddenSlides(true);
// Sunumu PDF olarak kaydeder
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Aşağıdaki örnek, PowerPoint'i şifre korumalı PDF'ye nasıl dönüştüreceğinizi gösterir. 
```cpp
// PowerPoint dosyasını temsil eden bir Presentation nesnesini örnekler
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// PDF şifresini ve erişim izinlerini ayarlar
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Sunumu PDF olarak kaydeder
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Aşağıdaki örnek, PowerPoint'i notlarla PDF'ye nasıl dönüştüreceğinizi gösterir. 
```cpp
// Bir sunum dosyasını temsil eden bir Presentation nesnesi örnekler
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Diğer Bağlantılar

* Sınıf [SaveOptions](../saveoptions/)
* Sınıf [IPdfOptions](../ipdfoptions/)
* AdAlanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)