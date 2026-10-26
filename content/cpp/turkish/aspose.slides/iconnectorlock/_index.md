---
title: IConnectorLock
second_title: Aspose.Slides için C++ API Referansı
description: Üst Connector üzerinde hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
weight: 1860
url: /tr/aspose.slides/iconnectorlock/
---
## IConnectorLock sınıfı

Üst [Connector](../connector/) üzerinde hangi işlemlerin devre dışı bırakıldığını belirler.

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Ok uçlarının değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bir şeklin yeniden boyutlandırmada en-boy oranını koruması gerekip gerekmediğini belirler. Okunur **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Tüm kilit-bayrakları devre dışı ise true döndürür. Salt-okunur **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | Bu şeklin taşınmasının yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Okunur **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, hedef tip tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Ok uçlarının değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Şeklin yeniden boyutlandırmada en-boy oranını koruması gerekip gerekmediğini belirler. Yaz **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | Bu şeklin taşınmasının yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Diğer Bağlantılar

* Sınıf [IBaseShapeLock](../ibaseshapelock/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)