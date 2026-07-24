---
title: ISwfOptions
second_title: Aspose.Slides for C++ API Referansı
description: Sunumun SWF formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
weight: 469
url: /tr/aspose.slides.export/iswfoptions/
---
## ISwfOptions sınıfı

Sunumun SWF formatında kaydedilmesini kontrol eden seçenekler sunar.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanan nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift duyarlıklı karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. Varsayılan **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Kaynak font bulunamadığında kullanılan fontu döndürür. [System::String](../../system/string/) okunur. |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Bağlam menüsünü etkinleştirir/devre dışı bırakır. Varsayılan **true**. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Gradyan görsel stilini döndürür. [GradientStyle](../../aspose.slides/gradientstyle/) okunur. |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | JPEG görüntü kalitesini belirtir. \n\n Varsayılan **95**. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. \n\n Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo yanlış görüntülenebilir. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Logonun tam hiperlink adresini alır. Yalnızca bir [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) belirtilmişse etkili olur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri arama nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakın. |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Alt bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Tam ekran düğmesini gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Sol bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Sayfaların etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. Varsayılan **true**. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Sayfa adımı göstericisini gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Arama bölümünü gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Tüm üst bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Sunumu kaydederken JavaScript çağrısı içeren hiperlinklerin atlanıp atlanmayacağını belirtir. **bool** okunur. Varsayılan değer **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu alır [ISlidesLayoutOptions](../islideslayoutoptions/). Bu özellik **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** tipindeki nesnelerin atanmasını desteklemez. |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Açık sol bölme ile başlar. flashvars içinde geçersiz kılınabilir. Varsayılan **false**. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyiciyi içerip içermeyeceğini belirtir. Varsayılan **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesne döndürür. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve türev sınıfların kopya oluşturmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve türev sınıfların kopya oluşturmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirtir. Varsayılan **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Kaynak font bulunamadığında kullanılacak fontu ayarlar. [System::String](../../system/string/) yazar. |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Bağlam menüsünü etkinleştirir/devre dışı bırakır. Varsayılan **true**. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Gradyanın görsel stilini ayarlar. [GradientStyle](../../aspose.slides/gradientstyle/) yazar. |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | JPEG görüntü kalitesini belirtir. \n\n Varsayılan **95**. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. \n\n Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo yanlış görüntülenebilir. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Logonun tam hiperlink adresini ayarlar. Yalnızca bir [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) belirtilmişse etkili olur. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri arama nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakın. |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Alt bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Tam ekran düğmesini gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirtir. Varsayılan **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Sol bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Sayfaların etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirtir. Varsayılan **true**. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Sayfa adımı göstericisini gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Arama bölümünü gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Tüm üst bölmeyi gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan **true**. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Sunumu kaydederken JavaScript çağrısı içeren hiperlinklerin atlanıp atlanmayacağını belirtir. **bool** yazar. Varsayılan değer **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Sunumu dışa aktarırken slaytların sayfaya yerleştirildiği modu ayarlar [ISlidesLayoutOptions](../islideslayoutoptions/). Bu özellik **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** tipindeki nesnelerin atanmasını desteklemez. |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Açık sol bölme ile başlar. flashvars içinde geçersiz kılınabilir. Varsayılan **false**. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyiciyi içerip içermeyeceğini belirtir. Varsayılan **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Uyarıları alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesne ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca

* Sınıf [ISaveOptions](../isaveoptions/)
* AdAlanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)