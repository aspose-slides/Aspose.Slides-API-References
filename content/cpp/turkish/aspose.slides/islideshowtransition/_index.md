---
title: ISlideShowTransition
second_title: Aspose.Slides for C++ API Referansı
description: Slayt gösterisi geçişini temsil eder.
type: docs
weight: 3810
url: /tr/aspose.slides/islideshowtransition/
---
## ISlideShowTransition sınıfı


Slayt gösterisi geçişini temsil eder.

```cpp
class ISlideShowTransition : public virtual System::Object
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türündeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türündeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN’ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. Okur **bool**. |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. Bu ayar advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmemişse otomatik ilerleme olmayacağı varsayılır. Okur **uint32_t**. |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | Fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. Bu öznitelik belirtilmemişse true değeri varsayılır. Okur **bool**. |
| virtual **int32_t** [get_Duration](./get_duration/)() | Slayt geçiş efekti süresini milisaniye cinsinden alır. **int32_t** okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | Gömülü ses verisini döndürür. [IAudio](../iaudio/) okunur. |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, oluşturan uygulama bu sesin yerleşik sesler listesindeki name özniteliğini kontrol etmeye uyarılır ve gerektiğinde özel bir ad ya da UI sunabilir. Okur **bool**. |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayı gerçekleşene kadar döngü yapıp yapmayacağını belirtir. Okur **bool**. |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | Slayt geçişi için ses modunu ayarlar veya döndürür. [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) okunur. |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | Geçiş sesinin insan tarafından okunabilir adını belirtir. Ses adını alıp ayarlamak için [ISlideShowTransition::set_Sound](./set_sound/) atanmalıdır. [System::String](../../system/string/) okunur. |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | Mevcut slayttan bir sonraki slayta geçişte kullanılacak geçiş hızını belirtir. [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) okunur. |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | Geçiş tipi. [TransitionType](../../aspose.slides.slideshow/transitiontype/) okunur. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) göster geçiş değeri. Salt-okunur [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlemesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType ile tanımlanan tipe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel türlerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumları için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | Bu öznitelik, slayt gösterisinin belirli bir süreden sonra bir sonraki slayta geçip geçmeyeceğini belirtir. **bool** yazar. |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | Geçişin başlaması gereken zamanı milisaniye cinsinden belirtir. Bu ayar advClick özniteliğiyle birlikte kullanılabilir. Bu öznitelik belirtilmemişse otomatik ilerleme olmayacağı varsayılır. **uint32_t** yazar. |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | Fare tıklamasının slaytı ilerletip ilerletmeyeceğini belirtir. Bu öznitelik belirtilmemişse true değeri varsayılır. **bool** yazar. |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | Slayt geçiş efekti süresini milisaniye cinsinden ayarlar. **int32_t** yazar. |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | Gömülü ses verisini ayarlar. [IAudio](../iaudio/) yazar. |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | Bu sesin yerleşik bir ses olup olmadığını belirtir. Bu öznitelik true olarak ayarlanırsa, oluşturan uygulama bu sesin yerleşik sesler listesindeki name özniteliğini kontrol etmeye uyarılır ve gerektiğinde özel bir ad ya da UI sunabilir. **bool** yazar. |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | Bu öznitelik, sesin slayt gösterisinde bir sonraki ses olayı gerçekleşene kadar döngü yapıp yapmayacağını belirtir. **bool** yazar. |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | Slayt geçişi için ses modunu ayarlar veya döndürür. [TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) yazar. |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | Geçiş sesinin insan tarafından okunabilir adını belirtir. Ses adını alıp ayarlamak için [ISlideShowTransition::set_Sound](./set_sound/) atanmalıdır. [System::String](../../system/string/) yazar. |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | Mevcut slayttan bir sonraki slayta geçişte kullanılacak geçiş hızını belirtir. [TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) yazar. |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | Geçiş tipi. [TransitionType](../../aspose.slides.slideshow/transitiontype/) yazar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını bir zayıf işaretçi olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)