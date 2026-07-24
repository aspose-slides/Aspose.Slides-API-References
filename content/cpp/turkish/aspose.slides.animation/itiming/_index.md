---
title: ITiming
second_title: Aspose.Slides for C++ API Referansı
description: Animasyon zamanlamasını temsil eder.
type: docs
weight: 443
url: /tr/aspose.slides.animation/itiming/
---
## ITiming sınıfı


Animasyon zamanlamasını temsil eder.

```cpp
class ITiming : public virtual System::Object
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# stilinde kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# stilinde kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | Süre hızlandırma davranışı etkisinin yüzdesini tanımlar. **float** okunur. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | İleri yönde oynatıldıktan sonra animasyonun ters yönde otomatik olarak oynatılıp oynatılmayacağını tanımlar. **bool** okunur. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | Süre yavaşlatma davranışı etkisinin yüzdesini tanımlar. **float** okunur. |
| virtual **float** [get_Duration](./get_duration/)() | Animasyon etkisinin süresini tanımlar. **float** okunur. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | Etkinin kaç kez tekrarlanması gerektiğini tanımlar. **float** okunur. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | Etkinin kaç kez tekrarlanması gerektiğini tanımlar. **float** okunur. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. **bool** okunur. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. **bool** okunur. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | Etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. [EffectRestartType](../effectrestarttype/) okunur. |
| virtual **bool** [get_Rewind](./get_rewind/)() | Bu öznitelik, etkinin çalındıktan sonra geriye sarılıp sarılmayacağını belirtir. **bool** okunur. |
| virtual **float** [get_Speed](./get_speed/)() | Zamanlamanın ne kadar hızlandırılacağını (veya yavaşlatılacağını) yüzde olarak belirtir. **float** okunur. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | Tetikleyiciden sonraki gecikme süresini tanımlar. **float** okunur. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | Tetikleyici türünü tanımlar. [EffectTriggerType](../effecttriggertype/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yöntemi analogu. Özel nesnelerin karma değer üretmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yöntemi analogu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özel uygulanması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumuna özel uygulanması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | Süre hızlandırma davranışı etkisinin yüzdesini tanımlar. **float** yazılır. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | İleri yönde oynatıldıktan sonra animasyonun ters yönde otomatik olarak oynatılıp oynatılmayacağını tanımlar. **bool** yazılır. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | Süre yavaşlatma davranışı etkisinin yüzdesini tanımlar. **float** yazılır. |
| virtual void [set_Duration](./set_duration/)(**float**) | Animasyon etkisinin süresini tanımlar. **float** yazılır. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | Etkinin kaç kez tekrarlanması gerektiğini tanımlar. **float** yazılır. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | Etkinin kaç kez tekrarlanması gerektiğini tanımlar. **float** yazılır. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | Bu öznitelik, etkinin slayt sonuna kadar tekrarlanıp tekrarlanmayacağını belirtir. **bool** yazılır. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrarlanıp tekrarlanmayacağını belirtir. **bool** yazılır. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | Etkinin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. [EffectRestartType](../effectrestarttype/) yazılır. |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | Bu öznitelik, etkinin çalındıktan sonra geriye sarılıp sarılmayacağını belirtir. **bool** yazılır. |
| virtual void [set_Speed](./set_speed/)(**float**) | Zamanlamanın ne kadar hızlandırılacağını (veya yavaşlatılacağını) yüzde olarak belirtir. **float** yazılır. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | Tetikleyiciden sonraki gecikme süresini tanımlar. **float** yazılır. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | Tetikleyici türünü tanımlar. [EffectTriggerType](../effecttriggertype/) yazılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yöntemi analogu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca

* Sınıf [Object](../../system/object/)
* Ad alanı [Aspose::Slides::Animation](../)
* Kütüphane [Aspose.Slides](../../)