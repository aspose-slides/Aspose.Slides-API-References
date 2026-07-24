---
title: DataLabel
second_title: Aspose.Slides for C++ API Referansı
description: Seri etiketlerini temsil eder.
type: docs
weight: 365
url: /tr/aspose.slides.charts/datalabel/
---
## DataLabel sınıfı

Seri etiketlerini temsil eder.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | Parametre "text" içindeki metinle TextFrameForOverriding'i başlatır. TextFrameForOverriding zaten başlatılmışsa, sadece metnini değiştirir. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | [DataLabel](./) sınıfının yeni bir örneğini oluşturur. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. **float** okunur. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. **float** okunur. |
| **float** [get_ActualX](./get_actualx/)() override | Grafik öğesinin sol üst köşe göreli gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. **float** okunur. |
| **float** [get_ActualY](./get_actualy/)() override | Grafik öğesinin sol üst köşe göreli gerçek üst konumunu belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. **float** okunur. |
| **float** [get_Bottom](./get_bottom/)() override | Alt. **float** sadece okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | Üst grafik nesnesini döndürür. [IChart](../ichart/) sadece okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | Veri etiketi biçimini döndürür. [IDataLabelFormat](../idatalabelformat/) sadece okunur. |
| **float** [get_Height](./get_height/)() override | Başlığın yüksekliğini, grafiğin yüksekliğine oran olarak döndürür. **float** okunur. |
| **bool** [get_IsVisible](./get_isvisible/)() override | False, veri etiketinin görünür olmadığını (ve böylece tüm Show* bayraklarının (ShowValue, ...) false olduğunu) gösterir. **bool** sadece okunur. |
| **float** [get_Right](./get_right/)() override | Sağ. **float** sadece okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | Metin biçimini döndürür. [IChartTextFormat](../icharttextformat/) sadece okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | Zengin biçimli metin içerebilir. Bu özellik null değilse, bu biçimli metin değeri veri etiketinin otomatik oluşturulan metninin üzerine yazar. Otomatik oluşturulan veri etiketi metni, ShowSeriesName, ShowValue, ... özellikleri tarafından yönetilen ve TextFormatManager.TextFormat özelliğiyle biçimlendirilmiş metindir. [ITextFrame](../../aspose.slides/itextframe/) sadece okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | Çalışma kitabı veri hücresini alır. IDataLabelFormat::get(set)_ShowLabelValueFromCell özelliği true ise uygulanır. |
| **float** [get_Width](./get_width/)() override | Başlığın genişliğini, grafiğin genişliğine oran olarak döndürür. **float** okunur. |
| **float** [get_X](./get_x/)() override | Başlığın x koordinatını, grafiğin genişliğine oran olarak döndürür. **float** okunur. |
| **float** [get_Y](./get_y/)() override | Başlığın y koordinatını, grafiğin yüksekliğine oran olarak döndürür. **float** okunur. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | [DataLabelFormat](../datalabelformat/) ayarları veya [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text() değerine dayalı gerçek etiket metnini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| void [Hide](./hide/)() override | Tüm Show* bayraklarını (ShowValue, ...) false olarak ayarlayarak veri etiketini gizler. IsVisible bundan sonra false olacaktır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni bir nesne başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni bir nesne başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Height](./set_height/)(**float**) override | Başlığın yüksekliğini, grafiğin yüksekliğine oran olarak ayarlar. **float** yazılır. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | Çalışma kitabı veri hücresini ayarlar. IDataLabelFormat::get(set)_ShowLabelValueFromCell özelliği true ise uygulanır. |
| void [set_Width](./set_width/)(**float**) override | Başlığın genişliğini, grafiğin genişliğine oran olarak ayarlar. **float** yazılır. |
| void [set_X](./set_x/)(**float**) override | Başlığın x koordinatını, grafiğin genişliğine oran olarak ayarlar. **float** yazılır. |
| void [set_Y](./set_y/)(**float**) override | Başlığın y koordinatını, grafiğin yüksekliğine oran olarak ayarlar. **float** yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit kaldırmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Sınıf [IDataLabel](../idatalabel/)
* Sınıf [IDOMObject](../../aspose.slides/idomobject/)
* Ad alanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)