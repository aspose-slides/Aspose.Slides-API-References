---
title: IEffectFormat
second_title: Aspose.Slides için C++ API Referansı
description: Şeklin efekt özelliklerini temsil eder.
type: docs
weight: 2029
url: /tr/aspose.slides/ieffectformat/
---
## IEffectFormat sınıfı


Represents effect properties of shape.

```cpp
class IEffectFormat : public Aspose::Slides::IEffectParamSource
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual void [DisableBlurEffect](./disableblureffect/)() | Bulanıklaştırma etkisini devre dışı bırakır. |
| virtual void [DisableFillOverlayEffect](./disablefilloverlayeffect/)() | Dolgu bindirme etkisini devre dışı bırakır. |
| virtual void [DisableGlowEffect](./disablegloweffect/)() | Parıltı etkisini devre dışı bırakır. |
| virtual void [DisableInnerShadowEffect](./disableinnershadoweffect/)() | İç gölge etkisini devre dışı bırakır. |
| virtual void [DisableOuterShadowEffect](./disableoutershadoweffect/)() | Dış gölge etkisini devre dışı bırakır. |
| virtual void [DisablePresetShadowEffect](./disablepresetshadoweffect/)() | Ön ayarlı gölge etkisini devre dışı bırakır. |
| virtual void [DisableReflectionEffect](./disablereflectioneffect/)() | Yansıma etkisini devre dışı bırakır. |
| virtual void [DisableSoftEdgeEffect](./disablesoftedgeeffect/)() | Yumuşak kenar etkisini devre dışı bırakır. |
| virtual void [EnableFillOverlayEffect](./enablefilloverlayeffect/)() | Dolgu bindirme etkisini etkinleştirir. |
| virtual void [EnableGlowEffect](./enablegloweffect/)() | Parıltı etkisini etkinleştirir. |
| virtual void [EnableInnerShadowEffect](./enableinnershadoweffect/)() | İç gölge etkisini etkinleştirir. |
| virtual void [EnableOuterShadowEffect](./enableoutershadoweffect/)() | Dış gölge etkisini etkinleştirir. |
| virtual void [EnablePresetShadowEffect](./enablepresetshadoweffect/)() | Ön ayarlı gölgeler etkisini etkinleştirir. |
| virtual void [EnableReflectionEffect](./enablereflectioneffect/)() | Yansıma etkisini etkinleştirir. |
| virtual void [EnableSoftEdgeEffect](./enablesoftedgeeffect/)() | Yumuşak kenar etkisini etkinleştirir. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) anlambilimini kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesnelerini C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesnelerini C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\> [get_BlurEffect](./get_blureffect/)() | Bulanıklaştırma etkisi. [Effects::IBlur](../../aspose.slides.effects/iblur/) oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\> [get_FillOverlayEffect](./get_filloverlayeffect/)() | Dolgu bindirme etkisi. [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\> [get_GlowEffect](./get_gloweffect/)() | Parıltı etkisi. [Effects::IGlow](../../aspose.slides.effects/iglow/) oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\> [get_InnerShadowEffect](./get_innershadoweffect/)() | İç gölge. [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) oku. |
| virtual **bool** [get_IsNoEffects](./get_isnoeffects/)() | Tüm etkiler devre dışı bırakılmışsa (yeni oluşturulmuş, varsayılan [EffectFormat](../effectformat/) nesnesi gibi) true döndürür. Salt-okunur **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\> [get_OuterShadowEffect](./get_outershadoweffect/)() | Dış gölge. [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\> [get_PresetShadowEffect](./get_presetshadoweffect/)() | Ön ayarlı gölge. [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\> [get_ReflectionEffect](./get_reflectioneffect/)() | Yansıma. [Effects::IReflection](../../aspose.slides.effects/ireflection/) oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\> [get_SoftEdgeEffect](./get_softedgeeffect/)() | Yumuşak kenar. [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) oku. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayaç veri yapısını alır. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormatEffectiveData](../ieffectformateffectivedata/)\> [GetEffective](./geteffective/)() | Kalıtım uygulanmış etkili biçimlendirme verisini alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini etkinleştirir. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin stringler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_BlurEffect](./set_blureffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IBlur](../../aspose.slides.effects/iblur/)\>) | Bulanıklaştırma etkisi. [Effects::IBlur](../../aspose.slides.effects/iblur/) yaz. |
| virtual void [set_FillOverlayEffect](./set_filloverlayeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/)\>) | Dolgu bindirme etkisi. [Effects::IFillOverlay](../../aspose.slides.effects/ifilloverlay/) yaz. |
| virtual void [set_GlowEffect](./set_gloweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IGlow](../../aspose.slides.effects/iglow/)\>) | Parıltı etkisi. [Effects::IGlow](../../aspose.slides.effects/iglow/) yaz. |
| virtual void [set_InnerShadowEffect](./set_innershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/)\>) | İç gölge. [Effects::IInnerShadow](../../aspose.slides.effects/iinnershadow/) yaz. |
| virtual void [set_OuterShadowEffect](./set_outershadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/)\>) | Dış gölge. [Effects::IOuterShadow](../../aspose.slides.effects/ioutershadow/) yaz. |
| virtual void [set_PresetShadowEffect](./set_presetshadoweffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/)\>) | Ön ayarlı gölge. [Effects::IPresetShadow](../../aspose.slides.effects/ipresetshadow/) yaz. |
| virtual void [set_ReflectionEffect](./set_reflectioneffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::IReflection](../../aspose.slides.effects/ireflection/)\>) | Yansıma. [Effects::IReflection](../../aspose.slides.effects/ireflection/) yaz. |
| virtual void [set_SoftEdgeEffect](./set_softedgeeffect/)([System::SharedPtr](../../system/sharedptr/)\<[Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/)\>) | Yumuşak kenar. [Effects::ISoftEdge](../../aspose.slides.effects/isoftedge/) yaz. |
| virtual void [SetBlurEffect](./setblureffect/)(**double**, **bool**) | Bulanıklaştırma etkisini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini etkinleştirir. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IEffectParamSource](../ieffectparamsource/)
* Ad alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)