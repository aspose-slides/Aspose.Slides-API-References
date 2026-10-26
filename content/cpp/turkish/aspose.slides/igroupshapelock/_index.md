---
title: IGroupShapeLock
second_title: Aspose.Slides for C++ API Referansı
description: Üst GroupShape üzerindeki hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
weight: 2497
url: /tr/aspose.slides/igroupshapelock/
---
## IGroupShapeLock sınıfı


Üst [GroupShape](../groupshape/) üzerindeki hangi işlemlerin devre dışı bırakıldığını belirler.

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# biçiminde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# biçiminde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili kullanım amaçları için. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Şeklin yeniden boyutlandırma sırasında en-boy oranını koruyup korumayacağını belirler. Okuma **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Tüm kilit bayrakları devre dışı bırakılmışsa true döndürür. Salt okunur **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bu şeklin taşınmasının yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | Bu grup şeklinin bölünmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımına izin verir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | String durumları için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Şeklin yeniden boyutlandırma sırasında en-boy oranını koruyup korumamasını belirler. Yazma **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bu şeklin taşınmasının yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | Bu grup şeklinin bölünmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçiye (paylaşılan yerine) ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IBaseShapeLock](../ibaseshapelock/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)