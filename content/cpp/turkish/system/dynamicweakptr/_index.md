---
title: DynamicWeakPtr
second_title: Aspose.Slides for C++ API Referansı
description: Saklanan nesnenin şablon argümanlarının gösterici modlarını izleyen ve her atamadan sonra güncelleyen akıllı gösterici sınıfı. Bu tür, diğer nesnenin silinmesini yönetmek için bir göstericidir. Yığın üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referans ile geçirilmelidir.
type: docs
weight: 781
url: /tr/system/dynamicweakptr/
---
## DynamicWeakPtr sınıfı

Smart pointer sınıfı, saklanan nesnenin şablon argümanlarının gösterici modlarını izler ve her atamadan sonra günceller. Bu tür, diğer nesnenin silinmesini yönetmek için bir göstericidir. Yığın üzerinde ayrılmalı ve fonksiyonlara değer olarak ya da const referans ile geçirilmelidir.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Pointee | type. |
| trunkMode | Mode of smart pointer itself, shared or weak. |
| weakLeafs | Indexes of template arguments of stored type which should be set to weak pointer mode. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Alt koleksiyonun [begin()](../smartptr/begin/) metoduna erişimci. Yalnızca SmartPtr_ [begin()](../smartptr/begin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [begin](../smartptr/begin/)() const | Alt koleksiyonun [begin()](../smartptr/begin/) metoduna erişimci. Yalnızca SmartPtr_ [begin()](../smartptr/begin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Göstericiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Göstericiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Göstericiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Göstericiyi dynamic_cast ile türetilmiş tipe dönüştürür. |
| auto [cbegin](../smartptr/cbegin/)() const | Alt koleksiyonun [cbegin()](../smartptr/cbegin/) metodına erişimci. Yalnızca SmartPtr_ [cbegin()](../smartptr/cbegin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [cend](../smartptr/cend/)() const | Alt koleksiyonun [cend()](../smartptr/cend/) metodına erişimci. Yalnızca SmartPtr_ [cend()](../smartptr/cend/) metoduna sahip bir özelleştirme türü ise derlenir. |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | İşaret edilen nesne üzerinde const_cast kullanarak göstericiyi farklı bir tipe dönüştürür. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | İşaret edilen nesne üzerinde dynamic_cast kullanarak göstericiyi farklı bir tipe dönüştürür. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Null akıllı gösterici oluşturur. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Verilen nesneye işaret eden akıllı gösterici oluşturur. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Akıllı göstericiyi kopya yapıcı ile oluşturur. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Akıllı göstericiyi kopya yapıcı ile oluşturur. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Akıllı göstericiyi kopya yapıcı ile oluşturur. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Akıllı göstericiyi taşımalı yapıcı ile oluşturur. |
| auto [end](../smartptr/end/)() | Alt koleksiyonun [end()](../smartptr/end/) metoduna erişimci. Yalnızca SmartPtr_ [end()](../smartptr/end/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [end](../smartptr/end/)() const | Alt koleksiyonun [end()](../smartptr/end/) metoduna erişimci. Yalnızca SmartPtr_ [end()](../smartptr/end/) metoduna sahip bir özelleştirme türü ise derlenir. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Gösterici modunu alır. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak göstericinin paylaşılan modda olduğunu doğrular. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut paylaşılan göstericilerin sayısını (mevcut olan dahil) alır. Mevcut göstericinin paylaşılan modda olduğunu doğrular. |
| int [GetHashCode](../smartptr/gethashcode/)() const | İşaret edilen nesne üzerinde [GetHashCode()](../smartptr/gethashcode/) metodunu çağırır. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır; yoksa istisna fırlatır. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döner. [get()](../smartptr/get/) ile aynı. |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döner. [get()](../smartptr/get/) ile aynı. |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipte veya onun alt tipinde olup olmadığını kontrol eder. C# 'is' semantiğini takip eder. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Göstericinin sahip olduğu nesneden farklı bir nesneye işaret edip etmediğini (aliasing yapıcıyla oluşturulmuş) kontrol eder. |
| **bool** [IsShared](../smartptr/isshared/)() const | Göstericinin paylaşılan modda olup olmadığını kontrol eder. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Göstericinin zayıf (weak) modda olup olmadığını kontrol eder. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Göstericinin null olmadığını kontrol eder. |
| **bool** [operator!](../smartptr/operator_not/)() const | Göstericinin null olup olmadığını kontrol eder. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | İşaret edilen nesneye referans alır. Göstericinin null olmadığını doğrular. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | [SmartPtr](../smartptr/) sınıfı için 'less' karşılaştırma semantiği sağlar. |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | [SmartPtr](../smartptr/) sınıfı için 'less' karşılaştırma semantiği sağlar. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Akıllı göstericiyi taşımalı atama yapar. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Akıllı göstericiyi kopyalı atama yapar. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Akıllı göstericiyi kopyalı atama yapar. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Akıllı göstericiyi atar. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Akıllı göstericiyi null olarak ayarlar. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Akıllı göstericinin null olup olmadığını kontrol eder. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Göstericiden aliasing'i (aliasing yapıcı ile oluşturulan) kaldırır, işaret ettiği nesneyi (paylaşılan ise yönetir, zayıf ise izler) aynı nesne olduğundan emin olur. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../smartptr/reset/)() | Göstericiyi nullptr'ye işaret edecek şekilde ayarlar. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Gösterici modunu ayarlar. Referans verilen nesnenin referans sayısını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne üzerinde (varsa) SetTemplateWeakPtr() metodunu çağırır. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Gereken modda [SmartPtr](../smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Gereken modda null-pointer [SmartPtr](../smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Belirtilen nesneye işaret eden [SmartPtr](../smartptr/) oluşturur veya ham göstericiyi [SmartPtr](../smartptr/)'ye dönüştürür. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) nesnesini kopya yapıcı ile oluşturur. İki gösterici de sonradan aynı nesneye işaret eder. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) nesnesini kopya yapıcı ile oluşturur. İki gösterici de sonradan aynı nesneye işaret eder. İzin verildiğinde tip dönüşümü yapar. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) nesnesini taşımalı yapıcı ile oluşturur. Etkin olarak, iki göstericiyi takas eder, eğer ikisi de aynı modda ise. x çağrıdan sonra kullanılamaz olabilir. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Referans verilen dizinin tipini yeni bir farklı tipte dizi oluşturarak dönüştürür. C#'da desteklenmeyen bir dizi tip casti C++'da yararlı olur. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapılarını çevirmek için kullanılır. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ptr'nin başlangıç değeriyle sahiplik bilgilerini paylaşan ancak ilişkili olmayan ve yönetilmeyen p göstericisini tutan bir [SmartPtr](../smartptr/) oluşturur. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak göstericiyi farklı bir tipe dönüştürür. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Herhangi bir gösterici tipini [Object](../object/)'ye işaret eden göstericiye dönüştürür. Pointee_ tipinin tam olmasını gerektirmez. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Pointee_ tipi için [System::TypeInfo](../typeinfo/) nesnesini almanın kısayolu. |
|  [~SmartPtr](../smartptr/~smartptr/)() | [SmartPtr](../smartptr/) nesnesini yok eder. Gerekiyorsa, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) temel sınıf takma adı. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | Kendi tip takma adı. |
| [Pointee_](./pointee_/) | İşaret edilen tip. |

## Ayrıca Bakınız

* Sınıf [SmartPtr](../smartptr/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)