---
title: IPdfOptions
second_title: Aspose.Slides for C++ API Referansı
description: Sunumun Pdf formatında kaydedilmesini kontrol eden seçenekleri sağlar.
type: docs
weight: 274
url: /tr/aspose.slides.export/ipdfoptions/
---
## IPdfOptions sınıf


Provides options that control how a presentation is saved in Pdf format.

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | Belgenin kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir. Bkz. [PdfAccessPermissions](../pdfaccesspermissions/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | Kullanıcı tanımlı yazı tipi ailesi adlarının bir dizisini döndürür; [Aspose.Slides](../../aspose.slides/) bunları ortak olarak değerlendirmelidir. Read [System::String](../../system/string/)[] |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | Belirtilen şeffaf rengi **true** ise bir görüntüye uygular. |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | Her görüntü için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. **bool**.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasına yol açar. |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. Read [PdfCompliance](../pdfcompliance/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür. Reads [System::String](../../system/string/). |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | Her slaytın etrafına siyah çerçeve çizmek için true. Read **bool**. |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Read **bool**. |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | ASCII karakterleri 32-127 için TrueType yazı tiplerini gömmek için true. 127'den büyük karakter kodları için [Fonts](../../aspose.slides/fonts/) her zaman gömülür. Read **bool**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Gradyenin görsel stilini döndürür. Read [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | Görüntünün şeffaf rengini alır. |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | Sunumdaki tüm OLE verilerini ortaya çıkan PDF'de gömülü dosyalara dönüştürmek için true. Read **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Dışa aktarılan belgede [Ink](../../aspose.slides.ink/) nesnelerinin görünümünü kontrol eden seçenekler sağlar. Read-only [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür. Read **uint8_t**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | PDF belgesini korumak için kullanıcı şifresi ayarlar. Read [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri çağırma nesnesini temsil eder. Bkz. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'e kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için ortaya çıkan PDF'de metnin kalitesini artırabilir. Read **bool**. |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | Sunumda kullanılan tüm metafile'ları PNG görüntülere dönüştürmek için true. Read **bool**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan **false**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirler. Read **bool**. Varsayılan değer **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri döndürür. |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma tipini belirler. Read [PdfTextCompression](../pdftextcompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür. Read [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel türlerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarının başlangıçını yapar. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize ve nullptr durumuna özel özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın dize durumuna özel özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | Belge kullanıcı erişimiyle açıldığında hangi erişim izinlerinin verileceğini belirten bir dizi bayrak içerir. [PdfAccessPermissions](../pdfaccesspermissions/) bakınız. |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Kullanıcı tanımlı yazı tipi ailesi adlarının bir dizisini ayarlar; [Aspose.Slides](../../aspose.slides/) bunları ortak olarak kabul etmelidir. Write [System::String](../../system/string/)[] |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | Belirtilen şeffaf rengi **true** ise bir görüntüye uygular. |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | Her görüntü için varsayılanın yerine en etkili sıkıştırmanın otomatik olarak seçilip seçilmeyeceğini gösterir. **bool**.true olarak ayarlanırsa, sunumdaki her görüntü için en uygun sıkıştırma algoritması seçilir ve bu, ortaya çıkan PDF belgesinin daha küçük olmasına yol açar. |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | Oluşturulan PDF belgesi için istenen uyumluluk seviyesi. Write [PdfCompliance](../pdfcompliance/). |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Kaynak yazı tipi bulunamadığında kullanılacak yazı tipini ayarlar. Writes [System::String](../../system/string/). |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | Her slaytın etrafına siyah çerçeve çizmek için true. Write **bool**. |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | Yazı tipinin tüm karakterlerinin mi yoksa yalnızca kullanılan alt kümesinin mi gömülmesi gerektiğini belirler. Write **bool**. |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | ASCII karakterleri 32-127 için TrueType yazı tiplerini gömmek için true. [Fonts](../../aspose.slides/fonts/) 127'den büyük karakter kodları için her zaman gömülür. Write **bool**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Gradyenin görsel stilini ayarlar. Write [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | Görüntünün şeffaf rengini ayarlar. |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | Sunumdaki tüm OLE verilerini ortaya çıkan PDF'de gömülü dosyalara dönüştürmek için true. Write **bool**. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri ayarlar. Write **uint8_t**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | PDF belgesini korumak için kullanıcı şifresi ayarlar. Write [System::String](../../system/string/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri çağırma nesnesini temsil eder. Bkz. [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | Yazı tipi kalın stilini desteklemediğinde metnin bitmap olarak rasterleştirilip PDF'e kaydedilip kaydedilmeyeceğini gösterir. Bu yaklaşım belirli yazı tipleri için ortaya çıkan PDF'de metnin kalitesini artırabilir. Write **bool**. |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | Sunumda kullanılan tüm metafile'ları PNG görüntülere dönüştürmek için true. Write **bool**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan **false**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirler. Write **bool**. Varsayılan değer **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../islideslayoutoptions/). |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | PDF belgesi içindeki görüntülerin çözünürlüğünü belirleyen bir değeri ayarlar. |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | Belgedeki tüm metin içeriği için kullanılacak sıkıştırma tipini belirler. Write [PdfTextCompression](../pdftextcompression/). |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi ayarlar. Write [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstergelerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bkz.

* Sınıf [ISaveOptions](../isaveoptions/)
* Ad alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)