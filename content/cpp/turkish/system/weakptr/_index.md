---
title: WeakPtr
second_title: Aspose.Slides için C++ API Referansı
description: "Yapıcıda kendisini zayıf moda ayarlayan System::SmartPtr sınıfının alt sınıfı. Lütfen bu sınıfın örneğinin her zaman zayıf modda kalacağını garanti etmediğini, çünkü set_Mode() hâlâ erişilebilir olduğunu unutmayın. Bu tip, başka bir nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da sabit referansla geçirilmelidir."
type: docs
weight: 1496
url: /tr/system/weakptr/
---
## WeakPtr sınıfı

[System::SmartPtr](../smartptr/) sınıfının alt sınıfı, yapıcıda kendisini zayıf moda ayarlar. Lütfen bu sınıfın örneğinin her zaman zayıf modda kalacağını garanti etmediğini, çünkü [set_Mode()](../smartptr/set_mode/) hâlâ erişilebilir olduğunu unutmayın. Bu tip, başka bir nesnenin silinmesini yönetmek için bir işaretçidir. Yığın (stack) üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da sabit referansla geçirilmelidir.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İşaret edilen tip. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| auto [begin](../smartptr/begin/)() | [begin()](../smartptr/begin/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [begin()](../smartptr/begin/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| auto [begin](../smartptr/begin/)() const | [begin()](../smartptr/begin/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [begin()](../smartptr/begin/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | İşaretçiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | İşaretçiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| auto [cbegin](../smartptr/cbegin/)() const | [cbegin()](../smartptr/cbegin/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [cbegin()](../smartptr/cbegin/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| auto [cend](../smartptr/cend/)() const | [cend()](../smartptr/cend/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [cend()](../smartptr/cend/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | İşaret edilen nesne üzerinde const_cast kullanarak farklı tipe dönüştürür. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | İşaret edilen nesne üzerinde dynamic_cast kullanarak farklı tipe dönüştürür. |
| auto [end](../smartptr/end/)() | [end()](../smartptr/end/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [end()](../smartptr/end/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| auto [end](../smartptr/end/)() const | [end()](../smartptr/end/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [end()](../smartptr/end/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| **bool** [expired](./expired/)() const | Başvurulan nesnenin zaten silinip silinmediğini kontrol eder. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | İşaretçi modunu alır. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşımlı modda olduğunu varsayar. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Başvurulan nesneye ait mevcut paylaşımlı işaretçi sayısını (geçerli işaretçi dahil) alır. Geçerli işaretçinin paylaşımlı modda olduğunu varsayar. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Başvurulan nesneyi alır. İşaretçinin zayıf modda olduğunu varsayar. |
| int [GetHashCode](../smartptr/gethashcode/)() const | [GetHashCode()](../smartptr/gethashcode/) yöntemini işaret edilen nesne üzerinde çağırır. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Mevcut başvurulan nesneyi (varsa) alır veya bir istisna fırlatır. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](../smartptr/get/) ile aynı davranışa sahiptir. |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Başvurulan nesneyi alır. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](../smartptr/get/) ile aynı davranışa sahiptir. |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipte ya da onun alt tipinde olup olmadığını kontrol eder. C# `is` anlamını takip eder. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | İşaretçinin sahip olduğu nesne (aliasing yapıcıyla oluşturulan) dışındaki bir nesneye işaret edip etmediğini kontrol eder. |
| **bool** [IsShared](../smartptr/isshared/)() const | İşaretçinin paylaşımlı modda olup olmadığını kontrol eder. |
| **bool** [IsWeak](../smartptr/isweak/)() const | İşaretçinin zayıf modda olup olmadığını kontrol eder. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | İşaretçinin null olup olmadığını kontrol eder. |
| **bool** [operator!](../smartptr/operator_not/)() const | İşaretçinin null olup olmadığını kontrol eder. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | İşaret edilen nesneye referans alır. İşaretçinin null olmadığını varsayar. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Başvurulan nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | [SmartPtr](../smartptr/) sınıfı için “küçük” karşılaştırma semantiği sağlar. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | [SmartPtr](../smartptr/) sınıfı için “küçük” karşılaştırma semantiği sağlar. |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Zayıf işaretçiye değer atar. SmartPtr_ özel atama operatörüne çağrı yapar. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | [SmartPtr](../smartptr/) nesnesini taşıyarak atar. x kullanılamaz hâle gelir. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | [SmartPtr](../smartptr/) nesnesini kopyalayarak atar. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | [SmartPtr](../smartptr/) nesnesini kopyalayarak atar. Gerekli tip dönüşümleri yapılır. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | [SmartPtr](../smartptr/) nesnesine ham işaretçi atar. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Zayıf işaretçinin null olup olmadığını kontrol eder. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Alias (aliasing yapıcıyla oluşturulan) işaretçiyi kaldırır, işaretçinin (paylaşımlıysa) yönettiği ya da (zayıfsa) izlediği nesnenin aynı olmasını sağlar. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../smartptr/reset/)() | İşaretçiyi nullptr’a yönlendirir. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | İşaretçi modunu ayarlar. Başvurulan nesnenin referans sayısını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne (varsa) üzerinde SetTemplateWeakPtr() yöntemini çağırır. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Gerekli modda bir [SmartPtr](../smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Gerekli modda null işaretçi [SmartPtr](../smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Belirtilen nesneye işaret eden bir [SmartPtr](../smartptr/) oluşturur ya da ham işaretçiyi [SmartPtr](../smartptr/) tipine dönüştürür. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) nesnesini kopya yapıcıyla oluşturur. Her iki işaretçi de aynı nesneye işaret eder. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) nesnesini kopya yapıcıyla oluşturur. Her iki işaretçi de aynı nesneye işaret eder. İzin verildiğinde tip dönüşümü yapılır. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) nesnesini taşıma yapıcıyla oluşturur. İki işaretçi aynı modda ise yer değiştirir. x çağrı sonrası kullanılamaz hâle gelebilir. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Referans alınan dizinin tipini, farklı tipte yeni bir dizi oluşturarak dönüştürür. C#’ta desteklenmeyen dizi tip dönüşümleri için yararlıdır. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) oluşturur; ptr’ın ilk değerindeki sahiplik bilgilerini paylaşır, ancak ilişkili olmayan ve yönetilmeyen p işaretçisini tutar. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak farklı tipe dönüştürür. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../object/) tipine dönüştürür. Pointee_ tipinin tam olması gerekmez. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Pointee_ tipi için [System::TypeInfo](../typeinfo/) nesnesine hızlı erişim sağlar. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Null işaretçi oluşturur. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Verilen nesneye zayıf işaretçi oluşturur. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | ptr’ın işaret ettiği aynı nesneye başvuran zayıf işaretçi oluşturur. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | x’in işaret ettiği aynı nesneye başvuran zayıf işaretçi oluşturur. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Zayıf işaretçiyi kopya yapıcıyla oluşturur. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Zayıf işaretçiyi kopya yapıcıyla oluşturur. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Zayıf işaretçiyi taşıma yapıcıyla oluşturur. |
|  [~SmartPtr](../smartptr/~smartptr/)() | [SmartPtr](../smartptr/) nesnesini yok eder. Gerekirse işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Tip tanımları

| Tip tanımı | Açıklama |
| --- | --- |
| [SmartPtr_](./smartptr_/) | İlgili [SmartPtr](../smartptr/) sınıfının takma adı. |
| [WeakPtr_](./weakptr_/) | Kendine ait tipin takma adı. |
| [Pointee_](./pointee_/) | İşaret edilen tip. |

## Ayrıca bakınız

* Sınıf [SmartPtr](../smartptr/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)