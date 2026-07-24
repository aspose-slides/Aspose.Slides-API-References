---
title: X509Certificate2CollectionPtr
second_title: Aspose.Slides for C++ API Referansı
description: X509 sertifikalarının koleksiyonuna işaretçi. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.
type: docs
weight: 66
url: /tr/system.security.cryptography.x509certificates/x509certificate2collectionptr/
---
## X509Certificate2CollectionPtr sınıfı

X509 sertifikalarının koleksiyonuna bir işaretçidir. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığın üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.

```cpp
class X509Certificate2CollectionPtr : public System::SmartPtr<X509Certificate2Collection>
```

## Yöntemler

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Alt koleksiyonun [begin()](../../system/smartptr/begin/) metoduna erişim. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | Alt koleksiyonun [begin()](../../system/smartptr/begin/) metoduna erişim. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Alt koleksiyonun [cbegin()](../../system/smartptr/cbegin/) metoduna erişim. Yalnızca SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | Alt koleksiyonun [cend()](../../system/smartptr/cend/) metoduna erişim. Yalnızca SmartPtr_ [cend()](../../system/smartptr/cend/) metoduna sahip bir özelleştirme türü ise derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | İşaretçiyi işaret edilen nesne üzerinde const_cast kullanarak farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | İşaretçiyi işaret edilen nesne üzerinde dynamic_cast kullanarak farklı bir tipe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | Alt koleksiyonun [end()](../../system/smartptr/end/) metoduna erişim. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [end](../../system/smartptr/end/)() const | Alt koleksiyonun [end()](../../system/smartptr/end/) metoduna erişim. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) metoduna sahip bir özelleştirme türü ise derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | İşaretçi kipini alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşılan modda olduğunu doğrular. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Başvurulan nesneye mevcut olan paylaşılan işaretçi sayısını (geçerli dahil) alır. Geçerli işaretçinin paylaşılan modda olduğunu doğrular. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | İşaret edilen nesne üzerinde [GetHashCode()](../../system/smartptr/gethashcode/) metodunu çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Şu anda başvurulan nesneyi (varsa) alır veya bir istisna fırlatır. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döner. [get()](../../system/smartptr/get/) ile aynı. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Başvurulan nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döner. [get()](../../system/smartptr/get/) ile aynı. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipe veya onun alt tipine ait olup olmadığını kontrol eder. C# 'is' semantiğini izler. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | İşaretçinin sahibi olduğu nesne dışında başka bir nesneye işaret edip etmediğini (aliasing yapıcı ile oluşturulmuş) kontrol eder. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | İşaretçinin paylaşılan modda olup olmadığını kontrol eder. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | İşaretçinin zayıf modda olup olmadığını kontrol eder. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | İşaretçinin null olmadığını kontrol eder. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | İşaretçinin null olup olmadığını kontrol eder. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaret edilen nesneye referansı alır. İşaretçinin null olmamasını doğrular. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Başvurulan nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için daha az karşılaştırma semantiği sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için daha az karşılaştırma semantiği sağlar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesini move-atama yapar. x kullanılamaz hâle gelir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesini kopya-atama yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesini kopya-atama yapar. Gerekli tip dönüşümlerini yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Ham işaretçiyi [SmartPtr](../../system/smartptr/) nesnesine atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | İşaretçinin nullptr'ı işaret edip etmediğini kontrol eder. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate2](../x509certificate2/)\>\& [operator[]](./operator[]/)(size_t) const | Erişimci. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | İşaretçiden aliasing'i (aliasing yapıcı ile oluşturulan) kaldırır, işaret ettiği aynı nesneyi (paylaşılan ise yönetir, zayıf ise izler) sağlamak için emin olur. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | İşaretçiyi nullptr'a işaret edecek şekilde ayarlar. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | İşaretçi kipini ayarlar. Başvurulan nesnenin referans sayılarını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne üzerinde (varsa) SetTemplateWeakPtr() metodunu çağırır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte null-pointer [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Belirtilen nesneye işaret eden [SmartPtr](../../system/smartptr/) oluşturur veya ham işaretçiyi [SmartPtr](../../system/smartptr/)'e dönüştürür. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapılandırır. Her iki işaretçi de daha sonra aynı nesneyi işaret eder. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapılandırır. Her iki işaretçi de daha sonra aynı nesneyi işaret eder. İzin verildiğinde tip dönüşümü yapar. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini move yapılandırır. Etkili olarak, iki işaretçi aynı kipteyse takasını yapar. Çağrı sonrası x kullanılamaz olabilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Başvurulan dizinin tipini, farklı tipte yeni bir dizi oluşturarak dönüştürür. C#'ta mevcut olup C++'ta desteklenmeyen dizi tip dönüşümleri için kullanışlıdır. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapıları için kullanılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini, ptr'nin ilk değeriyle sahiplik bilgisini paylaşacak şekilde, ancak alakasız ve yönetilmeyen p işaretçisi tutacak şekilde oluşturur. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | İşaretçiyi işaret edilen nesne üzerinde static_cast kullanarak farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../../system/object/) tipine dönüştürür. Pointee_ tipinin tam olmasını gerektirmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) nesnesini Pointee_ tipi için almanın kısayolu. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)() | Null işaretçi yapıcı. |
|  [X509Certificate2CollectionPtr](./x509certificate2collectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509Certificate2Collection](../x509certificate2collection/)\>\&) | Yapıcı. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerekirse, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## İlgili

* Sınıf [SmartPtr](../../system/smartptr/)
* Ad alanı [System::Security::Cryptography::X509Certificates](../)
* Kütüphane [Aspose.Slides](../../)