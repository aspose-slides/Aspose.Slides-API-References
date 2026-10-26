---
title: Trendline
second_title: Aspose.Slides için C++ API Referansı
description: Sınıf, grafik serisinin trend çizgisini temsil eder
type: docs
weight: 1366
url: /tr/aspose.slides.charts/trendline/
---
## Trendline sınıfı

Sınıf, grafik serisinin trend çizgisini temsil eder

```cpp
class Trendline : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::TrendlineCollection>>,
                  public Aspose::Slides::Charts::ITrendline
```

## Metodlar

| Metod | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | TextFrameForOverriding'i parametre "text" içindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa sadece metnini değiştirir. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **double** [get_Backward](./get_backward/)() override | Trend çizgisinin veri serisinin öncesinde uzadığı kategori (veya dağılım grafiğinde birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer herhangi bir sıfırdan büyük ya da eşit değer olmalıdır. Okunur **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Üst grafiği döndürür. Salt okunur [IChart](../ichart/). |
| **bool** [get_DisplayEquation](./get_displayequation/)() override | Trend çizgisinde denklemin (Rsquaredvalue ile aynı etikette) görüntülendiğini belirtir. Okunur **bool**. |
| **bool** [get_DisplayRSquaredValue](./get_displayrsquaredvalue/)() override | Trend çizgisinin R-kare değerinin grafik üzerinde (eşitlik ile aynı etikette) görüntülendiğini belirtir. Okunur **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Trend çizgisinin biçimini temsil eder. Okunur [IFormat](../iformat/). |
| **double** [get_Forward](./get_forward/)() override | Trend çizgisinin veri serisinin sonrasında uzadığı kategori (veya birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer herhangi bir sıfırdan büyük ya da eşit değer olmalıdır. Okunur **double**. |
| **double** [get_Intercept](./get_intercept/)() override | Trend çizgisinin y eksenini kestiği değeri belirtir. Bu özellik yalnızca trend çizgi türü exp, linear veya poly olduğunda desteklenir. Okunur **double**. |
| **uint8_t** [get_Order](./get_order/)() override | Polinom trend çizgisinin derecesini belirtir. Diğer trend çizgi tiplerinde göz ardı edilir. Değer 2 ile 6 arasında olmalıdır. Okunur **uint8_t**. |
| **uint8_t** [get_Period](./get_period/)() override | Hareketli ortalama trend çizgisi için periyodu belirtir. Diğer trend çizgi varyantlarında göz ardı edilir. Değer 2 ile 255 arasında olmalıdır. Okunur **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | Bu trend çizgisiyle ilgili lejand girdisini temsil eder. Salt okunur [ILegendEntryProperties](../ilegendentryproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Metin biçimini döndürür. Salt okunur [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Zengin formatlı metin içerebilir. Bu özellik null değilse bu formatlı metin değeri veri etiketi için otomatik oluşturulan metni geçersiz kılar. Otomatik oluşturulan veri etiketi metni, ShowSeriesName, ShowValue, ... özellikleriyle yönetilen ve TextFormatManager.TextFormat özelliğiyle biçimlendirilmiş metindir. Salt okunur [ITextFrame](../../aspose.slides/itextframe/). |
| [System::String](../../system/string/) [get_TrendlineName](./get_trendlinename/)() override | Trend çizgisinin adını alır. Okunur [System::String](../../system/string/). |
| [Aspose::Slides::Charts::TrendlineType](../trendlinetype/) [get_TrendlineType](./get_trendlinetype/)() override | Trend çizgisinin tipini alır. Okunur [Charts::TrendlineType](../trendlinetype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_Backward](./set_backward/)(**double**) override | Trend çizgisinin veri serisinin öncesinde uzadığı kategori (veya dağılım grafiğinde birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer herhangi bir sıfırdan büyük ya da eşit değer olmalıdır. Yazılır **double**. |
| void [set_DisplayEquation](./set_displayequation/)(**bool**) override | Trend çizgisinde denklemin (Rsquaredvalue ile aynı etikette) görüntülendiğini belirtir. Yazılır **bool**. |
| void [set_DisplayRSquaredValue](./set_displayrsquaredvalue/)(**bool**) override | Trend çizgisinin R-kare değerinin grafik üzerinde (eşitlik ile aynı etikette) görüntülendiğini belirtir. Yazılır **bool**. |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | Trend çizgisinin biçimini temsil eder. Yazılır [IFormat](../iformat/). |
| void [set_Forward](./set_forward/)(**double**) override | Trend çizgisinin veri serisinin sonrasında uzadığı kategori (veya birim) sayısını belirtir. Dağılım ve dağılım olmayan grafiklerde değer herhangi bir sıfırdan büyük ya da eşit değer olmalıdır. Yazılır **double**. |
| void [set_Intercept](./set_intercept/)(**double**) override | Trend çizgisinin y eksenini kestiği değeri belirtir. Bu özellik yalnızca trend çizgi türü exp, linear veya poly olduğunda desteklenir. Yazılır **double**. |
| void [set_Order](./set_order/)(**uint8_t**) override | Polinom trend çizgisinin derecesini belirtir. Diğer trend çizgi tiplerinde göz ardı edilir. Değer 2 ile 6 arasında olmalıdır. Yazılır **uint8_t**. |
| void [set_Period](./set_period/)(**uint8_t**) override | Hareketli ortalama trend çizgisi için periyodu belirtir. Diğer trend çizgi varyantlarında göz ardı edilir. Değer 2 ile 255 arasında olmalıdır. Yazılır **uint8_t**. |
| void [set_TrendlineName](./set_trendlinename/)([System::String](../../system/string/)) override | Trend çizgisinin adını ayarlar. Yazılır [System::String](../../system/string/). |
| void [set_TrendlineType](./set_trendlinetype/)([Aspose::Slides::Charts::TrendlineType](../trendlinetype/)) override | Trend çizgi tipini ayarlar. Yazılır [Charts::TrendlineType](../trendlinetype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [DomObject](../../aspose.slides/domobject/)
* Sınıf [ITrendline](../itrendline/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)