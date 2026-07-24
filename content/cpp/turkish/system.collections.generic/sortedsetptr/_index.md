---
title: SortedSetPtr
second_title: C++ API Referansı için Aspose.Slides
description: SortedSet referanslarını tutmak için işaretçi. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığını üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçilmelidir.
type: docs
weight: 586
url: /tr/system.collections.generic/sortedsetptr/
---
## SortedSetPtr sınıfı


İşaretçi, [SortedSet](../sortedset/) referansları tutmak için kullanılır. Bu tip, diğer nesnelerin silinmesini yönetmek için bir işaretçidir. Yığını üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçilmelidir.

```cpp
template<typename T>class SortedSetPtr : public System::SmartPtr<SortedSet<T>>
```

## Yöntemler

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Alttaki koleksiyonun [begin()](../../system/smartptr/begin/) yöntemine erişimci. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | Alttaki koleksiyonun [begin()](../../system/smartptr/begin/) yöntemine erişimci. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi türetilmiş tipe dynamic_cast ile dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi türetilmiş tipe dynamic_cast ile dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Alttaki koleksiyonun [cbegin()](../../system/smartptr/cbegin/) yöntemine erişimci. Yalnızca SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | Alttaki koleksiyonun [cend()](../../system/smartptr/cend/) yöntemine erişimci. Yalnızca SmartPtr_ [cend()](../../system/smartptr/cend/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | İşaret edilen nesne üzerinde const_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | İşaret edilen nesne üzerinde dynamic_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | Alttaki koleksiyonun [end()](../../system/smartptr/end/) yöntemine erişimci. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| auto [end](../../system/smartptr/end/)() const | Alttaki koleksiyonun [end()](../../system/smartptr/end/) yöntemine erişimci. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | İşaretçi kipini alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşımlı kipte olduğunu doğrular. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut olan paylaşımlı işaretçi sayısını (geçerli olan da dahil) alır. Geçerli işaretçinin paylaşımlı kipte olduğunu doğrular. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | İşaret edilen nesne üzerinde [GetHashCode()](../../system/smartptr/gethashcode/) çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır ya da bir istisna atar. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır ya da nullptr döner. [get()](../../system/smartptr/get/) ile aynı. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır ya da nullptr döner. [get()](../../system/smartptr/get/) ile aynı. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipe veya onun alt tipine ait olup olmadığını denetler. C# 'is' semantiğini takip eder. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | İşaretçinin sahip olduğu nesneden başka bir nesneye işaret edip etmediğini (aliasing kurucusu ile oluşturulmuş) denetler. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | İşaretçinin paylaşımlı kipte olup olmadığını denetler. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | İşaretçinin zayıf kipte olup olmadığını denetler. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | İşaretçinin null olmadığını denetler. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | İşaretçinin null olup olmadığını denetler. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaret edilen nesneye referans döndürür. İşaretçinin null olmadığını doğrular. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare (küçük karşılaştırma) semantiği sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare (küçük karşılaştırma) semantiği sağlar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesine hareket ataması yapar. x kullanılamaz hâle gelir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya ataması yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya ataması yapar. Gerekli tip dönüşümlerini gerçekleştirir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Ham işaretçiyi [SmartPtr](../../system/smartptr/) nesnesine atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | İşaretçinin nullptr'ı işaret edip etmediğini denetler. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | İşaretçiden aliasing'i (aliasing kurucusu ile oluşturulan) kaldırır, işaret ettiği nesneyi aynı nesneyi yönettiğinden (paylaşımlıysa) ya da izlediğinden (zayıfsa) emin olur. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | İşaretçiyi nullptr'a işaret edecek şekilde ayarlar. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | İşaretçi kipini ayarlar. Referans verilen nesnenin referans sayılarını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne üzerinde (varsa) SetTemplateWeakPtr() yöntemini çağırır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte null-pointer [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Belirtilen nesneyi işaret eden [SmartPtr](../../system/smartptr/) oluşturur ya da ham işaretçiyi [SmartPtr](../../system/smartptr/)'a dönüştürür. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya ile oluşturur. Her iki işaretçi de sonrasında aynı nesneyi işaret eder. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya ile oluşturur. Her iki işaretçi de sonrasında aynı nesneyi işaret eder. İzin verildiğinde tip dönüşümü yapılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini taşımayla oluşturur. Etkili olarak, iki işaretçi aynı kipte ise birbirleriyle takas edilir. x çağrı sonrası kullanılamaz hâle gelebilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Referans verilen dizinin tipini, farklı tipte yeni bir dizi oluşturarak dönüştürür. C#'ta bulunan ve C++'ta desteklenmeyen dizi tipi dönüşümü gerektiğinde faydalıdır. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş bir dizi başlatır. Bazı C# kod yapılarını çevirmek için kullanılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesi oluşturur; bu nesne ptr'nin ilk değeriyle sahiplik bilgisini paylaşır, ancak alakasız ve yönetilmeyen p işaretçisini tutar. |
|  [SortedSetPtr](./sortedsetptr/)() | Null işaretçi kurucusu. |
|  [SortedSetPtr](./sortedsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedSet](../sortedset/)\<T\>\>\&) | Kopya kurucu. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../../system/object/)'e işaretçi tipine dönüştürür. Pointee_ tipinin tam olmasını gerektirmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) nesnesini Pointee_ tipi için almanın kısayolu. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerekiyorsa, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../system/smartptr/)
* İsim alanı [System::Collections::Generic](../)
* Kütüphane [Aspose.Slides](../../)