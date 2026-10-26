---
title: IAutoShapeLock
second_title: C++ için Aspose.Slides API Referansı
description: Üst AutoshapeEx üzerinde hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
weight: 1379
url: /tr/aspose.slides/iautoshapelock/
---
## IAutoShapeLock sınıf

Ebeveyn AutoshapeEx üzerindeki hangi işlemlerin devre dışı bırakıldığını belirler.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Yöntemler

| Metod | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmadığına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmadığına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | Ok uçlarının değiştirilmesinin yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Bir şeklin yeniden boyutlandırılırken en-boy oranını korumasının gerekip gerekmediğini belirler. **bool** okur. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Tüm kilit bayrakları devre dışı bırakıldıysa true döner. Salt okunur **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bu şeklin taşınmasının yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bu şeklin seçilmesinin yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | Bir şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. **bool** okur. |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | Metin düzenlemesinin yasak olup olmadığını belirler. **bool** okur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun bir benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının bir benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün bir benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun bir benzeri. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | Ok uçlarının değiştirilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Bir şeklin yeniden boyutlandırılırken en-boy oranını korumasının gerekip gerekmediğini belirler. **bool** yazar. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bu şeklin taşınmasının yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bu şeklin seçilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | Bir şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | Metin düzenlemesinin yasak olup olmadığını belirler. **bool** yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstergelerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun bir benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler ve ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IBaseShapeLock](../ibaseshapelock/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)