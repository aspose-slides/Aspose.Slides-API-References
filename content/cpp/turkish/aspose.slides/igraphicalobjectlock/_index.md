---
title: IGraphicalObjectLock
second_title: Aspose.Slides için C++ API Referansı
description: Üst GraphicalObjectEx üzerindeki hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
weight: 2471
url: /tr/aspose.slides/igraphicalobjectlock/
---
## IGraphicalObjectLock sınıfı

Üst GraphicalObjectEx üzerindeki hangi işlemlerin devre dışı bırakıldığını belirler.

```cpp
class IGraphicalObjectLock : public virtual Aspose::Slides::IBaseShapeLock
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'da NaN'in hiçbir değere, NaN dahil, eşit olmadığı belirtilse de, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'da NaN'in hiçbir değere, NaN dahil, eşit olmadığı belirtilse de, iki NaN'in eşit kabul edildiği C# tarzı çift kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | Şeklin yeniden boyutlandırıldığında en-boy oranını koruyup korumayacağını belirler. Okuma **bool**. |
| virtual **bool** [get_DrilldownLocked](./get_drilldownlocked/)() | Bu nesnenin alt şekillerinin seçilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | Tüm kilit bayrakları devre dışı bırakıldıysa true döndürür. Yalnızca-okunur **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | Bu şeklin taşınmasının yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Okuma **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin karmalanmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumları için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Stringler durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | Şeklin yeniden boyutlandırıldığında en-boy oranını koruyup korumayacağını belirler. Yazma **bool**. |
| virtual void [set_DrilldownLocked](./set_drilldownlocked/)(**bool**) | Bu nesnenin alt şekillerinin seçilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | Bu şeklin taşınmasının yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını ortak (shared) yerine zayıf (weak) işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IBaseShapeLock](../ibaseshapelock/)
* İsim Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)