---
title: MotionEffect
second_title: Aspose.Slides for C++ API Referansı
description: Efektin hareket etkisi davranışını temsil eder.
type: docs
weight: 469
url: /tr/aspose.slides.animation/motioneffect/
---
## MotionEffect sınıfı

Etkinin hareket etkisi davranışını temsil eder.

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türündeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türündeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı nokta kayan sayı karşılaştırmasını taklit eder; iki NaN değeri eşit kabul edilir, ancak IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı nokta kayan sayı karşılaştırmasını taklit eder; iki NaN değeri eşit kabul edilir, ancak IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | Animasyon davranışlarının birikip birikmediğini temsil eder. [NullableBool](../../aspose.slides/nullablebool/) okunur. |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilmediğini temsil eder. [BehaviorAdditiveType](../behavioradditivetype/) okunur. |
| **float** [get_Angle](./get_angle/)() override | Hareket yolunun göreli açısını tanımlar. **float** okunur. |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | Animasyonun göreli ofset değerini yüzde olarak tanımlar. [System::Drawing::PointF](../../system.drawing/pointf/) okunur. |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | Yüzde cinsinden, animasyonun başlatılacağı x/y koordinatını belirtir. [System::Drawing::PointF](../../system.drawing/pointf/) okunur. |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | Animasyon yolunun kökeninin slayt düzeni ya da ebeveyn gibi neye göre olduğunu belirtir. [MotionOriginType](../motionorigintype/) okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | Animasyon hareketi için yol primitive'ini ve ardından gelen koordinatları belirtir. [IMotionPath](../imotionpath/) okunur. |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. [MotionPathEditMode](../motionpatheditmode/) okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | Davranış özelliklerini temsil eder. Salt-okunur [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | Bir X açısı ile bir hareket yolunu döndürmek için kullanılan dönüş merkezini tanımlar. [System::Drawing::PointF](../../system.drawing/pointf/) okunur. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | Efekt davranışı için zamanlama özelliklerini temsil eder. [ITiming](../itiming/) okunur. |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | Animasyon hareket etkisi için hedef konumu (yüzde) belirtir. [System::Drawing::PointF](../../system.drawing/pointf/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkilendirilmiş referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumuna özgü özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumuna özel bir özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | Animasyon davranışlarının birikip birikmediğini temsil eder. [NullableBool](../../aspose.slides/nullablebool/) yazılır. |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | Geçerli animasyon davranışının diğer çalışan animasyonlarla birleştirilip birleştirilmediğini temsil eder. [BehaviorAdditiveType](../behavioradditivetype/) yazılır. |
| void [set_Angle](./set_angle/)(**float**) override | Hareket yolunun göreli açısını tanımlar. **float** yazılır. |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Animasyonun göreli ofset değerini (yüzde) tanımlar. [System::Drawing::PointF](../../system.drawing/pointf/) yazılır. |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Yüzde cinsinden animasyonun başlatılacağı x/y koordinatını belirtir. [System::Drawing::PointF](../../system.drawing/pointf/) yazılır. |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | Animasyon yolunun kökeninin slayt düzeni ya da ebeveyn gibi neye göre olduğunu belirtir. [MotionOriginType](../motionorigintype/) yazılır. |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | Animasyon hareketi için yol primitive ve ardından gelen koordinatları belirtir. [IMotionPath](../imotionpath/) yazılır. |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | Şekil hareket ettirildiğinde hareket yolunun nasıl hareket ettiğini belirtir. [MotionPathEditMode](../motionpatheditmode/) yazılır. |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Bir X açısı ile bir hareket yolunu döndürmek için kullanılan dönüş merkezini tanımlar. [System::Drawing::PointF](../../system.drawing/pointf/) yazılır. |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | Efekt davranışı için zamanlama özelliklerini temsil eder. [ITiming](../itiming/) yazılır. |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | Animasyon hareket etkisi için hedef konumu (yüzde) belirtir. [System::Drawing::PointF](../../system.drawing/pointf/) yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesine olanak tanır. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [Behavior](../behavior/)
* Sınıf [IMotionEffect](../imotioneffect/)
* AdAlanı [Aspose::Slides::Animation](../)
* Kütüphane [Aspose.Slides](../../)