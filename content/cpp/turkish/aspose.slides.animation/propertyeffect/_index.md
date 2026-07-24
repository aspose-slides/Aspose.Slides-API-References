---
title: PropertyEffect
second_title: Aspose.Slides for C++ API Referansı
description: Özellik etkisi davranışını temsil eder.
type: docs
weight: 521
url: /tr/aspose.slides.animation/propertyeffect/
---
## PropertyEffect sınıfı


Özellik etkisi davranışını temsil eder.

```cpp
class PropertyEffect : public Aspose::Slides::Animation::Behavior,
                       public Aspose::Slides::Animation::IPropertyEffect
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) sözdizimi kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | Animasyon davranışlarının birikip birikmediğini gösterir. [NullableBool](../../aspose.slides/nullablebool/)'ı okuyun. |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilmediğini gösterir. [BehaviorAdditiveType](../behavioradditivetype/)'ı okuyun. |
| [System::String](../../system/string/) [get_By](./get_by/)() override | Animasyonun başlangıç öncesindeki konumuna göre göreceli bir ofset değeri belirtir. [System::String](../../system/string/)'ı okuyun. |
| [PropertyCalcModeType](../propertycalcmodetype/) [get_CalcMode](./get_calcmode/)() override | Animasyonun ara değerleme modunu belirtir. [PropertyCalcModeType](../propertycalcmodetype/)'ı okuyun. |
| [System::String](../../system/string/) [get_From](./get_from/)() override | Animasyonun başlangıç değerini belirtir. [System::String](../../system/string/)'ı okuyun. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPoint](../ipoint/)\> [get_Point](./get_point/)(**int32_t**) override | Belirtilen indeksde animasyon noktasını döndürür. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\> [get_Points](./get_points/)() override | Animasyon noktalarını belirtir. [IPointCollection](../ipointcollection/)'ı okuyun. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | Davranışın özelliklerini temsil eder. Salt okunur [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | Etki davranışı için zamanlama özelliklerini temsil eder. [ITiming](../itiming/)'ı okuyun. |
| [System::String](../../system/string/) [get_To](./get_to/)() override | Animasyonun bitiş değerini belirtir. [System::String](../../system/string/)'ı okuyun. |
| [PropertyValueType](../propertyvaluetype/) [get_ValueType](./get_valuetype/)() override | Bir özellik değerinin tipini belirtir. [PropertyValueType](../propertyvaluetype/)'ı okuyun. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
|  [PropertyEffect](./propertyeffect/)() |  |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | Animasyon davranışlarının birikip birikmediğini gösterir. [NullableBool](../../aspose.slides/nullablebool/)'a yazın. |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilmediğini gösterir. [BehaviorAdditiveType](../behavioradditivetype/)'a yazın. |
| void [set_By](./set_by/)([System::String](../../system/string/)) override | Animasyonun başlangıç öncesindeki konumuna göre göreceli bir ofset değeri belirtir. [System::String](../../system/string/)'a yazın. |
| void [set_CalcMode](./set_calcmode/)([PropertyCalcModeType](../propertycalcmodetype/)) override | Animasyonun ara değerleme modunu belirtir. [PropertyCalcModeType](../propertycalcmodetype/)'a yazın. |
| void [set_From](./set_from/)([System::String](../../system/string/)) override | Animasyonun başlangıç değerini belirtir. [System::String](../../system/string/)'a yazın. |
| void [set_Points](./set_points/)([System::SharedPtr](../../system/sharedptr/)\<[IPointCollection](../ipointcollection/)\>) override | Animasyon noktalarını belirtir. [IPointCollection](../ipointcollection/)'a yazın. |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Etki davranışı için zamanlama özelliklerini temsil eder. [ITiming](../itiming/)'a yazın. |
| void [set_To](./set_to/)([System::String](../../system/string/)) override | Animasyonun bitiş değerini belirtir. [System::String](../../system/string/)'a yazın. |
| void [set_ValueType](./set_valuetype/)([PropertyValueType](../propertyvaluetype/)) override | Bir özellik değerinin tipini belirtir. [PropertyValueType](../propertyvaluetype/)'a yazın. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) ayarlar. Kaplardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Ayrıca Bakınız

* Sınıf [Behavior](../behavior/)
* Sınıf [IPropertyEffect](../ipropertyeffect/)
* İsim Uzayı [Aspose::Slides::Animation](../)
* Kütüphane [Aspose.Slides](../../)