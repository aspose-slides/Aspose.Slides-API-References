---
title: ColorFormat
second_title: Aspose.Slides için C++ API Referansı
description: Bir sunumda kullanılan bir rengi temsil eder.
type: docs
weight: 339
url: /tr/aspose.slides/colorformat/
---
## ColorFormat sınıfı

Bir sunumda kullanılan bir rengi temsil eder.

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## Yöntemler

| Method | Description |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | "color" kaynağından renk biçimini kopyalar. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Belirtilen nesneyle eşitliği kontrol eder. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değerle, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değerle, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| **uint8_t** [get_B](./get_b/)() override | Bir rengin mavi bileşenini döndürür. Tüm renk dönüşümleri göz ardı edilir. **uint8_t** okur. |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | Uygulanan tüm renk dönüşümleriyle elde edilen rengi döndürür. RGB renklerini ayarlar ve tüm renk dönüşümlerini temizler. [System::Drawing::Color](../../system.drawing/color/) okur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | Belirtilen indeksteki renge uygulanan renk dönüşüm işlemini döndürür. [Aspose::Slides::IColorOperation](../icoloroperation/) okuma/yazma. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | Bir renge uygulanan renk dönüşümlerinin koleksiyonunu döndürür. [IColorOperationCollection](../icoloroperationcollection/) yalnızca okuma. |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | Renk tanımlama yöntemini döndürür. [Slides::ColorType](../colortype/) okur. |
| **float** [get_FloatB](./get_floatb/)() override | Bir rengin mavi bileşenini döndürür. Tüm renk dönüşümleri göz ardı edilir. **float** okur. |
| **float** [get_FloatG](./get_floatg/)() override | Bir rengin yeşil bileşenini döndürür. Tüm renk dönüşümleri göz ardı edilir. **float** okur. |
| **float** [get_FloatR](./get_floatr/)() override | Bir rengin kırmızı bileşenini döndürür. Tüm renk dönüşümleri göz ardı edilir. **float** okur. |
| **uint8_t** [get_G](./get_g/)() override | Bir rengin yeşil bileşenini döndürür. Tüm renk dönüşümleri göz ardı edilir. |
| **float** [get_Hue](./get_hue/)() override | HSL temsiliyle bir rengin ton bileşenini döndürür. Tüm renk dönüşümleri göz ardı edilir. **float** okur. |
| **float** [get_Luminance](./get_luminance/)() override | HSL temsiliyle bir rengin parlaklık bileşenini döndürür. Tüm renk dönüşümleri göz ardı eder. **float** okur. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate nesnesini döndürür. [IDOMObject](../idomobject/) yalnızca okuma. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Üst [IPresentationComponent](../ipresentationcomponent/) nesnesini döndürür. [IPresentationComponent](../ipresentationcomponent/) yalnızca okuma. |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | Renk ön ayarını döndürür. [Slides::PresetColor](../presetcolor/) okur. |
| **uint8_t** [get_R](./get_r/)() override | Bir rengin kırmızı bileşenini döndürür. Tüm renk dönüşümleri göz ardı edilir. **uint8_t** okur. |
| **float** [get_Saturation](./get_saturation/)() override | HSL temsiliyle bir rengin doygunluk bileşenini döndürür. Tüm renk dönüşümleri göz ardı edilir. **float** okur. |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | Bir renk şemasına göre tanımlanan rengi döndürür. [Slides::SchemeColor](../schemecolor/) okur. |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | Sistem renk tablosuna göre tanımlanan rengi döndürür. [Slides::SystemColor](../systemcolor/) okur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Karma kodunu döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcı ile oluşturulmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcı ile oluşturulmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleşmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumu için özelleşmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_B](./set_b/)(**uint8_t**) override | Bir rengin mavi bileşenini ayarlar. Tüm renk dönüşümleri göz ardı edilir. **uint8_t** yazar. |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | Uygulanan tüm renk dönüşümleriyle elde edilen rengi döndürür. RGB renklerini ayarlar ve tüm renk dönüşümlerini temizler. [System::Drawing::Color](../../system.drawing/color/) yazar. |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | Belirtilen indeksteki renge uygulanan renk dönüşüm işlemini ayarlar. [Aspose::Slides::IColorOperation](../icoloroperation/) okuma/yazma. |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | Renk tanımlama yöntemini ayarlar. [Slides::ColorType](../colortype/) yazar. |
| void [set_FloatB](./set_floatb/)(**float**) override | Bir rengin mavi bileşenini ayarlar. Tüm renk dönüşümleri göz ardı edilir. **float** yazar. |
| void [set_FloatG](./set_floatg/)(**float**) override | Bir rengin yeşil bileşenini ayarlar. Tüm renk dönüşümleri göz ardı edilir. **float** yazar. |
| void [set_FloatR](./set_floatr/)(**float**) override | Bir rengin kırmızı bileşenini ayarlar. Tüm renk dönüşümleri göz ardı edilir. **float** yazar. |
| void [set_G](./set_g/)(**uint8_t**) override | Bir rengin yeşil bileşenini ayarlar. Tüm renk dönüşümleri göz ardı edilir. |
| void [set_Hue](./set_hue/)(**float**) override | HSL temsiliyle bir rengin ton bileşenini ayarlar. Tüm renk dönüşümleri göz ardı edilir. **float** yazar. |
| void [set_Luminance](./set_luminance/)(**float**) override | HSL temsiliyle bir rengin parlaklık bileşenini ayarlar. Tüm renk dönüşümleri göz ardı edilir. **float** yazar. |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | Renk ön ayarını ayarlar. [Slides::PresetColor](../presetcolor/) yazar. |
| void [set_R](./set_r/)(**uint8_t**) override | Bir rengin kırmızı bileşenini ayarlar. Tüm renk dönüşümleri göz ardı edilir. **uint8_t** yazar. |
| void [set_Saturation](./set_saturation/)(**float**) override | HSL temsiliyle bir rengin doygunluk bileşenini ayarlar. Tüm renk dönüşümleri göz ardı eder. **float** yazar. |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | Renk şemasına göre tanımlanan rengi ayarlar. [Slides::SchemeColor](../schemecolor/) yazar. |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | Sistem renk tablosuna göre tanımlanan rengi ayarlar. [Slides::SystemColor](../systemcolor/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf bir gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının şu anki değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | Mevcut renk biçimini temsil eden bir [System::String](../../system/string/) döndürür. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özelleştirilmiş nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [PVIObject](../pviobject/)
* Sınıf [IColorFormat](../icolorformat/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)