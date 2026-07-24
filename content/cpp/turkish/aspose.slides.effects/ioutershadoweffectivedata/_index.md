---
title: IOuterShadowEffectiveData
second_title: Aspose.Slides for C++ API Referansı
description: Dış Gölge etkisini temsil eden değiştirilemez nesne.
type: docs
weight: 898
url: /tr/aspose.slides.effects/ioutershadoweffectivedata/
---
## IOuterShadowEffectiveData sınıf

Immutable object which represents an Outer Shadow effect.

```cpp
class IOuterShadowEffectiveData : public virtual Aspose::Slides::Effects::IEffectEffectiveData
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989'da NaN'in hiçbir değerle, NaN dahil, eşit olmadığı belirtilse de, C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN değerinin eşit kabul edildiği, IEC 60559:1989'da NaN'in hiçbir değerle, NaN dahil, eşit olmadığı belirtilse de, C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) yarıçap. Yalnızca okunabilir **double**. |
| virtual **float** [get_Direction](./get_direction/)() | Gölgenin yönü. Yalnızca okunabilir **float**. |
| virtual **double** [get_Distance](./get_distance/)() | Gölgenin mesafesi. Yalnızca okunabilir **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | Dikdörtgen hizalaması. Yalnızca okunabilir [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | Gölgenin şekil ile döndürülüp döndürülmeyeceğini belirtir; şekil döndürülürse gölge de döner. Yalnızca okunabilir **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | Yatay ölçekleme faktörünü belirtir, negatif ölçekleme bir çevrilmeye neden olur. Yalnızca okunabilir **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | Dikey ölçekleme faktörünü belirtir, negatif ölçekleme bir çevrilmeye neden olur. Yalnızca okunabilir **double**. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ShadowColor](./get_shadowcolor/)() | Gölgenin rengi. Yalnızca okunabilir [System::Drawing::Color](../../system.drawing/color/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | Yatay çarpıtma açısını (derece cinsinden) belirtir. Yalnızca okunabilir **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | Dikey çarpıtma açısını (derece cinsinden) belirtir. Yalnızca okunabilir **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz; yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz; yalnızca yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans bazında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans bazında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) işlevinin string ve nullptr durumu için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) işlevinin string durumları için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döner. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IEffectEffectiveData](../ieffecteffectivedata/)
* Ad Alanı [Aspose::Slides::Effects](../)
* Kütüphane [Aspose.Slides](../../)