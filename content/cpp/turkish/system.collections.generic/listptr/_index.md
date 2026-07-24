---
title: ListPtr
second_title: Aspose.Slides for C++ API Referansı
description: Erişim operatörlerine sahip liste işaretçisi. Bu tür, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da const referans olarak geçirilmelidir.
type: docs
weight: 456
url: /tr/system.collections.generic/listptr/
---
## ListPtr sınıf

[List](../list/) erişim operatörleriyle işaretçi. Bu tür, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da const referans olarak geçirilmelidir.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | [begin()](../../system/smartptr/begin/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ özel bir tür ise ve [begin()](../../system/smartptr/begin/) metoduna sahipse derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | [begin()](../../system/smartptr/begin/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ özel bir tür ise ve [begin()](../../system/smartptr/begin/) metoduna sahipse derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi kendi türüne dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi static_cast kullanarak temel türe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş türe dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş türe dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | [cbegin()](../../system/smartptr/cbegin/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ özel bir tür ise ve [cbegin()](../../system/smartptr/cbegin/) metoduna sahipse derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | [cend()](../../system/smartptr/cend/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ özel bir tür ise ve [cend()](../../system/smartptr/cend/) metoduna sahipse derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | İşaret edilen nesneye const_cast uygulayarak farklı türe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | İşaret edilen nesneye dynamic_cast uygulayarak farklı türe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | [end()](../../system/smartptr/end/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ özel bir tür ise ve [end()](../../system/smartptr/end/) metoduna sahipse derlenir. |
| auto [end](../../system/smartptr/end/)() const | [end()](../../system/smartptr/end/) metoduna erişim sağlayıcı. Yalnızca SmartPtr_ özel bir tür ise ve [end()](../../system/smartptr/end/) metoduna sahipse derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | İşaretçi modunu alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşılan modda olduğunu doğrular. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut olan paylaşılan işaretçilerin sayısını (geçerli işaretçi dahil) alır. Geçerli işaretçinin paylaşılan modda olduğunu doğrular. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | İşaret edilen nesne üzerinde [GetHashCode()](../../system/smartptr/gethashcode/) metodunu çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Geçerli referans verilen nesneyi (varsa) alır veya hata fırlatır. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) veya nullptr değerini alır. [get()](../../system/smartptr/get/) ile aynı. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) veya nullptr değerini alır. [get()](../../system/smartptr/get/) ile aynı. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipe ya da onun alt tipine ait olup olmadığını denetler. C# 'is' semantiğini izler. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | İşaretçinin sahip olunan nesne dışındaki başka bir nesneyi işaret edip etmediğini (aliasing yapıcı ile oluşturulan) denetler. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | İşaretçinin paylaşılan modda olup olmadığını denetler. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | İşaretçinin zayıf modda olup olmadığını denetler. |
|  [ListPtr](./listptr/)(std::nullptr_t) | Null işaretçiyi başlatır. |
|  [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | İşaretçiyi belirtilen listeye başlatır. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | İşaretçinin null olmamasını denetler. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | İşaretçinin null olup olmadığını denetler. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaret edilen nesneye referansı alır. İşaretçinin null olmamasını doğrular. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için daha az karşılaştırma semantiği sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için daha az karşılaştırma semantiği sağlar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesine taşıma ataması yapar. x kullanılamaz hâle gelir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya ataması yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya ataması yapar. Gerekli tür dönüşümlerini gerçekleştirir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | [SmartPtr](../../system/smartptr/) nesnesine ham işaretçi atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | [List](../list/) işaretçisinin null olup olmadığını denetler. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | Erişici. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | Erişici. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | İşaretçiden aliasing'i (aliasing yapıcı ile oluşturulan) kaldırır, işaret ettiği nesnenin aynı nesne olduğunu (paylaşılıyorsa yönetir, zayıfsa izler) garanti eder. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | İşaretçiyi nullptr işaret edecek şekilde yapar. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | İşaretçi modunu ayarlar. Referans verilen nesnenin referans sayılarını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne (varsa) üzerinde SetTemplateWeakPtr() metodunu çağırır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gerekli modda [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gerekli modda null işaretçi [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Belirtilen nesneyi işaret eden [SmartPtr](../../system/smartptr/) oluşturur veya ham işaretçiyi [SmartPtr](../../system/smartptr/)'ye dönüştürür. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de daha sonra aynı nesneyi işaret eder. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de daha sonra aynı nesneyi işaret eder. İzin verilirse tür dönüşümü yapar. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini taşıma yapıcı ile oluşturur. Etkin olarak, iki işaretçiyi takas eder; eğer her ikisi aynı modda ise. x, çağrı sonrası kullanılamaz olabilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Referans verilen dizinin tipini, farklı tipte yeni bir dizi oluşturarak dönüştürür. C#'ta bulunan ancak C++'ta desteklenmeyen dizi tip dönüşümü varsa işe yarar. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ptr'nin ilk değeri ile sahiplik bilgilerini paylaşan bir [SmartPtr](../../system/smartptr/) oluşturur, ancak ilişkili olmayan ve yönetilmeyen p işaretçisini tutar. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak işaretçiyi farklı tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../../system/object/) işaretçisine dönüştürür. Pointee_ tipinin tam olmasını gerektirmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ tipi için [System::TypeInfo](../../system/typeinfo/) nesnesini almanın kısayolu. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerekirse, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../system/smartptr/)
* Ad Alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)