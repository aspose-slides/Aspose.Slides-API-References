---
title: AutoShapeLock
second_title: Aspose.Slides for C++ API Referansı
description: Üst AutoshapeEx üzerinde hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
weight: 79
url: /tr/aspose.slides/autoshapelock/
---
## AutoShapeLock sınıfı


Üst AutoshapeEx üzerinde hangi işlemlerin devre dışı bırakıldığını belirler.

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türündeki nesneleri C# stiliyle karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türündeki nesneleri C# stiliyle karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Ok başlarının değiştirilmesinin yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bir şeklin yeniden boyutlandırmada en-boy oranını korumasının zorunlu olup olmadığını belirler. Oku **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Tüm kilitleme bayrakları devre dışı bırakılmışsa true döndürür. Salt-okunur **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bu şeklin taşınmasının yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Bir şeklin tipinin değiştirilmesinin yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Oku **bool**. |
| **bool** [get_TextLocked](./get_textlocked/)() override | Metin düzenlemesinin yasak olup olmadığını belirler. Oku **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hashlenmesini etkinleştirir. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin klonlanmasını etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans açısından karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Ok başlarının değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bir şeklin yeniden boyutlandırmada en-boy oranını korumasının zorunlu olup olmadığını belirler. Yaz **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bu şeklin taşınmasının yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Bir şeklin tipinin değiştirilmesinin yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Yaz **bool**. |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | Metin düzenlemesinin yasak olup olmadığını belirler. Yaz **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin string'e dönüştürülmesini etkinleştirir. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma özelliğini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [BaseShapeLock](../baseshapelock/)
* Sınıf [IAutoShapeLock](../iautoshapelock/)
* İsim uzayı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)