---
title: Timing
second_title: Aspose.Slides C++ API Referansı
description: Animasyon zamanlamasını temsil eder.
type: docs
weight: 625
url: /tr/aspose.slides.animation/timing/
---
## Timing sınıfı


Represents animation timing.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipinde nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipinde nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'in eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'in eşit kabul edildiği C#-tarzı çift duyarlıklı kayan nokta karşılaştırmasını taklit eder, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **float** [get_Accelerate](./get_accelerate/)() override | Hızlandırma davranışı etkisinin sürenin yüzdesini açıklar. **float** okunur. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | İleri yönde oynatıldıktan sonra animasyonun ters yönde otomatik oynatılıp oynatılmayacağını açıklar. **bool** okunur. |
| **float** [get_Decelerate](./get_decelerate/)() override | Yavaşlatma davranışı etkisinin sürenin yüzde oranını açıklar. **float** okunur. |
| **float** [get_Duration](./get_duration/)() override | Animasyon etkisinin süresini açıklar. **float** okunur. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | Efektin tekrarlanması gereken sayısını açıklar. **float** okunur. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | Efektin tekrarlanması gereken sayısını açıklar. **float** okunur. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | Bu öznitelik, etkinin slayt sonuna kadar tekrar edip etmeyeceğini belirtir. **bool** okunur. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. **bool** okunur. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | Bir efektin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. [EffectRestartType](../effectrestarttype/) okunur. |
| **bool** [get_Rewind](./get_rewind/)() override | Bu öznitelik, etkinin oynatımı tamamlandığında geri sarılıp sarılmayacağını belirtir. **bool** okunur. |
| **float** [get_Speed](./get_speed/)() override | Zamanlamayı ne kadar hızlandırmak (veya yavaşlatmak) istediğinizi yüzde olarak belirtir. **float** okunur. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | Tetikleyiciden sonraki gecikme süresini açıklar. **float** okunur. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | Tetikleme tipini açıklar. [EffectTriggerType](../effecttriggertype/) okunur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedef tip tarafından tanımlanan bir örnek olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipinde nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | Hızlandırma davranışı etkisinin sürenin yüzdesini açıklar. **float** yazar. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | İleri yönde oynatıldıktan sonra animasyonun ters yönde otomatik oynatılıp oynatılmayacağını açıklar. **bool** yazar. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | Yavaşlatma davranışı etkisinin sürenin yüzde oranını açıklar. **float** yazar. |
| void [set_Duration](./set_duration/)(**float**) override | Animasyon etkisinin süresini açıklar. **float** yazar. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | Efektin tekrarlanması gereken sayısını açıklar. **float** yazar. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | Efektin tekrarlanması gereken sayısını açıklar. **float** yazar. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | Bu öznitelik, etkinin slayt sonuna kadar tekrar edip etmeyeceğini belirtir. **bool** yazar. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | Bu öznitelik, etkinin bir sonraki tıklamaya kadar tekrar edip etmeyeceğini belirtir. **bool** yazar. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | Bir efektin tamamlandıktan sonra yeniden başlatılıp başlatılmayacağını belirtir. [EffectRestartType](../effectrestarttype/) yazar. |
| void [set_Rewind](./set_rewind/)(**bool**) override | Bu öznitelik, etkinin oynatımı tamamlandığında geri sarılıp sarılmayacağını belirtir. **bool** yazar. |
| void [set_Speed](./set_speed/)(**float**) override | Zamanlamayı ne kadar hızlandırmak (veya yavaşlatmak) istediğinizi yüzde olarak belirtir. **float** yazar. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | Tetikleyiciden sonraki gecikme süresini açıklar. **float** yazar. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | Tetikleme tipini açıklar. [EffectTriggerType](../effecttriggertype/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçi (paylaşılan yerine) ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [ITiming](../itiming/)
* Sınıf [IDOMObject](../../aspose.slides/idomobject/)
* İsim Uzayı [Aspose::Slides::Animation](../)
* Kütüphane [Aspose.Slides](../../)