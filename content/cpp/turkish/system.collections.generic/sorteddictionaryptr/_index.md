---
title: SortedDictionaryPtr
second_title: Aspose.Slides için C++ API Referansı
description: Erişim operatörlerine sahip sıralı sözlük işaretçisi. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde allocate edilmeli ve fonksiyonlara değer olarak ya da const referans olarak geçirilmelidir.
type: docs
weight: 534
url: /tr/system.collections.generic/sorteddictionaryptr/
---
## SortedDictionaryPtr sınıf

Erişim operatörlerine sahip sıralı sözlük işaretçisi. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde allocate edilmeli ve fonksiyonlara değer olarak ya da const referans olarak geçirilmelidir.

```cpp
template<typename T,typename V>class SortedDictionaryPtr : public System::SmartPtr<SortedDictionary<T, V>>
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | [begin()](../../system/smartptr/begin/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | [begin()](../../system/smartptr/begin/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi temel tipe static_cast ile dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi türetilmiş tipe dynamic_cast ile dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi türetilmiş tipe dynamic_cast ile dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | [cbegin()](../../system/smartptr/cbegin/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | [cend()](../../system/smartptr/cend/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ [cend()](../../system/smartptr/cend/) metoduna sahip bir özelleştirme türü ise derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | İşaret edilen nesne üzerinde const_cast kullanarak farklı tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | İşaret edilen nesne üzerinde dynamic_cast kullanarak farklı tipe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | [end()](../../system/smartptr/end/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [end](../../system/smartptr/end/)() const | [end()](../../system/smartptr/end/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) metoduna sahip bir özelleştirme türü ise derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | İşaretçi kipini alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşımlı kipte olduğunu varsayar. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut işaretçi dahil olmak üzere kaç tane paylaşımlı işaretçi olduğunu alır. İşaretçinin paylaşımlı kipte olduğunu doğrular. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | İşaret edilen nesne üzerinde [GetHashCode()](../../system/smartptr/gethashcode/) çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Mevcut referans verilen nesneyi (varsa) alır ya da bir istisna fırlatır. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır ya da nullptr döner. [get()](../../system/smartptr/get/) ile aynıdır. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır ya da nullptr döner. [get()](../../system/smartptr/get/) ile aynıdır. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tip ya da onun alt tipi olup olmadığını kontrol eder. C# `is` anlamını izler. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | İşaretçinin sahip olduğu nesne (bir aliasing yapıcı tarafından oluşturulmuş) dışındaki bir nesneye işaret edip etmediğini kontrol eder. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | İşaretçinin paylaşımlı kipte olup olmadığını kontrol eder. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | İşaretçinin zayıf kipte olup olmadığını kontrol eder. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | İşaretçinin null olup olmadığını kontrol eder. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | İşaretçinin null olup olmadığını kontrol eder. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaret edilen nesneye referans alır. İşaretçinin null olmamasını doğrular. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare davranışı sunar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare davranışı sunar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesini taşımalı atar. x artık kullanılamaz. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesini kopya atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesini kopya atar. Gerekli tip dönüşümlerini yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | [SmartPtr](../../system/smartptr/) nesnesine ham işaretçi atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | İşaretçinin nullptr olup olmadığını kontrol eder. |
| V\& [operator[]](./operator[]/)(const T\&) const | Erişim işlevi. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Alias (aliasing yapıcı ile oluşturulmuş) kaldırır, işaretçinin (paylaşımlıysa) yönettiği veya (zayıf ise) izlediği nesnenin aynı olduğundan emin olur. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | İşaretçiyi nullptr'ye yönlendirir. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | İşaretçi kipini ayarlar. Referans verilen nesnenin referans sayısını etkileyebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne (varsa) üzerinde SetTemplateWeakPtr() metodunu çağırır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gereken kipte [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gereken kipte null-pointer [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Belirtilen nesneye işaret eden [SmartPtr](../../system/smartptr/) oluşturur ya da ham işaretçiyi [SmartPtr](../../system/smartptr/)'ye dönüştürür. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya oluşturur. Her iki işaretçi de sonradan aynı nesneye işaret eder. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya oluşturur. Her iki işaretçi de sonradan aynı nesneye işaret eder. İzin veriliyorsa tip dönüşümü yapılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini taşımalı oluşturur. Etkili olarak iki işaretçiyi takas eder, eğer aynı kipte iseler. x çağrı sonrası kullanılamaz olabilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Referans verilen dizi tipini yeni bir dizi oluşturarak farklı tipe dönüştürür. C#'ta desteklenmeyen dizi tip dönüşümleri için yararlıdır. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapılarının çevrilmesi için kullanılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) oluşturur; başlangıç ptr değerinin sahiplik bilgisini paylaşır ancak bağımsız ve yönetilmeyen p işaretçisini tutar. |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)() | Null işaretçi oluşturur. |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedDictionary](../sorteddictionary/)\<T, V\>\>\&) | Belirtilen sıralı sözlüğe işaretçi oluşturur. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak farklı tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../../system/object/) tipine dönüştürür. Pointee_ tipinin tam olması gerekmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ tipi için [System::TypeInfo](../../system/typeinfo/) nesnesini almanın kısayolu. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerekirse, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../system/smartptr/)
* Ad Alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)