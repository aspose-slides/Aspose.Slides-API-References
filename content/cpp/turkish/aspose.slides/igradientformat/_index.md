---
title: IGradientFormat
second_title: Aspose.Slides for C++ API Referansı
description: Bir degrade biçimini temsil eder.
type: docs
weight: 2380
url: /tr/aspose.slides/igradientformat/
---
## IGradientFormat sınıfı

Bir degrade biçimini temsil eder.

```cpp
class IGradientFormat : public Aspose::Slides::IFillParamSource
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türündeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türündeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [Aspose::Slides::GradientDirection](../gradientdirection/) [get_GradientDirection](./get_gradientdirection/)() | Bir degrade stilini döndürür. Okuyun [Slides::GradientDirection](../gradientdirection/). |
| virtual [Aspose::Slides::GradientShape](../gradientshape/) [get_GradientShape](./get_gradientshape/)() | Bir degrade şekilini döndürür. Okuyun [Slides::GradientShape](../gradientshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGradientStop](../igradientstop/)\> [get_GradientStop](./get_gradientstop/)(**int32_t**) | Belirtilen indeksteki bir degrade noktasını döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGradientStopCollection](../igradientstopcollection/)\> [get_GradientStops](./get_gradientstops/)() | Degrade noktalarının koleksiyonunu döndürür. Salt okunur [IGradientStopCollection](../igradientstopcollection/). |
| virtual **float** [get_LinearGradientAngle](./get_lineargradientangle/)() | Bir degrade açısını döndürür. Okuyun **float**. |
| virtual [NullableBool](../nullablebool/) [get_LinearGradientScaled](./get_lineargradientscaled/)() | Bir degrade'in ölçeklendirilip ölçeklendirilmediğini belirler. Okuyun [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Bir degrade için döndürme kipini döndürür. Okuyun [Slides::TileFlip](../tileflip/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneğini temsil edip etmediğini kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şey kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türündeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_GradientDirection](./set_gradientdirection/)([Aspose::Slides::GradientDirection](../gradientdirection/)) | Bir degrade stilini ayarlar. Yazın [Slides::GradientDirection](../gradientdirection/). |
| virtual void [set_GradientShape](./set_gradientshape/)([Aspose::Slides::GradientShape](../gradientshape/)) | Bir degrade şekli ayarlar. Yazın [Slides::GradientShape](../gradientshape/). |
| virtual void [set_LinearGradientAngle](./set_lineargradientangle/)(**float**) | Bir degrade açısını ayarlar. **float**'ı yazın. |
| virtual void [set_LinearGradientScaled](./set_lineargradientscaled/)([NullableBool](../nullablebool/)) | Bir degrade'in ölçekli olup olmadığını belirler. Yazın [NullableBool](../nullablebool/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Bir degrade için döndürme kipini ayarlar. Yazın [Slides::TileFlip](../tileflip/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IFillParamSource](../ifillparamsource/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)