---
title: IFillFormatEffectiveData
second_title: Aspose.Slides için C++ API Referansı
description: Etkili doldurma biçimlendirme özelliklerini içeren değiştirilemez nesne.
type: docs
weight: 2120
url: /tr/aspose.slides/ifillformateffectivedata/
---
## IFillFormatEffectiveData sınıf

Etkili doldurma biçimlendirme özelliklerini içeren değiştirilemez nesne.

```cpp
class IFillFormatEffectiveData : public Aspose::Slides::IFillParamSource
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece dahili amaçlar için. |
| virtual [Aspose::Slides::FillType](../filltype/) [get_FillType](./get_filltype/)() | Doldurma türünü döndürür. Yalnızca okuma [Slides::FillType](../filltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGradientFormatEffectiveData](../igradientformateffectivedata/)\> [get_GradientFormat](./get_gradientformat/)() | Gradyan doldurma biçimini döndürür. Yalnızca okuma [IGradientFormatEffectiveData](../igradientformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPatternFormatEffectiveData](../ipatternformateffectivedata/)\> [get_PatternFormat](./get_patternformat/)() | Desen doldurma biçimini döndürür. Yalnızca okuma [IPatternFormatEffectiveData](../ipatternformateffectivedata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormatEffectiveData](../ipicturefillformateffectivedata/)\> [get_PictureFillFormat](./get_picturefillformat/)() | Resim doldurma biçimini döndürür. Yalnızca okuma [IPictureFillFormatEffectiveData](../ipicturefillformateffectivedata/). |
| virtual **bool** [get_RotateWithShape](./get_rotatewithshape/)() | Dolgunun şekil ile döndürülüp döndürülmeyeceğini belirler. Yalnızca okuma **bool**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_SolidFillColor](./get_solidfillcolor/)() | Dolgu rengini döndürür. Yalnızca okuma [System::Drawing::Color](../../system.drawing/color/). |
| virtual [SchemeColor](../schemecolor/) [get_SolidFillSchemeColor](./get_solidfillschemecolor/)() | Renk şemasına göre tanımlanan doldurma rengini alır. [SchemeColor::NotDefined](../schemecolor/) değeri, [IFillFormatEffectiveData::get_SolidFillColor](./get_solidfillcolor/)'nın şema rengi olmadığını gösterir. Yalnızca okuma [SchemeColor](../schemecolor/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe ait bir örnek olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemeyi uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referans karşılaştırması, değer tipini nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in stringler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilit açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Açıklamalar

Bu arayüz, [IFillFormat](../ifillformat/) arayüzüyle birlikte, miras uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır. 

## Ayrıca Bakınız

* Sınıf [IFillParamSource](../ifillparamsource/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)