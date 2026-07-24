---
title: IChartTitle
second_title: Aspose.Slides for C++ API Referansı
description: Grafik başlığı özelliklerini temsil eder.
type: docs
weight: 911
url: /tr/aspose.slides.charts/icharttitle/
---
## IChartTitle sınıf


Grafik başlığı özelliklerini temsil eder.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | TextFrameForOverriding'i \"text\" parametresindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa sadece metnini değiştirir. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Grafiğin sol üst köşesine göre grafik öğesinin gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Grafiğin sol üst köşesine göre grafik öğesinin gerçek üst kısmını belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Grafiğin yüksekliğinin bir kesri olarak grafik öğesinin üst kısmını alır. Salt okunur **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Grafiği döndürür. Salt okunur [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | Bir başlığın doldurma, çizgi, efekt stillerini döndürür. Salt okunur [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Grafiğin yüksekliğinin bir kesri olarak grafik öğesinin yüksekliğini belirtir. **float** okunur. |
| virtual **bool** [get_Overlay](./get_overlay/)() | Diğer grafik öğelerinin başlığın üzerine geçmesine izin verilip verilmeyeceğini belirler. **bool** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Salt okunur [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Grafiğin genişliğinin bir kesri olarak grafik öğesinin sağını alır. Salt okunur **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Temel slaytı döndürür. Salt okunur [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Grafik metin biçimini döndürür. Salt okunur [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Zengin biçimlendirilmiş metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri otomatik oluşturulan metnin üzerine yazar. Otomatik oluşturulan metin, veri etiketi, değer ekseninin gösterge birimi etiketi, eksen başlığı, grafik başlığı, trend çizgi etiketi gibi örtük bir özelliktir. Otomatik oluşturulan metin [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) özelliğiyle biçimlendirilir. Salt okunur [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Grafiğin genişliğinin bir kesri olarak grafik öğesinin genişliğini belirtir. **float** okunur. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Grafiğin genişliğinin bir kesri olarak grafik öğesinin x konumunu (sol) belirtir. **float** okunur. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Grafiğin yüksekliğinin bir kesri olarak grafik öğesinin üst kısmını belirtir. **float** okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun eşdeğeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının eşdeğeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün eşdeğeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun eşdeğeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un string ve nullptr durumu için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un string durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Grafiğin yüksekliğinin bir kesri olarak grafik öğesinin yüksekliğini belirtir. **float** yazar. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | Diğer grafik öğelerinin başlığın üzerine geçmesine izin verilip verilmeyeceğini belirler. **bool** yazar. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Grafiğin genişliğinin bir kesri olarak grafik öğesinin genişliğini belirtir. **float** yazar. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Grafiğin genişliğinin bir kesri olarak grafik öğesinin x konumunu (sol) belirtir. **float** yazar. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Grafiğin yüksekliğinin bir kesri olarak grafik öğesinin üst kısmını belirtir. **float** yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun eşdeğeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [ILayoutable](../ilayoutable/)
* Sınıf [IOverridableText](../ioverridabletext/)
* Sınıf [IActualLayout](../iactuallayout/)
* Ad Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)