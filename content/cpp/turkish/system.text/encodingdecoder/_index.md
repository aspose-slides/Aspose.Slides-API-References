---
title: EncodingDecoder
second_title: Aspose.Slides için C++ API Referansı
description: "Kodlama nesnesini kullanarak çözümleme yapan kod çözücü. Bu sınıfın nesneleri yalnızca System::MakeObject() fonksiyonu kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığıta veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr göstericisine sarın ve bu göstericiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 235
url: /tr/system.text/encodingdecoder/
---
## EncodingDecoder sınıf

[Decoder](../decoder/) kodlama nesnesini kullanarak çözümleme yapan. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu kullanılarak ayrılmalıdır. Bu türün örneğini asla yığıt üzerinde ya da new operatörü kullanarak oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
class EncodingDecoder : public System::Text::Decoder
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Convert](./convert/)(const **uint8_t** *, int, char_t *, int, **bool**, int\&, int\&, **bool**\&) override | Baytları karakterlere dönüştürür. |
| void [Convert](./convert/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, **bool**, int\&, int\&, **bool**\&) override | Baytları karakterlere dönüştürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) sözdizimi ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türündeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türündeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece dahili amaçlar için. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_Fallback](../decoder/get_fallback/)() const | Hata işleme geri dönüşünü alır. |
| [DecoderFallbackBufferPtr](../../system/decoderfallbackbufferptr/) [get_FallbackBuffer](../decoder/get_fallbackbuffer/)() const | Geri dönüş tamponunu alır. |
| virtual int [GetCharCount](../decoder/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Bir tamponu çözümlemek için gereken karakter sayısını alır. |
| virtual int [GetCharCount](../decoder/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, **bool**) | Bir tamponu çözümlemek için gereken karakter sayısını alır. |
| virtual int [GetCharCount](../decoder/getcharcount/)(const **uint8_t** *, int, **bool**) | Bir tamponu çözümlemek için gereken karakter sayısını alır. |
| virtual int [GetChars](../decoder/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Bir tamponun çözümlemesinden elde edilen karakterleri al. |
| virtual int [GetChars](../decoder/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int, **bool**) | Bir tamponun çözümlemesinden elde edilen karakterleri al. |
| virtual int [GetChars](../decoder/getchars/)(const **uint8_t** *, int, char_t *, int, **bool**) | Bir tamponun çözümlemesinden elde edilen karakterleri al. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özelleştirilmiş nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTip tarafından tanımlanan tipe ait bir örnek temsil edip etmediğini kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() deyiminin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türündeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [Reset](../decoder/reset/)() | Kod çözücünün dahili durumunu temizler. |
| void [set_Fallback](../decoder/set_fallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Hata işleme geri dönüşünü ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özelleştirilmiş nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() deyiminin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [Decoder](../decoder/)
* Ad alanı [System::Text](../)
* Kütüphane [Aspose.Slides](../../)