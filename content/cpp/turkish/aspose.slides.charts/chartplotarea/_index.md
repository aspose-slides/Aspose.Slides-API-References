---
title: ChartPlotArea
second_title: Aspose.Slides for C++ API Referansı
description: Grafiğin çizileceği dikdörtgeni temsil eder.
type: docs
weight: 248
url: /tr/aspose.slides.charts/chartplotarea/
---
## ChartPlotArea sınıfı

Grafiğin çizilmesi gerektiği dikdörtgeni temsil eder.

```cpp
class ChartPlotArea : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                      public Aspose::Slides::Charts::IChartPlotArea
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; ancak IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; ancak IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **float** [get_ActualHeight](./get_actualheight/)() override | Grafik öğesinin gerçek yüksekliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. Okur **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | Grafik öğesinin gerçek genişliğini belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. Okur **float**. |
| **float** [get_ActualX](./get_actualx/)() override | Grafik öğesinin sol üst köşeye göre gerçek x konumunu (sol) belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. Okur **float**. |
| **float** [get_ActualY](./get_actualy/)() override | Grafik öğesinin sol üst köşeye göre gerçek üst konumunu belirtir. Gerçek değerleri almak için önce [IChart::ValidateChartLayout](../ichart/validatechartlayout/) yöntemini çağırın. Okur **float**. |
| **float** [get_Bottom](./get_bottom/)() override | Alt. Salt okunur **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | [Chart](../chart/). Salt okunur [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | Bir çizim alanının biçimini döndürür. Salt okunur [IFormat](../iformat/). |
| **float** [get_Height](./get_height/)() override | Çizim alanı sınırlama kutusunun yüksekliğini, grafiğin yüksekliğine oranı (0 ile 1 arasında) olarak döndürür. Okur **float**. |
| **bool** [get_IsLocationAutocalculated](./get_islocationautocalculated/)() | Konumun nasıl hesaplanacağını tanımlar: true \u2013 otomatik hesaplanır; X, Y, Width, Height özellikleriyle tanımlanır. Salt okunur **bool**. |
| [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() override | Çizim alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik alanı iç kısmına (eksen ve eksen etiketleri hariç) ya da dış kısmına (eksen ve eksen etiketleri dahil) göre yerleştirip yerleştirilmeyeceğini belirtir. Okur [LayoutTargetType](../layouttargettype/). |
| **float** [get_Right](./get_right/)() override | Sağ. Salt okunur **float**. |
| **float** [get_Width](./get_width/)() override | Çizim alanı sınırlama kutusunun genişliğini, grafiğin genişliğine oranı (0 ile 1 arasında) olarak döndürür. Okur **float**. |
| **float** [get_X](./get_x/)() override | Çizim alanı sınırlama kutusunun sol üst köşesinin x koordinatını, grafiğin genişliğine oranı (0 ile 1 arasında) olarak döndürür. Okur **float**. |
| **float** [get_Y](./get_y/)() override | Çizim alanı sınırlama kutusunun sol üst köşesinin y koordinatını, grafiğin yüksekliğine oranı (0 ile 1 arasında) olarak döndürür. Okur **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan tipe bir örnek olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve türev sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve türev sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_Height](./set_height/)(**float**) override | Çizim alanı sınırlama kutusunun yüksekliğini, grafiğin yüksekliğine oranı (0 ile 1 arasında) olarak ayarlar. Yazar **float**. |
| void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) override | Çizim alanının yerleşimi manuel olarak tanımlanmışsa, bu özellik alanı iç kısmına (eksen ve eksen etiketleri hariç) ya da dış kısmına (eksen ve eksen etiketleri dahil) göre yerleştirip yerleştirilmeyeceğini belirtir. Yazar [LayoutTargetType](../layouttargettype/). |
| void [set_Width](./set_width/)(**float**) override | Çizim alanı sınırlama kutusunun genişliğini, grafiğin genişliğine oranı (0 ile 1 arasında) olarak ayarlar. Yazar **float**. |
| void [set_X](./set_x/)(**float**) override | Çizim alanı sınırlama kutusunun sol üst köşesinin x koordinatını, grafiğin genişliğine oranı (0 ile 1 arasında) olarak ayarlar. Yazar **float**. |
| void [set_Y](./set_y/)(**float**) override | Çizim alanı sınırlama kutusunun sol üst köşesinin y koordinatını, grafiğin yüksekliğine oranı (0 ile 1 arasında) olarak ayarlar. Yazar **float**. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n'inci şablon bağımsız değişkenini zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstergeleri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Diğer Bağlantılar

* Sınıf [DomObject](../../aspose.slides/domobject/)
* Sınıf [IChartPlotArea](../ichartplotarea/)
* AdAlanı [Aspose::Slides::Charts](../)
* Kütüphane [Aspose.Slides](../../)