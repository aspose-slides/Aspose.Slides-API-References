---
title: ITrendline
second_title: Aspose.Slides for C++ API Referansı
description: Sınıf, grafik serisinin eğri çizgisini temsil eder
type: docs
weight: 1223
url: /tr/aspose.slides.charts/itrendline/
---
## ITrendline sınıfı

Sınıf, grafik serisinin eğri çizgisini temsil eder

```cpp
class ITrendline : public Aspose::Slides::Charts::IOverridableText
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | Parametre \"text\" içindeki metinle TextFrameForOverriding'i başlatır. TextFrameForOverriding zaten başlatılmışsa yalnızca metnini değiştirir. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; burada iki NaN eşit kabul edilir, ancak IEC 60559:1989’a göre NaN hiçbir değerle, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; burada iki NaN eşit kabul edilir, ancak IEC 60559:1989’a göre NaN hiçbir değerle, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **double** [get_Backward](./get_backward/)() | Eğri çizgisinin, trendi izlenen serinin verilerinden önce uzadığı kategori (veya dağılımlı grafikte birim) sayısını belirtir. Dağılımlı ve dağılımsız grafiklerde değer herhangi bir sıfırdan büyük olmayan değer olabilir. Okuma **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Grafiği döndürür. Yalnızca okuma [IChart](../ichart/). |
| virtual **bool** [get_DisplayEquation](./get_displayequation/)() | Eğri çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etiket içinde) gösterileceğini belirtir. Okuma **bool**. |
| virtual **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() | Eğri çizgisinin R-kare değerinin grafikte (denklemin aynı etiketi içinde) gösterileceğini belirtir. Okuma **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Eğri çizgisinin biçimini temsil eder. Okuma [IFormat](../iformat/). |
| virtual **double** [get_Forward](./get_forward/)() | Eğri çizgisinin, trendi izlenen serinin verilerinden sonra uzadığı kategori (veya dağılımlı grafikte birim) sayısını belirtir. Dağılımlı ve dağılımsız grafiklerde değer herhangi bir sıfırdan büyük olmayan değer olabilir. Okuma **double**. |
| virtual **double** [get_Intercept](./get_intercept/)() | Eğri çizgisinin y eksenini kesişeceği değeri belirtir. Bu özellik yalnızca trend çizgi tipi exp, linear veya poly olduğunda desteklenir. Okuma **double**. |
| virtual **uint8_t** [get_Order](./get_order/)() | Polinomsal eğri çizgisinin derecesini belirtir. Diğer eğri çizgi tipleri için göz ardı edilir. Değer 2 ile 6 arasında olmalıdır. Okuma **uint8_t**. |
| virtual **uint8_t** [get_Period](./get_period/)() | Hareketli ortalama eğri çizgisi için trend çizgisinin periyodunu belirtir. Diğer eğri çizgi varyantları için göz ardı edilir. Değer 2 ile 255 arasında olmalıdır. Okuma **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Yalnızca okuma [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | Bu eğri çizgisiyle ilgili lejand girişini temsil eder. Yalnızca okuma [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Temel slaytı döndürür. Yalnızca okuma [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Grafik metin biçimini döndürür. Yalnızca okuma [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Zengin biçimlendirilmiş metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri otomatik oluşturulan metnin üzerine yazar. Otomatik oluşturulan metin, veri etiketi, değer ekseninin gösterim birim etiketi, eksen başlığı, grafik başlığı, eğri çizgi etiketi gibi örtük bir özelliktir. Otomatik oluşturulan metin [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) özelliğiyle biçimlendirilir. Yalnızca okuma [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() | Eğri çizgisinin adını alır. Okuma [System::String](../../system/string/). |
| virtual [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() | Eğri çizgi tipini alır. Okuma [TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi string ve nullptr durumu için. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi stringler durumu için. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_Backward](./set_backward/)(**double**) | Eğri çizgisinin, trendi izlenen serinin verilerinden önce uzadığı kategori (veya dağılımlı grafikte birim) sayısını belirtir. Dağılımlı ve dağılımsız grafiklerde değer herhangi bir sıfırdan büyük olmayan değer olabilir. Yazma **double**. |
| virtual void [set_DisplayEquation](./set_displayequation/)(**bool**) | Eğri çizgisinin denkleminin grafikte (Rsquaredvalue ile aynı etiket içinde) gösterileceğini belirtir. Yazma **bool**. |
| virtual void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) | Eğri çizgisinin R-kare değerinin grafikte (denklemin aynı etiketi içinde) gösterileceğini belirtir. Yazma **bool**. |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | Eğri çizgisinin biçimini temsil eder. Yazma [IFormat](../iformat/). |
| virtual void [set_Forward](./set_forward/)(**double**) | Eğri çizgisinin, trendi izlenen serinin verilerinden sonra uzadığı kategori (veya dağılımlı grafikte birim) sayısını belirtir. Dağılımlı ve dağılımsız grafiklerde değer herhangi bir sıfırdan büyük olmayan değer olabilir. Yazma **double**. |
| virtual void [set_Intercept](./set_intercept/)(**double**) | Eğri çizgisinin y eksenini kesişeceği değeri belirtir. Bu özellik yalnızca trend çizgi tipi exp, linear veya poly olduğunda desteklenir. Yazma **double**. |
| virtual void [set_Order](./set_order/)(**uint8_t**) | Polinomsal eğri çizgisinin derecesini belirtir. Diğer eğri çizgi tipleri için göz ardı edilir. Değer 2 ile 6 arasında olmalıdır. Yazma **uint8_t**. |
| virtual void [set_Period](./set_period/)(**uint8_t**) | Hareketli ortalama eğri çizgisi için trend çizgisinin periyodunu belirtir. Diğer eğri çizgi varyantları için göz ardı edilir. Değer 2 ile 255 arasında olmalıdır. Yazma **uint8_t**. |
| virtual void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) | Eğri çizgisinin adını ayarlar. Yazma [System::String](../../system/string/). |
| virtual void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) | Eğri çizgi tipini ayarlar. Yazma [TrendlineType](../trendlinetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string’e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Sınıf [IOverridableText](../ioverridabletext/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)