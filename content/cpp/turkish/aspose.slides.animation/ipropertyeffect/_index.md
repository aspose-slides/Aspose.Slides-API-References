---
title: IPropertyEffect
second_title: Aspose.Slides için C++ API Referansı
description: Özellik etkisi davranışını temsil eder.
type: docs
weight: 339
url: /tr/aspose.slides.animation/ipropertyeffect/
---
## IPropertyEffect sınıf

Özellik etkisi davranışını temsil eder.

```cpp
class IPropertyEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimi kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesnelerini karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesnelerini karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN değeri eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | Animasyon davranışlarının birikip birikmediğini temsil eder. [NullableBool](../../aspose.slides/nullablebool/) okunur. |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilmediğini temsil eder. [BehaviorAdditiveType](../behavioradditivetype/) okunur. |
| virtual [System::String](../../system/string/) [get_By](./get_by/)() | Animasyonun başlangıçtan önceki konumuna göre göreli ofset değerini belirler. [System::String](../../system/string/) okunur. |
| virtual [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() | Animasyon için ara değerleme modunu belirtir. [PropertyCalcModeType](../propertycalcmodetype/) okunur. |
| virtual [System::String](../../system/string/) [get_From](./get_from/)() | Animasyonun başlangıç değerini belirler. [System::String](../../system/string/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) | Belirtilen indekste animasyonun bir noktasını döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() | Animasyonun noktalarını belirler. [IPointCollection](../ipointcollection/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | Davranışın özelliklerini temsil eder. Salt okunur [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | Etki davranışı için zamanlama özelliklerini temsil eder. [ITiming](../itiming/) okunur. |
| virtual [System::String](../../system/string/) [get_To](./get_to/)() | Animasyonun bitiş değerini belirler. [System::String](../../system/string/) okunur. |
| virtual [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() | Bir özellik değerinin tipini belirler. [PropertyValueType](../propertyvaluetype/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin karma oluşturmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şey kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string ve nullptr durumu için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string durumları için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | Animasyon davranışlarının birikip birikmediğini temsil eder. [NullableBool](../../aspose.slides/nullablebool/) yazılır. |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilmediğini temsil eder. [BehaviorAdditiveType](../behavioradditivetype/) yazılır. |
| virtual void [set_By](./set_by/)([System::String](../../system/string/)) | Animasyonun başlangıçtan önceki konumuna göre göreli ofset değerini belirler. [System::String](../../system/string/) yazılır. |
| virtual void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) | Animasyon için ara değerleme modunu belirler. [PropertyCalcModeType](../propertycalcmodetype/) yazılır. |
| virtual void [set_From](./set_from/)([System::String](../../system/string/)) | Animasyonun başlangıç değerini belirler. [System::String](../../system/string/) yazılır. |
| virtual void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) | Animasyonun noktalarını belirler. [IPointCollection](../ipointcollection/) yazılır. |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | Etki davranışı için zamanlama özelliklerini temsil eder. [ITiming](../itiming/) yazılır. |
| virtual void [set_To](./set_to/)([System::String](../../system/string/)) | Animasyonun bitiş değerini belirler. [System::String](../../system/string/) yazılır. |
| virtual void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) | Bir özellik değerinin tipini belirler. [PropertyValueType](../propertyvaluetype/) yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IBehavior](../ibehavior/)
* Ad alanı [Aspose::Slides::Animation](../)
* Kütüphane [Aspose.Slides](../../)