---
title: GroupShapeLock
second_title: Aspose.Slides for C++ API Referansı
description: Üst GroupShape üzerindeki hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
weight: 1210
url: /tr/aspose.slides/groupshapelock/
---
## GroupShapeLock sınıfı

Üst [GroupShape](../groupshape/) üzerinde hangi işlemlerin devre dışı bırakıldığını belirler.

```cpp
class GroupShapeLock : public Aspose::Slides::BaseShapeLock,
                       public Aspose::Slides::IGroupShapeLock
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamakla birlikte, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamakla birlikte, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Şeklin yeniden boyutlandırma sırasında en boy oranını koruyup korumaması gerektiğini belirler. Okur **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Okur **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Tüm kilit bayrakları devre dışı bırakılmışsa true döndürür. Salt okunur **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bu şeklin hareket ettirilmesinin yasak olup olmadığını belirler. Okur **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Okur **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Okur **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Okur **bool**. |
| **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() override | Bu grup şeklinin bölünmesinin yasak olup olmadığını belirler. Okur **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını (klonlanmasını) sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Şeklin yeniden boyutlandırma sırasında en boy oranını koruyup korumaması gerektiğini belirler. **bool** yazar. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. **bool** yazar. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bu şeklin hareket ettirilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bu şeklin seçilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. **bool** yazar. |
| void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) override | Bu grup şeklinin bölünmesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kaplardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [BaseShapeLock](../baseshapelock/)
* Sınıf [IGroupShapeLock](../igroupshapelock/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)