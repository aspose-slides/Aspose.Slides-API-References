---
title: ISVGOptions
second_title: Aspose.Slides for C++ API Referansı
description: Bir SVG seçeneğini temsil eder.
type: docs
weight: 404
url: /tr/aspose.slides.export/isvgoptions/
---
## ISVGOptions sınıf

Bir SVG seçeneğini temsil eder.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür. [System::String](../../system/string/) okunur. |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir bool işareti. True ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu durum dosyanın daha büyük olmasına yol açabilir). Okur **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | SVG'de 3B metnin devre dışı bırakılıp bırakılmadığını belirler. Okur **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren bir değeri alır. **true** olarak ayarlandığında, ligatürler çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik **false**. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. Okur **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1, işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. [Aspose.Slides](../../aspose.slides/) SVG yazma motoru bu sorunu, oku olan çizgi sonunu kırparak, çizginin işaretçileri örtmemesini sağlayacak bir geçici çözümle giderir. Bu seçenek bu davranışı kapatır. Okur **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Dışarıdan yüklenen yazı tiplerinin işlenme şeklini belirler. [SvgExternalFontsHandling](../svgexternalfontshandling/) okunur. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Gradyanın görsel stilini döndürür. [GradientStyle](../../aspose.slides/gradientstyle/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Dışa aktarılan belgelerdeki [Ink](../../aspose.slides.ink/) nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Sadece-okunur [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | JPEG kodlama kalitesini belirler. Okur **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Met dosya rasterleştirme için alt çözünürlük sınırını döndürür. Okur **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Resim sıkıştırma seviyesini temsil eder. [PicturesCompression](../picturescompression/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Yüzde cinsinden ilerleme güncellemelerini kaydetmek için bir geri çağırma nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Kullanıcının şekil dönüşümünü kontrol etmesine olanak tanıyan bir geri çağırma arabirimini döndürür ve ayarlar. [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) okunur. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Sunumu kaydederken JavaScript çağrısı içeren köprülerin atlanıp atlanmayacağını belirtir. Okur **bool**. Varsayılan değer **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. Okur **bool**. Varsayılan değer **true**. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Metin çerçevesinin render alanına dahil edilip edilmeyeceğini belirler. Okur **bool**. Varsayılan değer **false**. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. Okur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Uyarıları alıp yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayıcı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referansla bir değer tipindeki nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumu için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Kaynak yazı tipi bulunamadığında kullanılacak yazı tipini ayarlar. [System::String](../../system/string/) yazar. |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | Kırpılmış parçaların belgenin bir parçası olarak kalıp kalmayacağını belirten bir bool işareti. True ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu durum dosyanın daha büyük olmasına yol açabilir). **bool** yazar. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | SVG'de 3B metnin devre dışı bırakılıp bırakılmadığını belirler. **bool** yazar. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Ligatürler kullanılmadan metnin işlenip işlenmeyeceğini gösteren bir değer ayarlar. **true** olarak ayarlandığında, ligatürler çıktıda devre dışı bırakılır. Varsayılan olarak bu özellik **false**. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. **bool** yazar. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 işaretçiler için iç boşluk tanımlama yeteneğine sahip değildir. [Aspose.Slides](../../aspose.slides/) SVG yazma motoru bu sorunu, oku olan çizgi sonunu kırparak, çizginin işaretçileri örtmemesini sağlayacak bir geçici çözümle giderir. Bu seçenek bu davranışı kapatır. **bool** yazar. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Dışarıdan yüklenen yazı tiplerinin işlenme şeklini belirler. [SvgExternalFontsHandling](../svgexternalfontshandling/) yazar. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Gradyanın görsel stilini ayarlar. [GradientStyle](../../aspose.slides/gradientstyle/) yazar. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | JPEG kodlama kalitesini belirler. **int32_t** yazar. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Met dosya rasterleştirme için alt çözünürlük sınırını ayarlar. **int32_t** yazar. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Resim sıkıştırma seviyesini temsil eder. [PicturesCompression](../picturescompression/) yazar. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Yüzde cinsinden ilerleme güncellemelerini kaydetmek için bir geri çağırma nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Kullanıcının şekil dönüşümünü kontrol etmesine olanak tanıyan bir geri çağırma arabirimini döndürür ve ayarlar. [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) yazar. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Sunumu kaydederken JavaScript çağrısı içeren köprülerin atlanıp atlanmayacağını belirtir. **bool** yazar. Varsayılan değer **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. **bool** yazar. Varsayılan değer **true**. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Metin çerçevesinin render alanına dahil edilip edilmeyeceğini belirler. **bool** yazar. Varsayılan değer **false**. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Slayttaki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. **bool** yazar. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Uyarıları alıp yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [ISaveOptions](../isaveoptions/)
* Ad alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)