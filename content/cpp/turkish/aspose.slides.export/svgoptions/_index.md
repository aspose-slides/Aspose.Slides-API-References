---
title: SVGOptions
second_title: Aspose.Slides for C++ API Referansı
description: SVG seçeneklerini temsil eder.
type: docs
weight: 703
url: /tr/aspose.slides.export/svgoptions/
---
## SVGOptions sınıfı

Bir SVG seçeneğini temsil eder.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Metodlar

| Metod | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standartına göre NaN hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C#-stilindeki kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standartına göre NaN hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C#-stilindeki kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Varsayılan ayarları döndürür. Salt okunur [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür. [System::String](../../system/string/) okunur. |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Bir boolean bayrak, kırpılmış parçaların belgenin bir parçası olarak kalıp kalmadığını gösterir. true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | SVG içinde 3B metnin devre dışı bırakılıp bırakılmadığını belirler. **bool** okunur. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Metnin birleştirme karakterleri (ligatur) kullanılmadan render edilip edilmediğini gösteren bir değer alır. **true** olarak ayarlandığında, birleştirme karakterleri çıktı içinde devre dışı bırakılır. Varsayılan olarak bu özellik **false** olarak ayarlanmıştır. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. **bool** okunur. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1, işaretçiler için iç boşlukları tanımlama yeteneğine sahip değildir. [Aspose.Slides](../../aspose.slides/) SVG yazma motoru bu sorun için bir çözüm sunar: okla satır sonunu kırpar, böylece satır işaretçileri örtüşmez. Bu seçenek bu davranışı kapatır. **bool** okunur. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Harici yüklenen yazı tiplerinin işlenme yolunu belirler. [SvgExternalFontsHandling](../svgexternalfontshandling/) okunur. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gradyanın görsel stilini döndürür. [GradientStyle](../../aspose.slides/gradientstyle/) okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Dışa aktarılan belgede [Ink](../../aspose.slides.ink/) nesnelerinin görünümünü kontrol eden seçenekler sağlar. Salt okunur [IInkOptions](../iinkoptions/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | JPEG kodlama kalitesini belirler. **int32_t** okunur. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Metafile rasterleştirme için alt çözünürlük sınırını döndürür. **int32_t** okunur. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Resim sıkıştırma seviyesini temsil eder. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri çağırma nesnesi temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Kullanıcının şekil dönüşümünü kontrol etmesine izin veren bir geri çağırma arayüzünü döndürür ve ayarlar. [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) okunur. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | En basit ve en küçük SVG dosyası üretimi için ayarları döndürür. Salt okunur [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Sunumu kaydederken JavaScript çağrısı içeren köprülerin atlanıp atlanmayacağını belirtir. **bool** okunur. Varsayılan değer **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. **bool** okunur. Varsayılan değer **true**. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Metin çerçevesinin render alanına dahil edilip edilmeyeceğini belirler. **bool** okunur. Varsayılan değer **false**. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Slayd üzerindeki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. **bool** okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) okunur. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | En doğru SVG dosyası üretimi için ayarları döndürür. Salt okunur [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans yoluyla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans yoluyla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumuna özgü özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ün dize durumuna özgü özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini ayarlar. [System::String](../../system/string/) yazar. |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Bir boolean bayrak, kırpılmış parçaların belgenin bir parçası olarak kalıp kalmadığını gösterir. true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya yol açabilir). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | SVG içinde 3B metnin devre dışı bırakılıp bırakılmadığını belirler. **bool** yazar. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Metnin birleştirme karakterleri (ligatur) kullanılmadan render edilip edilmeyeceğini gösteren bir değeri ayarlar. **true** olarak ayarlandığında, birleştirme karakterleri çıktı içinde devre dışı bırakılır. Varsayılan olarak bu özellik **false** olarak ayarlanmıştır. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | FromCornerX ve FromCenter gradyanlarının bölünmesini devre dışı bırakır. **bool** yazar. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1, işaretçiler için iç boşlukları tanımlama yeteneğine sahip değildir. [Aspose.Slides](../../aspose.slides/) SVG yazma motoru bu sorun için bir çözüm sunar: okla satır sonunu kırpar, böylece satır işaretçileri örtüşmez. Bu seçenek bu davranışı kapatır. **bool** yazar. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Harici yüklenen yazı tiplerinin işlenme yolunu belirler. [SvgExternalFontsHandling](../svgexternalfontshandling/) yazar. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Gradyanın görsel stilini ayarlar. [GradientStyle](../../aspose.slides/gradientstyle/) yazar. |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | JPEG kodlama kalitesini belirler. **int32_t** yazar. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Metafile rasterleştirme için alt çözünürlük sınırını ayarlar. **int32_t** yazar. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Resim sıkıştırma seviyesini temsil eder. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri çağırma nesnesi temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Kullanıcının şekil dönüşümünü kontrol etmesine izin veren bir geri çağırma arayüzünü döndürür ve ayarlar. [ISvgShapeFormattingController](../isvgshapeformattingcontroller/) yazar. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Sunumu kaydederken JavaScript çağrısı içeren köprülerin atlanıp atlanmayacağını belirtir. **bool** yazar. Varsayılan değer **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Render sırasında şeklin belirtilen dönüşünün uygulanıp uygulanmayacağını belirler. **bool** yazar. Varsayılan değer **true**. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Metin çerçevesinin render alanına dahil edilip edilmeyeceğini belirler. **bool** yazar. Varsayılan değer **false**. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Slayd üzerindeki metnin grafik olarak kaydedilip kaydedilmeyeceğini belirler. **bool** yazar. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf bir gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| [SVGOptions](./svgoptions/)() | [SVGOptions](./) sınıfının yeni bir örneğini başlatır. |
| [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | [SVGOptions](./) sınıfının yeni bir örneğini, bağlantı gömme denetleyici nesnesini belirterek başlatır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [SaveOptions](../saveoptions/)
* Sınıf [ISVGOptions](../isvgoptions/)
* AdAlanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)