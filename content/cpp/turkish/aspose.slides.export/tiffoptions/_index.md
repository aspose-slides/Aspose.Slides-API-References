---
title: TiffOptions
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.
type: docs
weight: 768
url: /tr/aspose.slides.export/tiffoptions/
---
## TiffOptions sınıf


Bir sunumun TIFF formatında nasıl kaydedileceğini kontrol eden seçenekleri sağlar.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## Methods

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN da dahil, eşit olmadığından, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN da dahil, eşit olmadığından, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | Renkli bir resmi siyah beyaz bir resme dönüştürmek için algoritmayı belirler. Bu seçenek yalnızca [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) veya [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) olarak ayarlandığında uygulanır. Okuma [BlackWhiteConversionMode](../blackwhiteconversionmode/). Varsayılan [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | Sıkıştırma tipini belirtir. Okuma [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür. Okuma [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | İnç başına nokta olarak yatay çözünürlüğü belirtir. Okuma **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | İnç başına nokta olarak dikey çözünürlüğü belirtir. Okuma **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Degrade'nin görsel stilini döndürür. Okuma [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dır; bu, oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir. Okuma [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Dışa aktarılan belgede [Ink](../../aspose.slides.ink/) nesnelerinin görünümünü kontrol eden seçenekleri sağlar. Salt-okunur [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | Oluşturulan görüntüler için piksel biçimini belirtir. Okuma [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri çağırma nesnesini temsil eder. Bakınız [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir. Okuma **bool**. Varsayılan değer **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Sunumu dışa aktarırken slaytların sayfaya yerleştirilme kipini alır [ISlidesLayoutOptions](../islideslayoutoptions/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Okuma [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin karma oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referansla değer tipindeki nesneyi nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | Renkli bir resmi siyah beyaz bir resme dönüştürmek için algoritmayı belirler. Bu seçenek yalnızca [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) veya [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) olarak ayarlandığında uygulanır. Yazma [BlackWhiteConversionMode](../blackwhiteconversionmode/). Varsayılan [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | Sıkıştırma tipini belirtir. Yazma [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Kaynak yazı tipi bulunamadığında kullanılacak yazı tipini ayarlar. Yazma [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | İnç başına nokta olarak yatay çözünürlüğü belirtir. Yazma **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | İnç başına nokta olarak dikey çözünürlüğü belirtir. Yazma **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Degrade'nin görsel stilini ayarlar. Yazma [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Oluşturulan TIFF görüntüsünün boyutunu belirtir. Varsayılan değer 0x0'dır; bu, oluşturulan görüntü boyutlarının sunum slaytı boyutuna göre hesaplanacağı anlamına gelir. Yazma [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | Oluşturulan görüntüler için piksel biçimini belirtir. Yazma [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri çağırma nesnesini temsil eder. Bakınız [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Sunumu kaydederken JavaScript çağrıları içeren köprüleri atlayıp atlamayacağını belirtir. Yazma **bool**. Varsayılan değer **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Sunumu dışa aktarırken slaytların sayfaya yerleştirilme kipini ayarlar [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Uyarıları alan ve yükleme sürecinin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. Yazma [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [TiffOptions](./tiffoptions/)() | Varsayılan yapıcı. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit kaldırma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Açıklamalar


Aşağıdaki örnek, PowerPoint'i varsayılan boyutta TIFF'e nasıl dönüştüreceğinizi gösterir. 
```cpp
// Bir sunum dosyasını temsil eden Presentation nesnesi oluşturur
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// Sunumu TIFF belgesine kaydediyor
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
Aşağıdaki örnek, PowerPoint'i özel boyutta TIFF'e nasıl dönüştüreceğinizi gösterir. 
```cpp
// Bir Sunum dosyasını temsil eden Presentation nesnesini oluşturur
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// TiffOptions sınıfını oluşturur
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// Sıkıştırma tipini ayarlama
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Sıkıştırma Türleri
// Default - Varsayılan sıkıştırma şemasını belirtir (LZW).
// None - Sıkıştırma olmadığını belirtir.
// CCITT3
// CCITT4
// LZW
// RLE
// Derinlik sıkıştırma tipine bağlıdır ve manuel olarak ayarlanamaz.
// Çözünürlük birimi her zaman "2"'ye eşittir (dots per inch)
// Görüntü DPI'sını ayarlama
opts->set_DpiX(200);
opts->set_DpiY(100);
// Giriş Görüntü Boyutunu ayarla
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Sunumu belirtilen görüntü boyutuyla TIFF olarak kaydeder
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
Aşağıdaki örnek, PowerPoint'i özel görüntü piksel biçimiyle TIFF'e nasıl dönüştüreceğinizi gösterir. 
```cpp
// Bir Sunum dosyasını temsil eden Presentation nesnesi oluşturur
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// Sunumu belirtilen görüntü boyutuyla TIFF olarak kaydeder
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## Ayrıca Bakınız

* Class [SaveOptions](../saveoptions/)
* Class [ITiffOptions](../itiffoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)