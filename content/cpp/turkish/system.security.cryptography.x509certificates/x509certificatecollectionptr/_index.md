---
title: X509CertificateCollectionPtr
second_title: Aspose.Slides for C++ API Referansı
description: X509 sertifikalarının koleksiyonuna işaretçi. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığında ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.
type: docs
weight: 92
url: /tr/system.security.cryptography.x509certificates/x509certificatecollectionptr/
---
## X509CertificateCollectionPtr sınıfı

X509 sertifikalarının koleksiyonuna işaretçi. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.

```cpp
class X509CertificateCollectionPtr : public System::SmartPtr<X509CertificateCollection>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Alttaki koleksiyonun [begin()](../../system/smartptr/begin/) yöntemine erişici. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) yöntemiyle özelleştirilmiş bir tip ise derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | Alttaki koleksiyonun [begin()](../../system/smartptr/begin/) yöntemine erişici. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) yöntemiyle özelleştirilmiş bir tip ise derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi derived tipe dynamic_cast ile dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi derived tipe dynamic_cast ile dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Alttaki koleksiyonun [cbegin()](../../system/smartptr/cbegin/) yöntemine erişici. Yalnızca SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) yöntemiyle özelleştirilmiş bir tip ise derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | Alttaki koleksiyonun [cend()](../../system/smartptr/cend/) yöntemine erişici. Yalnızca SmartPtr_ [cend()](../../system/smartptr/cend/) yöntemiyle özelleştirilmiş bir tip ise derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | İşaretlenen nesne üzerinde const_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | İşaretlenen nesne üzerinde dynamic_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | Alttaki koleksiyonun [end()](../../system/smartptr/end/) yöntemine erişici. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) yöntemiyle özelleştirilmiş bir tip ise derlenir. |
| auto [end](../../system/smartptr/end/)() const | Alttaki koleksiyonun [end()](../../system/smartptr/end/) yöntemine erişici. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) yöntemiyle özelleştirilmiş bir tip ise derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaretlenen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | İşaretçi modunu alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaretlenen nesneyi alır, ancak işaretçinin paylaşımlı modda olduğunu doğrular. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut olan paylaşımlı işaretçilerin sayısını, mevcut olanı da dahil ederek alır. Mevcut işaretçinin paylaşımlı modda olduğunu doğrular. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | İşaretlenen nesne üzerinde [GetHashCode()](../../system/smartptr/gethashcode/) çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır veya bir istisna fırlatır. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaretlenen nesneyi (varsa) alır veya nullptr döndürür. [get()](../../system/smartptr/get/) ile aynı. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaretlenen nesneyi (varsa) alır veya nullptr döndürür. [get()](../../system/smartptr/get/) ile aynı. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaretlenen nesnenin belirli bir tipte ya da onun alt tipinde olup olmadığını kontrol eder. C# 'is' semantiğini izler. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | İşaretçinin, sahip olduğu nesne (aliasing constructor ile oluşturulan) dışında başka bir nesneyi işaret edip etmediğini kontrol eder. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | İşaretçinin paylaşımlı modda olup olmadığını kontrol eder. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | İşaretçinin zayıf (weak) modda olup olmadığını kontrol eder. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | İşaretçinin null olmadığını kontrol eder. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | İşaretçinin null olup olmadığını kontrol eder. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaretlenen nesneye referans alır. İşaretçinin null olmadığını doğrular. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için less karşılaştırma semantiği sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için less karşılaştırma semantiği sağlar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesini move-atama yapar. x kullanılamaz hâle gelir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesini kopya-atama yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesini kopya-atama yapar. Gerekli tip dönüşümlerini gerçekleştirir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Raw işaretçiyi [SmartPtr](../../system/smartptr/) nesnesine atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr yapar. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | İşaretçinin nullptr işaret edip etmediğini kontrol eder. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\& [operator[]](./operator[]/)(int) const | Erişimci. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | İşaretçiden aliasing'i (aliasing constructor ile oluşturulan) kaldırır, işaret ettiği aynı nesneyi (paylaşımlıysa yönetir, zayıfsa izler) garantiler. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaretlenen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | İşaretçiyi nullptr'ye işaret eder. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | İşaretçi modunu ayarlar. Referans verilen nesnenin referans sayılarını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaretlenen nesne (varsa) üzerinde SetTemplateWeakPtr() metodunu çağırır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gerekli modda [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gerekli modda null-pointer [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Belirtilen nesneyi işaret eden [SmartPtr](../../system/smartptr/) oluşturur ya da raw işaretçiyi [SmartPtr](../../system/smartptr/)'ye dönüştürür. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcıyla oluşturur. Her iki işaretçi de ardından aynı nesneyi işaret eder. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcıyla oluşturur. Her iki işaretçi de ardından aynı nesneyi işaret eder. İzin verilirse tip dönüşümü yapar. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini move yapıcıyla oluşturur. Etkin olarak, ikisi de aynı modda ise iki işaretçiyi takas eder. Çağrı sonrası x kullanılamaz hâle gelebilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Referans verilen dizinin tipini farklı bir tipte yeni dizi oluşturarak dönüştürür. C#'ta desteklenmeyen bir dizi tip dönüşümü C++'ta kullanılabilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | ptr'nin ilk değeriyle sahiplik bilgilerini paylaşan, fakat alakasız ve yönetilmeyen p işaretçisini tutan bir [SmartPtr](../../system/smartptr/) oluşturur. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | İşaretlenen nesne üzerinde static_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../../system/object/)'ye işaretçi tipine dönüştürür. Pointee_ tipinin tam olmasını gerektirmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ tipi için [System::TypeInfo](../../system/typeinfo/) nesnesini almanın kısayolu. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)() | Null işaretçi yapıcı. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509CertificateCollection](../x509certificatecollection/)\>\&) | Yapıcı. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerektiğinde, işaretlenen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../system/smartptr/)
* Ad alanı [System::Security::Cryptography::X509Certificates](../)
* Kütüphane [Aspose.Slides](../../)