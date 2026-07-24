---
title: IColorFormat
second_title: Aspose.Slides for C++ API Referansı
description: Sunumda kullanılan bir rengi temsil eder.
type: docs
weight: 1691
url: /tr/aspose.slides/icolorformat/
---
## IColorFormat sınıfı

Represents a color used in a presentation.

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | Renk formatını "color" öğesinden kopyalar. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **uint8_t** [get_B](./get_b/)() | Bir rengin mavi bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **uint8_t**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | Uygulanan tüm renk dönüşümleriyle sonuç rengi döndürür. RGB renklerini ayarlar ve tüm renk dönüşümlerini siler. Okur [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | Belirtilen dizindeki renge uygulanan renk dönüşüm işlemini döndürür. Okuma/yazma [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | Bir renge uygulanan renk dönüşümlerinin koleksiyonunu döndürür. Salt-okunur [IColorOperationCollection](../icoloroperationcollection/). |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | Renk tanımlama yöntemini döndürür. Okur [Slides::ColorType](../colortype/). |
| virtual **float** [get_FloatB](./get_floatb/)() | Bir rengin mavi bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **float**. |
| virtual **float** [get_FloatG](./get_floatg/)() | Bir rengin yeşil bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **float**. |
| virtual **float** [get_FloatR](./get_floatr/)() | Bir rengin kırmızı bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **float**. |
| virtual **uint8_t** [get_G](./get_g/)() | Bir rengin yeşil bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **uint8_t**. |
| virtual **float** [get_Hue](./get_hue/)() | HSL temsili bir rengin ton bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **float**. |
| virtual **float** [get_Luminance](./get_luminance/)() | HSL temsili bir rengin parlaklık bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **float**. |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | Renk ön ayarını döndürür. Okur [Slides::PresetColor](../presetcolor/). |
| virtual **uint8_t** [get_R](./get_r/)() | Bir rengin kırmızı bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **uint8_t**. |
| virtual **float** [get_Saturation](./get_saturation/)() | HSL temsili bir rengin doygunluk bileşenini döndürür. Tüm renk dönüşümleri yoksayılır. Okur **float**. |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | Renk şeması tarafından tanımlanan rengi döndürür. Okur [Slides::SchemeColor](../schemecolor/). |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | Sistem renk tablosu tarafından tanımlanan rengi döndürür. Okur [Slides::SystemColor](../systemcolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcüsü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin çoğaltılmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, yalnızca yeni nesneyi başlatır ve türev sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, yalnızca yeni nesneyi başlatır ve türev sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans-karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Dize ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Dize durumları için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_B](./set_b/)(**uint8_t**) | Bir rengin mavi bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **uint8_t**. |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | Uygulanan tüm renk dönüşümleriyle sonuç rengi ayarlar. RGB renklerini ayarlar ve tüm renk dönüşümlerini siler. Yazar [System::Drawing::Color](../../system.drawing/color/). |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | Belirtilen dizindeki renge uygulanan renk dönüşüm işlemini ayarlar. Okuma/yazma [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | Renk tanımlama yöntemini ayarlar. Yazar [Slides::ColorType](../colortype/). |
| virtual void [set_FloatB](./set_floatb/)(**float**) | Bir rengin mavi bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **float**. |
| virtual void [set_FloatG](./set_floatg/)(**float**) | Bir rengin yeşil bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **float**. |
| virtual void [set_FloatR](./set_floatr/)(**float**) | Bir rengin kırmızı bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **float**. |
| virtual void [set_G](./set_g/)(**uint8_t**) | Bir rengin yeşil bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **uint8_t**. |
| virtual void [set_Hue](./set_hue/)(**float**) | HSL temsili bir rengin ton bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **float**. |
| virtual void [set_Luminance](./set_luminance/)(**float**) | HSL temsili bir rengin parlaklık bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **float**. |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | Renk ön ayarını ayarlar. Yazar [Slides::PresetColor](../presetcolor/). |
| virtual void [set_R](./set_r/)(**uint8_t**) | Bir rengin kırmızı bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **uint8_t**. |
| virtual void [set_Saturation](./set_saturation/)(**float**) | HSL temsili bir rengin doygunluk bileşenini ayarlar. Tüm renk dönüşümleri yoksayılır. Yazar **float**. |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | Renk şeması tarafından tanımlanan rengi ayarlar. Yazar [Slides::SchemeColor](../schemecolor/). |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | Sistem renk tablosu tarafından tanımlanan rengi ayarlar. Yazar [Slides::SystemColor](../systemcolor/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeyi sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | Mevcut renk formatını temsil eden bir [System::String](../../system/string/) döndürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcüsü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Class [IFillParamSource](../ifillparamsource/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)