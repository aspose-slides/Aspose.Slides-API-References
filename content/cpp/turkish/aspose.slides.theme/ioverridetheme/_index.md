---
title: IOverrideTheme
second_title: Aspose.Slides for C++ API Referansı
description: Geçersiz kılan bir temayı temsil eder.
type: docs
weight: 391
url: /tr/aspose.slides.theme/ioverridetheme/
---
## IOverrideTheme sınıfı

Represents a overriding theme.

```cpp
class IOverrideTheme : public virtual Aspose::Slides::Theme::ITheme
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual void [Clear](./clear/)() | [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/)'ı null yaparak bu tema nesnesiyle yapılan tüm geçersiz kılmayı devre dışı bırak. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlamında karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamakla birlikte, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamakla birlikte, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ColorFormat](../itheme/get_colorformat/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\> [get_ColorScheme](../itheme/get_colorscheme/)() | Renk şemasını döndürür. Salt okunur [IColorScheme](../icolorscheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\> [get_FontScheme](../itheme/get_fontscheme/)() | Yazı tipi şemasını döndürür. Salt okunur [IFontScheme](../ifontscheme/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\> [get_FormatScheme](../itheme/get_formatscheme/)() | Şekil biçim şemasını döndürür. Salt okunur [IFormatScheme](../iformatscheme/). |
| virtual **bool** [get_IsEmpty](./get_isempty/)() | Doğru değer, [ColorScheme](../colorscheme/), [FontScheme](../fontscheme/), [FormatScheme](../formatscheme/)'nin null olduğu ve bu tema nesnesiyle herhangi bir geçersiz kılmanın devre dışı bırakıldığı anlamına gelir. Salt okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | Sunumu döndürür. Salt okunur [IPresentation](../../aspose.slides/ipresentation/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../ithemeeffectivedata/)\> [GetEffective](../itheme/geteffective/)() | Uygulanan kalıtımla etkili tema verisini alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual void [InitColorScheme](./initcolorscheme/)() | [ColorScheme](../colorscheme/)'yi yeni nesneyle başlat ve InheritedTheme'ın [ColorScheme](../colorscheme/)'ini geçersiz kıl. |
| virtual void [InitColorSchemeFrom](./initcolorschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorScheme](../icolorscheme/)\>) | [ColorScheme](../colorscheme/)'yi yeni nesneyle başlat ve InheritedTheme'ın [ColorScheme](../colorscheme/)'ini geçersiz kıl. |
| virtual void [InitColorSchemeFromInherited](./initcolorschemefrominherited/)() | [ColorScheme](../colorscheme/)'yi yeni nesneyle başlat ve InheritedTheme'ın [ColorScheme](../colorscheme/)'yi geçersiz kıl. Ve bu yeni nesnenin verilerini InheritedTheme'ın [ColorScheme](../colorscheme/) verileriyle başlat. |
| virtual void [InitFontScheme](./initfontscheme/)() | [FontScheme](../fontscheme/)'yi yeni nesneyle başlat ve InheritedTheme'ın [FontScheme](../fontscheme/)'ini geçersiz kıl. |
| virtual void [InitFontSchemeFrom](./initfontschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFontScheme](../ifontscheme/)\>) | [FontScheme](../fontscheme/)'yi yeni nesneyle başlat ve InheritedTheme'ın [FontScheme](../fontscheme/)'sini geçersiz kıl. |
| virtual void [InitFontSchemeFromInherited](./initfontschemefrominherited/)() | [FontScheme](../fontscheme/)'yi yeni nesneyle başlat ve InheritedTheme'ın [FontScheme](../fontscheme/)'sini geçersiz kıl. Ve bu yeni nesnenin verilerini InheritedTheme'ın [FontScheme](../fontscheme/) verileriyle başlat. |
| virtual void [InitFormatScheme](./initformatscheme/)() | [FormatScheme](../formatscheme/)'yi yeni nesneyle başlat ve InheritedTheme'ın [FormatScheme](../formatscheme/)'sini geçersiz kıl. |
| virtual void [InitFormatSchemeFrom](./initformatschemefrom/)([System::SharedPtr](../../system/sharedptr/)\<[IFormatScheme](../iformatscheme/)\>) | [FormatScheme](../formatscheme/)'ı yeni nesneyle başlat ve InheritedTheme'ın [FormatScheme](../formatscheme/)'sini geçersiz kıl. |
| virtual void [InitFormatSchemeFromInherited](./initformatschemefrominherited/)() | [FormatScheme](../formatscheme/)'yu yeni nesneyle başlat ve InheritedTheme'ın [FormatScheme](../formatscheme/)'ini geçersiz kıl. Ve bu yeni nesnenin verilerini InheritedTheme'ın [FormatScheme](../formatscheme/) verileriyle başlat. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Diğer

* Sınıf [ITheme](../itheme/)
* Ad alanı [Aspose::Slides::Theme](../)
* Kütüphane [Aspose.Slides](../../)