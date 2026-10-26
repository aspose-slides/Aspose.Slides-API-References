---
title: PictureFrameLock
second_title: Aspose.Slides for C++ API Referansı
description: Üst PictureFrame üzerinde hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
weight: 4746
url: /tr/aspose.slides/pictureframelock/
---
## PictureFrameLock sınıfı


Determines which operations are disabled on the parent [PictureFrame](../pictureframe/).

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimi kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | Ok uçlarının değiştirilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | Bir şeklin yeniden boyutlandırıldığında en-boy oranını koruması gerekip gerekmediğini belirler. Okuma **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | Görüntü kırpmanın yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | Tüm kilit bayrakları devre dışı bırakılmışsa true döndürür. Salt okunur **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | Bu şeklin hareket ettirilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | Bu şeklin dönme açısının değiştirilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | Şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. Okuma **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Okuma **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansa göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansa göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | Ayarlama değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | Ok uçlarının değiştirilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | Bir şeklin yeniden boyutlandırıldığında en-boy oranını korumasının zorunlu olup olmadığını belirler. Yazma **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | Görüntü kırpmanın yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | Bu şeklin hareket ettirilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | Bu şeklin dönme açısının değiştirilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | Bu şeklin seçilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | Şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. Yazma **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Yazma **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterge (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstergeleri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstergeler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [BaseShapeLock](../baseshapelock/)
* Sınıf [IPictureFrameLock](../ipictureframelock/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)