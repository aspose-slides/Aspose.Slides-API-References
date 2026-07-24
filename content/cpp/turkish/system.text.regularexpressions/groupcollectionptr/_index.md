---
title: GroupCollectionPtr
second_title: Aspose.Slides için C++ API Referansı
description: Grup koleksiyon işaretçisi. Bu tip, başka bir nesnenin silinmesini yönetmek için bir işaretçidir. Yığında (stack) ayrılmalı ve fonksiyonlara değer ya da const referans olarak geçirilmelidir.
type: docs
weight: 53
url: /tr/system.text.regularexpressions/groupcollectionptr/
---
## GroupCollectionPtr sınıfı


[Group](../group/) koleksiyon işaretçisi. Bu tip, başka bir nesnenin silinmesini yönetmek için bir işaretçidir. Yığında (stack) ayrılmalı ve fonksiyonlara değer ya da const referans olarak geçirilmelidir.

```cpp
class GroupCollectionPtr : public System::SmartPtr<GroupCollection>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Alt koleksiyonun [begin()](../../system/smartptr/begin/) metoduna erişimci. Yalnızca SmartPtr_ özelleşme türü [begin()](../../system/smartptr/begin/) metoduna sahipse derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | Alt koleksiyonun [begin()](../../system/smartptr/begin/) metoduna erişimci. Yalnızca SmartPtr_ özelleşme türü [begin()](../../system/smartptr/begin/) metoduna sahipse derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türe dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türe dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Alt koleksiyonun [cbegin()](../../system/smartptr/cbegin/) metoduna erişimci. Yalnızca SmartPtr_ özelleşme türü [cbegin()](../../system/smartptr/cbegin/) metoduna sahipse derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | Alt koleksiyonun [cend()](../../system/smartptr/cend/) metoduna erişimci. Yalnızca SmartPtr_ özelleşme türü [cend()](../../system/smartptr/cend/) metoduna sahirse derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | İşaretçiyi const_cast kullanarak farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | İşaretçiyi dynamic_cast kullanarak farklı bir tipe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | Alt koleksiyonun [end()](../../system/smartptr/end/) metoduna erişimci. Yalnızca SmartPtr_ özelleşme türü [end()](../../system/smartptr/end/) metoduna sahipse derlenir. |
| auto [end](../../system/smartptr/end/)() const | Alt koleksiyonun [end()](../../system/smartptr/end/) metoduna erişimci. Yalnızca SmartPtr_ özelleşme türü [end()](../../system/smartptr/end/) metoduna sahipse derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | İşaretçi kipini alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşımlı kipte olduğunu doğrular. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut işaretçi dahil olmak üzere mevcut paylaşımlı işaretçi sayısını alır. İşaretçinin paylaşımlı kipte olduğunu doğrular. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | İşaret edilen nesnede [GetHashCode()](../../system/smartptr/gethashcode/) metodunu çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır ya da bir istisna fırlatır. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır ya da nullptr döndürür. [get()](../../system/smartptr/get/) ile aynı. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır ya da nullptr döndürür. [get()](../../system/smartptr/get/) ile aynı. |
|  [GroupCollectionPtr](./groupcollectionptr/)() | Null işaretçi yapıcısı. |
|  [GroupCollectionPtr](./groupcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[GroupCollection](../groupcollection/)\>\&) | Tip dönüşüm yapıcısı. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipe ya da alt tipine ait olup olmadığını denetler. C# 'is' semantiğini izler. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | İşaretçinin, sahip olduğu nesne yerine başka bir nesneye işaret edip etmediğini denetler (aliasing yapıcıyla oluşturulmuş). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | İşaretçinin paylaşımlı kipte olup olmadığını denetler. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | İşaretçinin zayıf kipte olup olmadığını denetler. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | İşaretçinin null olmadığını denetler. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | İşaretçinin null olup olmadığını denetler. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaret edilen nesneye referans alır. İşaretçinin null olmadığını doğrular. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare semantiği sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare semantiği sağlar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesini taşımayla atar. x kullanılamaz hâle gelir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesini kopya ataması yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesini kopya ataması yapar. Gerekli tip dönüşümlerini gerçekleştirir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Ham işaretçiyi [SmartPtr](../../system/smartptr/) nesnesine atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr yapar. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | İşaretçinin nullptr’a işaret edip etmediğini denetler. |
| [GroupPtr](../groupptr/) [operator[]](./operator[]/)(size_t) const | [Group](../group/) erişimcisi. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | İşaretçiden aliasing'i (aliasing yapıcıyla oluşturulan) kaldırır, işaret ettiği nesnenin aynı nesneyi (paylaşımlıysa yönetir, zayıfsa izler) yönettiğinden emin olur. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | İşaretçiyi nullptr’a yönlendirir. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | İşaretçi kipini ayarlar. Referans verilen nesnenin referans sayısını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesnede (varsa) SetTemplateWeakPtr() metodunu çağırır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte null-pointer [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Belirtilen nesneye işaret eden [SmartPtr](../../system/smartptr/) oluşturur ya da ham işaretçiyi [SmartPtr](../../system/smartptr/)'a dönüştürür. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonrasında aynı nesneyi işaret eder. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonrasında aynı nesneyi işaret eder. İzin verildiğinde tip dönüşümü gerçekleştirir. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini taşımayla oluşturur. Etkili olarak, iki işaretçi aynı kipteyse yer değiştirir. Çağrı sonrası x kullanılmaz hâle gelebilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Referans verilen dizinin tipini yeni bir farklı tipte dizi oluşturarak dönüştürür. C#'ta desteklenmeyen dizi tipi dönüşümü C++'ta faydalıdır. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş bir dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) oluşturur; ptr'in başlangıç değerinin sahiplik bilgisini paylaşır ancak alakasız ve yönetilmeyen p işaretçisini tutar. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | İşaretçiyi static_cast kullanarak farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../../system/object/)'ye işaretçi tipine dönüştürür. Pointee_ tipinin tam olması gerekmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | {{Pointee_}} tipinin [System::TypeInfo](../../system/typeinfo/) nesnesini almanın kısayolu. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerekirse işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Aynı zamanda bakınız

* Sınıf [SmartPtr](../../system/smartptr/)
* Ad alanı [System::Text::RegularExpressions](../)
* Kütüphane [Aspose.Slides](../../)