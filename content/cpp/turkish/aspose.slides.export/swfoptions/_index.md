---
title: SwfOptions
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumun Swf formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.
type: docs
weight: 742
url: /tr/aspose.slides.export/swfoptions/
---
## SwfOptions sınıfı

Bir sunumun Swf formatında nasıl kaydedileceğini kontrol eden seçenekler sağlar.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_Compressed](./get_compressed/)() override | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirler. Varsayılan **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Kaynak font bulunamadığında kullanılan fontu döndürür. [System::String](../../system/string/) okur. |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Bağlam menüsünü etkinleştirir/devre dışı bırakır. Varsayılan true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gradyanın görsel stilini döndürür. [GradientStyle](../../aspose.slides/gradientstyle/) okur. |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | JPEG görüntülerinin kalitesini belirler. Varsayılan 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo düzgün görüntülenmeyebilir. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Logonun tam hiperlink adresini alır. Yalnızca bir [set_LogoImageBytes()](./set_logoimagebytes/) belirtilmişse etkili olur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri arama nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Alt paneli gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Tam ekran düğmesini gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Sol paneli gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirler. Varsayılan true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Sayfa adımcısını gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Arama bölümünü gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Üst panelin tamamını gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Sunumu kaydederken JavaScript çağrısı içeren hiperlinkleri atlayıp atlamayacağını belirler. **bool** okur. Varsayılan değer **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Sunumu [ISlidesLayoutOptions](../islideslayoutoptions/) dışa aktarırken slaytların sayfada yerleştirildiği modu alır. Bu özellik [HandoutLayoutingOptions](../handoutlayoutingoptions/) türündeki nesnelerin atanmasını desteklemez. |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Açık sol panel ile başlar. flashvars içinde geçersiz kılınabilir. Varsayılan false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyiciyi içerip içermeyeceğini belirler. Varsayılan **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Uyarı alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) okur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özel biçimi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumuna özel biçimi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Oluşturulan SWF belgesinin sıkıştırılıp sıkıştırılmayacağını belirler. Varsayılan **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Kaynak font bulunamadığında kullanılan fontu ayarlar. [System::String](../../system/string/) yazar. |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Bağlam menüsünü etkinleştirir/devre dışı bırakır. Varsayılan true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Gradyanın görsel stilini ayarlar. [GradientStyle](../../aspose.slides/gradientstyle/) yazar. |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | JPEG görüntülerinin kalitesini belirler. Varsayılan 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Görüntüleyicinin sağ üst köşesinde logo olarak gösterilecek görüntü. Görüntü 32x64 piksel PNG olmalıdır, aksi takdirde logo düzgün görüntülenmeyebilir. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Logonun tam hiperlink adresini ayarlar. Yalnızca bir [set_LogoImageBytes()](./set_logoimagebytes/) belirtilmişse etkili olur. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Yüzde olarak ilerleme güncellemelerini kaydetmek için bir geri arama nesnesini temsil eder. [IProgressCallback](../../aspose.slides/iprogresscallback/) bakınız. |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Alt paneli gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Tam ekran düğmesini gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Oluşturulan belgenin gizli slaytları içerip içermeyeceğini belirler. Varsayılan **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Sol paneli gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Sayfalar etrafındaki kenarlığın gösterilip gösterilmeyeceğini belirler. Varsayılan true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Sayfa adımcısını gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Arama bölümünü gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Üst panelin tamamını gösterir/gizler. flashvars içinde geçersiz kılınabilir. Varsayılan true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Sunumu kaydederken JavaScript çağrısı içeren hiperlinkleri atlayıp atlamayacağını belirler. **bool** yazar. Varsayılan değer **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Sunumu [ISlidesLayoutOptions](../islideslayoutoptions/) dışa aktarırken slaytların sayfada yerleştirildiği modu ayarlar. Bu özellik [HandoutLayoutingOptions](../handoutlayoutingoptions/) türündeki nesnelerin atanmasını desteklemez. |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Açık sol panel ile başlar. flashvars içinde geçersiz kılınabilir. Varsayılan false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Oluşturulan SWF belgesinin bütünleşik belge görüntüleyiciyi içerip içermeyeceğini belirler. Varsayılan **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Uyarı alan ve yükleme işleminin devam edip etmeyeceğine karar veren bir nesneyi döndürür veya ayarlar. [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [SwfOptions](./swfoptions/)() |  |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Açıklamalar

Aşağıdaki örnek, PowerPoint'in SWF Flash'e nasıl dönüştürüleceğini gösterir. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Ayrıca Bakınız

* Sınıf [SaveOptions](../saveoptions/)
* Sınıf [ISwfOptions](../iswfoptions/)
* Ad alanı [Aspose::Slides::Export](../)
* Kütüphane [Aspose.Slides](../../)