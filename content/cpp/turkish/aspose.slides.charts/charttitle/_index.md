---
title: ChartTitle
second_title: Aspose.Slides için C++ API Referansı
description: Grafik başlığı özelliklerini temsil eder.
type: docs
weight: 326
url: /tr/aspose.slides.charts/charttitle/
---
## ChartTitle sınıf

Grafik başlığı özelliklerini temsil eder.

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | TextFrameForOverriding'i parametre \"text\" içindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa, yalnızca metnini değiştirir. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değere, NaN dahil, eşit olmaması gerekirken, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| **float** [get_ActualX](./get_actualx/)() override | Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| **float** [get_ActualY](./get_actualy/)() override | Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| **float** [get_Bottom](./get_bottom/)() override | Alt. Yalnızca okunabilir **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Üst grafik nesnesini döndürür. Yalnızca okunabilir [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Başlığın dolgu, çizgi, efekt stillerini döndürür. Yalnızca okunabilir [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Başlığın yüksekliğini grafiğin yüksekliğinin bir kesri olarak döndürür. **float** okunur. |
| **bool** [get_Overlay](./get_overlay/)() override | Diğer grafik öğelerinin başlığın üzerine gelmesine izin verilip verilmeyeceğini belirler. **bool** okunur. |
| **float** [get_Right](./get_right/)() override | Sağ. Yalnızca okunabilir **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Metin biçimini döndürür. Yalnızca okunabilir [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Zengin biçimlendirilmiş metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri otomatik oluşturulan metnin üzerine yazar. Otomatik oluşturulan metin, veri etiketi, değer ekseninin görüntü birimi etiketi, eksen başlığı, grafik başlığı, trend çizgisi etiketi gibi öğelerin örtük bir özelliğidir. Otomatik oluşturulan metin [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) özelliğiyle biçimlendirilir. Yalnızca okunabilir [ITextFrame](../../aspose.slides/itextframe/). |
| **float** [get_Width](./get_width/)() override | Başlığın genişliğini grafiğin genişliğinin bir kesri olarak döndürür. **float** okunur. |
| **float** [get_X](./get_x/)() override | Başlığın x koordinatını grafiğin genişliğinin bir kesri olarak döndürür. **float** okunur. |
| **float** [get_Y](./get_y/)() override | Başlığın y koordinatını grafiğin yüksekliğinin bir kesri olarak döndürür. **float** okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından açıklanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesnesini nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un dize durumu için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Height](./set_height/)(**float**) override | Başlığın yüksekliğini grafiğin yüksekliğinin bir kesri olarak ayarlar. **float** yazılır. |
| void [set_Overlay](./set_overlay/)(**bool**) override | Diğer grafik öğelerinin başlığın üzerine gelmesine izin verilip verilmeyeceğini belirler. **bool** yazılır. |
| void [set_Width](./set_width/)(**float**) override | Başlığın genişliğini grafiğin genişliğinin bir kesri olarak ayarlar. **float** yazılır. |
| void [set_X](./set_x/)(**float**) override | Başlığın x koordinatını grafiğin genişliğinin bir kesri olarak ayarlar. **float** yazılır. |
| void [set_Y](./set_y/)(**float**) override | Başlığın y koordinatını grafiğin yüksekliğinin bir kesri olarak ayarlar. **float** yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [IChartTitle](../icharttitle/)
* Sınıf [IDOMObject](../../aspose.slides/idomobject/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)