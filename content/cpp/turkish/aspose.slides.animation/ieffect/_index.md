---
title: IEffect
second_title: Aspose.Slides for C++ API Referansı
description: Animasyon etkisini temsil eder.
type: docs
weight: 248
url: /tr/aspose.slides.animation/ieffect/
---
## IEffect sınıfı

Animasyon etkisini temsil eder.

```cpp
class IEffect : public virtual System::Object
```

## Methods

| Method | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmaması gerektiği halde, iki NaN'in eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() | Etki için bir son animasyon rengi tanımlar. [IColorFormat](../../aspose.slides/icolorformat/)'yi oku. |
| virtual [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() | Etki için bir son animasyon türü tanımlar. [AfterAnimationType](../afteranimationtype/)'yi oku. |
| virtual [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() | Etki için bir animasyon metin türü tanımlar. Şekil metni harf, kelime veya bütün olarak animasyonlanabilir. [AnimateTextType](../animatetexttype/)'yi oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) | Belirtilen indeksteki animasyon davranışını döndürür. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() | Etki için davranış koleksiyonunu döndürür. [IBehaviorCollection](../ibehaviorcollection/)'yi oku. |
| virtual **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() | Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. Pozitif bir değer, etki süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye olarak belirtir. **float**'ı oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffect](./)\> [get_Effect](./get_effect/)(**int32_t**) | Belirtilen indeksteki bir dizinin etkisini döndürür. |
| virtual [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() | Etkinin sınıfını tanımlar. [EffectPresetClassType](../effectpresetclasstype/)'yi oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() | Etki için bir diziyi döndürür. Salt okunur [ISequence](../isequence/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() | Etki için gömülü ses tanımlar. [IAudio](../../aspose.slides/iaudio/)'yi oku. |
| virtual **bool** [get_StopPreviousSound](./get_stopprevioussound/)() | Bu öznitelik, animasyon etkisinin önceki sesi durdurup durdurmayacağını belirtir. **bool**'ı oku. |
| virtual [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() | Etkinin alt türünü tanımlar. [EffectSubtype](../effectsubtype/)'yi oku. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() | Etki için hedef şekli döndürür. Salt okunur [IShape](../../aspose.slides/ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() | Metin animasyonunu döndürür. Salt okunur [ITextAnimation](../itextanimation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() | Etki için zamanlama değerini tanımlar. [ITiming](../itiming/)'yi oku. |
| virtual [EffectType](../effecttype/) [get_Type](./get_type/)() | Etkinin türünü tanımlar. [EffectType](../effecttype/)'yi oku. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yöntemine benzer. Özelleştirilmiş nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısına benzer. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörüne benzer. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Direkt çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yöntemine benzer. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referansla karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumuna özgüleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler durumuna özgüleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirli bir değer kadar azaltır. |
| virtual void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) | Etki için bir son animasyon rengi tanımlar. [IColorFormat](../../aspose.slides/icolorformat/)'yi yaz. |
| virtual void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) | Etki için bir son animasyon türü tanımlar. [AfterAnimationType](../afteranimationtype/)'yi yaz. |
| virtual void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) | Etki için bir animasyon metin türü tanımlar. Şekil metni harf, kelime veya bütün olarak animasyonlanabilir. [AnimateTextType](../animatetexttype/)'yi yaz. |
| virtual void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) | Belirtilen indeksteki animasyon davranışını ayarlar. |
| virtual void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) | Etki için davranış koleksiyonunu döndürür. [IBehaviorCollection](../ibehaviorcollection/)'yi yaz. |
| virtual void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) | Animasyonlu metin parçaları (kelimeler veya harfler) arasındaki gecikmeyi tanımlar. Pozitif bir değer, etki süresinin yüzdesini belirtir. Negatif bir değer ise gecikmeyi saniye olarak belirtir. **float**'yi yaz. |
| virtual void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) | Etkinin sınıfını tanımlar. [EffectPresetClassType](../effectpresetclasstype/)'yi yaz. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) | Etki için gömülü ses tanımlar. [IAudio](../../aspose.slides/iaudio/)'yi yaz. |
| virtual void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) | Bu öznitelik, animasyon etkisinin önceki sesi durdurup durdurmayacağını belirtir. **bool**'yi yaz. |
| virtual void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) | Etkinin alt türünü tanımlar. [EffectSubtype](../effectsubtype/)'yi yaz. |
| virtual void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | Etki için zamanlama değerini tanımlar. [ITiming](../itiming/)'yi yaz. |
| virtual void [set_Type](./set_type/)([EffectType](../effecttype/)) | Etkinin türünü tanımlar. [EffectType](../effecttype/)'yi yaz. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf bir işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yöntemine benzer. Özelleştirilmiş nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Direkt çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [Object](../../system/object/)
* Ad Alanı [Aspose::Slides::Animation](../)
* Kütüphane [Aspose.Slides](../../)