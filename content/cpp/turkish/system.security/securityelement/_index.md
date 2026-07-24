---
title: SecurityElement
second_title: Aspose.Slides for C++ API Referansı
description: "Güvenlik nesnesini kodlamak için XML nesne modeli. Gerçeklenmemiştir. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün bir örneğini yığına (stack) veya new operatörüyle oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 40
url: /tr/system.security/securityelement/
---
## SecurityElement sınıfı


Güvenlik nesnesini kodlamak için XML nesne modeli. Gerçeklenmemiştir. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün bir örneğini yığına (stack) veya new operatörüyle oluşturmaktan kaçının; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkabilir. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class SecurityElement : public System::Object
```

## Yöntemler

| Method | Description |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Etikete öznitelik ekler. |
| void [AddChild](./addchild/)([SecurityElement](./)) | Alt etiketi ekler. |
| [String](../../system/string/) [Attribute](./attribute/)(const [String](../../system/string/)\&) | Öznitelik değerini alır. |
| [SecurityElement](./) [Copy](./copy/)() | Etiketi klonlar. |
| **bool** [Equal](./equal/)([SecurityElement](./)) | Parametrelerin eşitliğini kontrol eder. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Objeleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static [String](../../system/string/) [Escape](./escape/)(const [String](../../system/string/)\&) | XML dizesindeki karakterleri kaçış karakteriyle yazar. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| static [SecurityElement](./) [FromString](./fromstring/)(const [String](../../system/string/)\&) | XML kodundan öğe oluşturur. |
| [System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\> [get_Attributes](./get_attributes/)() | Etiket özniteliklerini alır. |
| [System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\> [get_Children](./get_children/)() | Etiket alt nesnelerini alır. |
| [String](../../system/string/) [get_Tag](./get_tag/)() | Etiket adını alır. |
| [String](../../system/string/) [get_Text](./get_text/)() | Etiket iç metnini alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yöntemine benzer. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısına benzer. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörüne benzer. |
| static **bool** [IsValidAttributeName](./isvalidattributename/)(const [String](../../system/string/)\&) | Öznitelik adının geçerli olup olmadığını kontrol eder. |
| static **bool** [IsValidAttributeValue](./isvalidattributevalue/)(const [String](../../system/string/)\&) | Öznitelik değerinin geçerli olup olmadığını kontrol eder. |
| static **bool** [IsValidTag](./isvalidtag/)(const [String](../../system/string/)\&) | Etiketin geçerli olup olmadığını kontrol eder. |
| static **bool** [IsValidText](./isvalidtext/)(const [String](../../system/string/)\&) | Metnin geçerli olup olmadığını kontrol eder. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yöntemine benzer. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) nin dize durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| [SecurityElement](./) [SearchForChildByTag](./searchforchildbytag/)(const [String](../../system/string/)\&) | İsimle alt etiketi alır. |
| [String](../../system/string/) [SearchForTextOfTag](./searchfortextoftag/)(const [String](../../system/string/)\&) | Etiket adıyla alt etiket iç metnini alır. |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&) | Yapıcı. |
|  [SecurityElement](./securityelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Yapıcı. |
| void [set_Attributes](./set_attributes/)([System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\>) | Etiket özniteliklerini ayarlar. |
| void [set_Children](./set_children/)([System::Collections::Generic::List](../../system.collections.generic/list/)\<[SecurityElement](./)\>) | Etiket alt nesnelerini ayarlar. |
| void [set_Tag](./set_tag/)(const [String](../../system/string/)\&) | Etiket adını ayarlar. |
| void [set_Text](./set_text/)(const [String](../../system/string/)\&) | Etiket iç metnini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki işaretçilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Etiketi dizeye dönüştürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* İsim Alanı [System::Security](../)
* Kütüphane [Aspose.Slides](../../)