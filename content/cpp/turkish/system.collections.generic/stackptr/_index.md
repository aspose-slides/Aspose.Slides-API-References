---
title: StackPtr
second_title: Aspose.Slides for C++ API Referansı
description: Yığın işaretçisi. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.
type: docs
weight: 612
url: /tr/system.collections.generic/stackptr/
---
## StackPtr sınıfı

[Stack](../stack/) pointer. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.

```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Eleman tipi. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Alt koleksiyonun [begin()](../../system/smartptr/begin/) yöntemine erişim sağlar. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) metoduna sahip bir uzmanlaşma türü ise derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | Alt koleksiyonun [begin()](../../system/smartptr/begin/) yöntemine erişim sağlar. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) metoduna sahip bir uzmanlaşma türü ise derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Alt koleksiyonun [cbegin()](../../system/smartptr/cbegin/) yöntemine erişim sağlar. Yalnızca SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) metoduna sahip bir uzmanlaşma türü ise derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | Alt koleksiyonun [cend()](../../system/smartptr/cend/) yöntemine erişim sağlar. Yalnızca SmartPtr_ [cend()](../../system/smartptr/cend/) metoduna sahip bir uzmanlaşma türü ise derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | İşaret edilen nesne üzerinde const_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | İşaret edilen nesne üzerinde dynamic_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | Alt koleksiyonun [end()](../../system/smartptr/end/) yöntemine erişim sağlar. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) metoduna sahip bir uzmanlaşma türü ise derlenir. |
| auto [end](../../system/smartptr/end/)() const | Alt koleksiyonun [end()](../../system/smartptr/end/) yöntemine erişim sağlar. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) metoduna sahip bir uzmanlaşma türü ise derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | İşaretçi kipini alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşımlı kipte olduğunu doğrular. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut olan paylaşımlı işaretçi sayısını (geçerli işaretçi dahil) alır. Geçerli işaretçinin paylaşımlı kipte olduğunu doğrular. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | [GetHashCode()](../../system/smartptr/gethashcode/) metodunu işaret edilen nesne üzerinde çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır veya bir istisna fırlatır. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](../../system/smartptr/get/) ile aynı. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](../../system/smartptr/get/) ile aynı. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipte ya da onun türevi olup olmadığını denetler. C# 'is' semantiğini izler. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | İşaretçinin sahip olduğu nesneden farklı bir nesneye işaret edip etmediğini (aliasing yapıcı ile oluşturulmuş) denetler. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | İşaretçinin paylaşımlı kipte olup olmadığını denetler. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | İşaretçinin zayıf kipte olup olmadığını denetler. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | İşaretçinin null olmadığını denetler. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | İşaretçinin null olduğunu denetler. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaret edilen nesneye referans alır. İşaretçinin null olmadığını doğrular. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare semantiği sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare semantiği sağlar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesine move-atama yapar. x kullanılamaz hâle gelir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya-atama yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya-atama yapar. Gerekli tip dönüşümlerini gerçekleştirir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Ham işaretçiyi [SmartPtr](../../system/smartptr/) nesnesine atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | İşaretçinin nullptr'ı gösterip göstermediğini denetler. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | İşaretçiden aliasing'i (aliasing yapıcı ile oluşturulan) kaldırır, işaretçinin aynı nesneyi (paylaşımlıysa yönetir, zayıfsa izler) yönettiğinden emin olur. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | İşaretçiyi nullptr'ı işaret edecek şekilde ayarlar. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | İşaretçi kipini ayarlar. Referans verilen nesnenin referans sayısını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne (varsa) üzerindeki SetTemplateWeakPtr() metodunu çağırır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte null-pointer [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Belirtilen nesneyi işaret eden [SmartPtr](../../system/smartptr/) oluşturur ya da ham işaretçiyi [SmartPtr](../../system/smartptr/)'e dönüştürür. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonrasında aynı nesneyi işaret eder. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonrasında aynı nesneyi işaret eder. İzin verildiğinde tip dönüşümü yapar. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini move yapıcı ile oluşturur. Gerçekte, aynı kipte iki işaretçiyi takas eder. x çağrı sonrası kullanılmaz olabilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Referans verilen dizinin tipini farklı bir tipte yeni bir dizi oluşturarak dönüştürür. C#'ta desteklenmeyen dizi tip dönüşümü C++'ta faydalıdır. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş bir dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesi oluşturur; bu nesne ptr'nin ilk değeriyle sahiplik bilgilerini paylaşır, ancak ilişkili olmayan ve yönetilmeyen p işaretçisini tutar. |
|  [StackPtr](./stackptr/)() | Null işaretçi oluşturur. |
|  [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | Belirli bir yığını referanslayan işaretçi oluşturur. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../../system/object/) işaretçisine dönüştürür. Pointee_ tipinin tam olmasını gerektirmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) nesnesini Pointee_ tipi için elde etmeye kısayol. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerekirse, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Diğerlerine Bak

* Sınıf [SmartPtr](../../system/smartptr/)
* Ad alanı [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)