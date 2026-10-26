---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides için C++ API Referansı
description: "Temsilcilerin bir koleksiyonunu temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer veya referans olarak geçilmelidir. Bu tipin nesnelerini yönetmek için System::SmartPtr sınıfını asla kullanmayın."
type: docs
weight: 1093
url: /tr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> sınıfı

Delegelerin bir koleksiyonunu temsil eder. Bu tip yığıt üzerinde ayrılmalı ve fonksiyonlara değer ya da referans olarak geçilmelidir. Bu tipin nesnelerini yönetmek için asla [System::SmartPtr](../smartptr/) sınıfını kullanmayın.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| ReturnType | Koleksiyondaki her temsilcinin işaret ettiği çağrılabilir varlıkların dönüş tipi |
| ArgumentTypes | Koleksiyondaki her temsilcinin işaret ettiği çağrılabilir varlıkların argüman listesi |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | UYGULANMADI. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Belirtilen temsilciyi koleksiyona ekler. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Belirtilen fonksiyon nesnesini temsilci koleksiyonuna ekler. Fonksiyon nesnesi, koleksiyona eklenmeden önce Callback temsilci tipine dönüştürülür. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Belirtilen MulticastDelegate nesnesini temsilci koleksiyonuna ekler. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Belirtilen nesnenin belirtilen statik olmayan metodunu temsilci koleksiyonuna ekler. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Belirtilen nesnenin belirtilen statik olmayan metodunu temsilci koleksiyonuna ekler. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Belirtilen temsilciyi temsilci koleksiyonundan kaldırır. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Belirtilen nesnenin belirtilen statik olmayan metodunu temsilci koleksiyonundan kaldırır. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Belirtilen nesnenin belirtilen statik olmayan metodunu temsilci koleksiyonundan kaldırır. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Belirtilen MulticastDelegate nesnesini temsilci koleksiyonundan kaldırır. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Tüm temsilcileri temsilci koleksiyonundan kaldırır. |
| **bool** [empty](./empty/)() const | Temsilci koleksiyonunun boş olup olmadığını belirler. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | UYGULANMADI. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Şu anda temsilci koleksiyonunda bulunan tüm temsilcileri çağırır. Temsilciler, koleksiyona eklenme sırasına göre çağrılır. Metot, temsilciler yürütülürken bloke olur. |
| **bool** [IsNull](./isnull/)() const | Temsilci koleksiyonunun boş olup olmadığını belirler. |
|  [MulticastDelegate](./multicastdelegate/)() | Boş bir koleksiyon oluşturur. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Varsayılan yapıcıya eşdeğerdir. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Temsilci koleksiyonunun yüzeysel kopyasını gerçekleştirir. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Taşıma yapıcı. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Bir örnek oluşturur ve belirtilen temsilciyi temsilci koleksiyonuna ekler. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Bir örnek oluşturur ve belirtilen değeri temsilci koleksiyonuna ekler. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Bir örnek oluşturur ve belirtilen değeri temsilci koleksiyonuna ekler. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Temsilci koleksiyonunun boş olmadığını belirler. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | İki MulticastDelegate örneğinin - mevcut nesne ve belirtilen nesne - eşit olmadığını belirler. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Şu anda temsilci koleksiyonunda bulunan tüm temsilcileri çağırır. Temsilciler, koleksiyona eklenme sırasına göre çağrılır. Operatör, temsilciler yürütülürken bloke olur. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Belirtilen temsilciyi koleksiyona ekler. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Belirtilen temsilciyi temsilci koleksiyonundan kaldırır. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Belirtilen nesnenin temsil ettiği temsilci koleksiyonunu mevcut nesneye atar. Sonuç olarak her iki nesne de aynı temsilci koleksiyonuna işaret eder. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Taşıma atama operatörü. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Temsilci koleksiyonunun boş olup olmadığını belirler. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | İki MulticastDelegate örneğinin - mevcut nesne ve belirtilen nesne - eşit olup olmadığını belirler. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Boş (aslında bir şey çağırmayan) içerideki geri aramaları temizler. |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | [TypeInfo](../typeinfo/) nesnesine bir referans döndürür; bu nesne MulticastDelegate sınıf tipi bilgisini temsil eder. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Yıkıcı. |

## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [Callback](./callback/) | MulticastDelegate sınıfı tarafından temsil edilen temsilcilerin tipidir. |
| [Function](./function/) | Temsilci imzası ile ilişkili fonksiyonun tipidir. |

## Diğer Bilgiler

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)