---
title: RC2
second_title: Aspose.Slides for C++ API Referansı
description: "RC2 simetrik algoritma temel sınıfı. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak allocate edilmelidir. Bu tipin bir örneğini yığına (stack) ya da operator new ile oluşturmaktan kaçının; aksi takdirde çalışma zamanı hataları ve/veya assertion hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 365
url: /tr/system.security.cryptography/rc2/
---
## RC2 sınıfı


[RC2](./) simetrik algoritma temel sınıfı. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak allocate edilmelidir. Bu tipin örneğini yığına (stack) ya da operator new ile oluşturmaktan kaçının; aksi takdirde çalışma zamanı hataları ve/veya assert hataları oluşur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin.

```cpp
class RC2 : public System::Security::Cryptography::SymmetricAlgorithm
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | Algoritma örneği oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](../symmetricalgorithm/createdecryptor/)() | Algoritma nesnesiyle ilişkili parametrelerle deşifreleyici oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](../symmetricalgorithm/createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Açık parametrelerle deşifreleyici oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](../symmetricalgorithm/createencryptor/)() | Algoritma nesnesiyle ilişkili parametrelerle şifreleyici oluşturur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](../symmetricalgorithm/createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Açık parametrelerle şifreleyici oluşturur. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | İki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder; IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual void [GenerateIV](../symmetricalgorithm/generateiv/)() | Algoritma için rastgele başlangıç değeri üretir. Mevcut olanı (varsa) geçersiz kılar. |
| virtual void [GenerateKey](../symmetricalgorithm/generatekey/)() | Algoritma için rastgele anahtar üretir. Mevcut olanı (varsa) geçersiz kılar. |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | Kriptografik işlemin blok boyutunu alır. |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | Kriptografik işlemin geribildirim boyutunu alır. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | Kriptografik işlemin başlangıç değerini alır. Henüz oluşturulmamışsa yeni bir değer oluşturur. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | Kriptografik işlemin anahtarını alır. Henüz oluşturulmamışsa yeni bir anahtar oluşturur. |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | Kriptografik işlemin anahtar boyutunu alır. |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | Kriptografik işlemin modunu alır. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | Kriptografik işlemin dolgu (padding) değerini alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin karmalanmasını sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumları için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | Kriptografik işlemin blok boyutunu ayarlar. |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | Kriptografik işlemin geribildirim boyutunu ayarlar. |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Kriptografik işlemin başlangıç değerini ayarlar. |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Kriptografik işlemin anahtarını ayarlar. |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | Kriptografik işlemin anahtar boyutunu ayarlar. |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | Kriptografik işlemin modunu ayarlar. |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | Kriptografik işlemin dolgu (padding) değerini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | Anahtar boyutunun geçerli olup olmadığını kontrol eder. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [SymmetricAlgorithm](../symmetricalgorithm/)
* Ad alanı [System::Security::Cryptography](../)
* Kütüphane [Aspose.Slides](../../)