---
title: HtmlOptions
second_title: Aspose.Slides for C++ API Referansı
description: HTML dışa aktarma seçeneklerini temsil eder.
type: docs
weight: 118
url: /tr/aspose.slides.export/htmloptions/
---
## HtmlOptions sınıfı

Represents a HTML exporting options.

```cpp
class HtmlOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::IHtmlOptions
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür. [System::String](../../system/string/) okunur. |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Kırpılmış parçaların belge içinde kalıp kalmayacağını belirten bir Boolean bayrağıdır. true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya neden olabilir). |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Metnin ligatürler kullanılmadan işlenip işlenmediğini gösteren bir değeri alır. **true** olduğunda, çıktıda ligatürler devre dışı bırakılır. Varsayılan olarak bu özellik **false** olarak ayarlanmıştır. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gradyanın görsel stilini döndürür. [GradientStyle](../../aspose.slides/gradientstyle/) okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\> [get_HtmlFormatter](./get_htmlformatter/)() override | HTML şablonunu döndürür. [IHtmlFormatter](../ihtmlformatter/) okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | [Ink](../../aspose.slides.ink/) nesnelerinin dışa aktarılan belgede görünümünü kontrol eden seçenekler sağlar. Salt okunur [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri döndürür. **uint8_t** okunur. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Resim sıkıştırma seviyesini temsil eder. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | İlerleme güncellemelerini yüzde olarak kaydetmek için bir geri çağırma nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Sunumu kaydederken JavaScript çağrısı içeren hiperlinklerin atlanıp atlanmayacağını belirtir. **bool** okunur. Varsayılan değer **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\> [get_SlideImageFormat](./get_slideimageformat/)() override | Slayt görüntü formatı seçeneklerini döndürür. [ISlideImageFormat](../islideimageformat/) okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu alır [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **bool** [get_SvgResponsiveLayout](./get_svgresponsivelayout/)() override | svg konteynerinden genişlik ve yükseklik niteliklerini çıkarmak için true – bu, düzeni duyarlı hâle getirir. Aksi takdirde false. **bool** okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Uyarıları alan ve yükleme sürecinin devam edip edilmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun bir analogudur. Özel nesnelerin karma değerini (hash) etkinleştirir. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının bir analogudur. |
|  [HtmlOptions](./htmloptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Yeni bir [HtmlOptions](./) nesnesi oluşturur ve geri çağırma belirtir. |
|  [HtmlOptions](./htmloptions/)() | Tek bir HTML dosyasına kaydetmek için yeni bir [HtmlOptions](./) nesnesi oluşturur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün bir analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun bir analogudur. Özel tipleri kopyalamayı (clone) etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarının başlatılmasını gerçekleştirir. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirilmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Kaynak yazı tipi bulunamadığında kullanılan yazı tipini ayarlar. [System::String](../../system/string/) yazar. |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Kırpılmış parçaların belge içinde kalıp kalmayacağını belirten bir Boolean bayrağıdır. true ise kırpılmış parçalar kaldırılır, false ise belge içinde serileştirilir (bu daha büyük bir dosyaya neden olabilir). |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Metnin ligatürler kullanılmadan işlenip işlenmeyeceğini gösteren bir değeri ayarlar. **true** olduğunda, çıktıda ligatürler devre dışı bırakılır. Varsayılan olarak bu özellik **false** olarak ayarlanmıştır. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Gradyanın görsel stilini ayarlar. [GradientStyle](../../aspose.slides/gradientstyle/) yazar. |
| void [set_HtmlFormatter](./set_htmlformatter/)([System::SharedPtr](../../system/sharedptr/)\<[IHtmlFormatter](../ihtmlformatter/)\>) override | HTML şablonunu ayarlar. [IHtmlFormatter](../ihtmlformatter/) yazar. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | PDF belgesi içindeki JPEG görüntülerinin kalitesini belirleyen bir değeri ayarlar. **uint8_t** yazar. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Resim sıkıştırma seviyesini temsil eder. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | İlerleme güncellemelerini yüzde olarak kaydetmek için bir geri çağırma nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Sunumu kaydederken JavaScript çağrısı içeren hiperlinklerin atlanıp atlanmayacağını belirtir. **bool** yazar. Varsayılan değer **false**. |
| void [set_SlideImageFormat](./set_slideimageformat/)([System::SharedPtr](../../system/sharedptr/)\<[ISlideImageFormat](../islideimageformat/)\>) override | Slayt görüntü formatı seçeneklerini ayarlar. [ISlideImageFormat](../islideimageformat/) yazar. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Sunumu dışa aktarırken slaytların sayfada yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SvgResponsiveLayout](./set_svgresponsivelayout/)(**bool**) override | svg konteynerinden genişlik ve yükseklik niteliklerini çıkarmak için true – bu, düzeni duyarlı hâle getirir. Aksi takdirde false. **bool** yazar. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Uyarıları alan ve yükleme sürecinin devam edip edilmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun bir analogudur. Özel nesnelerin string'e dönüştürülmesini etkinleştirir. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma (unlock) işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [SaveOptions](../saveoptions/)
* Sınıf [IHtmlOptions](../ihtmloptions/)
* Ad alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)