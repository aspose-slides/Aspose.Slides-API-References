---
title: IDataLabel
second_title: Aspose.Slides C++ API Referansı
description: Bir dizi etiketini temsil eder.
type: docs
weight: 937
url: /tr/aspose.slides.charts/idatalabel/
---
## IDataLabel sınıf

Seri etiketlerini temsil eder.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | TextFrameForOverriding'i, parametredeki \"text\" metniyle başlatır. TextFrameForOverriding zaten başlatılmışsa, yalnızca metnini değiştirir. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | Grafik öğesinin, grafiğin sol üst köşesine göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | Grafik öğesinin, grafiğin sol üst köşesine göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) metodunu çağırın. **float** okunur. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | Grafiğin yüksekliğine oran olarak grafik öğesinin üst kısmını alır. Salt okunur **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | Grafiği döndürür. Salt okunur [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | Veri etiketinin biçimini döndürür. Salt okunur [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | Grafiğin yüksekliğine oran olarak grafik öğesinin yüksekliğini belirtir. **float** okunur. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | False, veri etiketinin görünür olmadığını (ve bu yüzden tüm Show*-bayraklarının (ShowValue, ...) false olduğunu) ifade eder. Salt okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Salt okunur [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | Grafiğin genişliğine oran olarak grafik öğesinin sağ kenarını alır. Salt okunur **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | Temel slaytı döndürür. Salt okunur [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | Grafik metin biçimini döndürür. Salt okunur [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | Zengin biçimlendirilmiş metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri otomatik oluşturulan metnin üzerine yazar. Otomatik oluşturulan metin, veri etiketi, değer ekseninin gösterge birimi etiketi, eksen başlığı, grafik başlığı, trend çizgisi etiketi için örtük bir özelliktir. Otomatik oluşturulan metin [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) özelliğiyle biçimlendirilir. Salt okunur [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | Çalışma kitabı veri hücresini alır. IDataLabelFormat::get(set)_ShowLabelValueFromCell özelliği true ise uygulanır. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | Grafiğin genişliğine oran olarak grafik öğesinin genişliğini belirtir. **float** okunur. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | Grafiğin genişliğine oran olarak grafik öğesinin x konumunu (sol) belirtir. **float** okunur. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | Grafiğin yüksekliğine oran olarak grafik öğesinin üst kısmını belirtir. **float** okunur. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | [DataLabelFormat](../datalabelformat/) ayarlarına veya TextFrameForOverriding.Text değerine göre gerçek etiket metnini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual void [Hide](./hide/)() | Tüm Show*-bayraklarını (ShowValue, ...) false durumuna ayarlayarak veri etiketini gizler. Bu işlemden sonra IsVisible false olur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel türlerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında bir şey kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında bir şey kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | Grafiğin yüksekliğine oran olarak grafik öğesinin yüksekliğini belirtir. **float** yazar. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | Çalışma kitabı veri hücresini ayarlar. IDataLabelFormat::get(set)_ShowLabelValueFromCell özelliği true ise uygulanır. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | Grafiğin genişliğine oran olarak grafik öğesinin genişliğini belirtir. **float** yazar. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | Grafiğin genişliğine oran olarak grafik öğesinin x konumunu (sol) belirtir. **float** yazar. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | Grafiğin yüksekliğine oran olarak grafik öğesinin üst kısmını belirtir. **float** yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Bakınız

* Sınıf [ILayoutable](../ilayoutable/)
* Sınıf [IOverridableText](../ioverridabletext/)
* Sınıf [IActualLayout](../iactuallayout/)
* Ad Alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)