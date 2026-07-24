---
title: TripleDESManaged
second_title: Aspose.Slides for C++ API Referansı
description: "Yönetilen TripleDES uygulaması. Yalnızca None doldurma ile ECB ve CFB modlarını ve None, Zeros ve PKCS7 doldurmalarına sahip CBC modunu destekler. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini asla yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 690
url: /tr/system.security.cryptography/tripledesmanaged/
---
## TripleDESManaged sınıfı


Yönetilen [TripleDES](../tripledes/) uygulaması. Yalnızca ECB ve CFB modlarını None doldurma ile ve CBC modunu None, Zeros ve PKCS7 doldurmalarıyla destekler. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini asla yığıt üzerinde veya new operatörü kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class TripleDESManaged : public System::Security::Cryptography::TripleDES
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | Algoritma örneği oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Açık parametrelerle şifre çözücü nesnesi oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | Algoritma nesnesi tarafından tanımlanan parametrelerle şifre çözücü nesnesi oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Algoritma nesnesi tarafından tanımlanan parametrelerle şifre çözücü nesnesi oluşturur. |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Açık parametrelerle şifreleyici nesnesi oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | Algoritma nesnesi tarafından tanımlanan parametrelerle şifreleyici nesnesi oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Algoritma nesnesi tarafından tanımlanan parametrelerle şifreleyici nesnesi oluşturur. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı çift duyarlıklı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [GenerateIV](./generateiv/)() override | Rastgele bir başlangıç değeri oluşturur ve algoritmanın iç yapısına kaydeder. |
| void [GenerateKey](./generatekey/)() override | Rastgele bir anahtar oluşturur ve algoritmanın iç yapısına kaydeder. |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | Kriptografik işlemin blok boyutunu alır. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | Kriptografik işlemin geri besleme boyutunu alır. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | Kriptografik işlemin başlangıç değerini alır. Henüz oluşturulmadıysa yeni oluşturur. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | Kriptografik işlemin anahtarını alır. Henüz oluşturulmadıysa yeni oluşturur. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | Kriptografik işlemin anahtar boyutunu alır. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | Kriptografik işlemin modunu alır. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | Kriptografik işlemin doldurmasını alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | Kriptografik işlemin blok boyutunu ayarlar. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | Kriptografik işlemin geri besleme boyutunu ayarlar. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Kriptografik işlemin başlangıç değerini ayarlar. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Kriptografik işlemin anahtarını ayarlar. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | Kriptografik işlemin anahtar boyutunu ayarlar. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | Kriptografik işlemin modunu ayarlar. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | Kriptografik işlemin doldurmasını ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlemci nesnesini kullanın. |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | Anahtar boyutunun geçerli olup olmadığını denetler. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [TripleDES](../tripledes/)
* Ad alanı [System::Security::Cryptography](../)
* Kütüphane [Aspose.Slides](../../)