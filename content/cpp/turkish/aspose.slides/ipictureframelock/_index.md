---
title: IPictureFrameLock
second_title: Aspose.Slides for C++ API Referansı
description: Üst PictureFrameEx üzerinde hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
weight: 3264
url: /tr/aspose.slides/ipictureframelock/
---
## IPictureFrameLock sınıf

Üst PictureFrameEx üzerindeki hangi işlemlerin devre dışı bırakıldığını belirler.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN’ın eşit kabul edildiği C#-stilinde kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN’ın eşit kabul edildiği C#-stilinde çift hassasiyetli kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Ok ucu değişikliklerinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bir şeklin yeniden boyutlandırma sırasında en-boy oranını korumasının gerekip gerekmediğini belirler. Okunur **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | Görsel kırpılmasının yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Tüm kilitleme bayrakları devre dışı bırakılmışsa true döndürür. Salt-okunur **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bu şeklin taşınmasının yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | Bu şeklin dönme açısının değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Bir şeklin tipinin değiştirilmesinin yasak olup olmadığını belirler. Okunur **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Okunur **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'ın string durumları için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Ok ucu değişikliklerinin yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Şeklin yeniden boyutlandırma sırasında en-boy oranını korumasının gerekip gerekmediğini belirler. Yazılabilir **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | Görsel kırpılmasının yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bu şeklin taşınmasının yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | Bu şeklin dönme açısının değiştirilmesinin yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Bir şeklin tipinin değiştirilmesinin yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Yazılabilir **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'inci template argümanını paylaşımlı yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [IBaseShapeLock](../ibaseshapelock/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)