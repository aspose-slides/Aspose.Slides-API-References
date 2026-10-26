---
title: BitArrayPtr
second_title: Aspose.Slides for C++ API Referansı
description: BitArray'ye gösterici. Bu tip, diğer nesnenin silinmesini yönetmek için bir göstergedir. Yığının (stack) üzerinde tahsis edilmeli ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.
type: docs
weight: 14
url: /tr/system.collections/bitarrayptr/
---
## BitArrayPtr sınıf

Gösterici [BitArray](../bitarray/). Bu tip, diğer nesnenin silinmesini yönetmek için bir göstergedir. Yığının (stack) üstünde tahsis edilmeli ve fonksiyonlara değer olarak ya da const referansla geçirilmelidir.

```cpp
class BitArrayPtr : public System::SmartPtr<BitArray>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | [begin()](../../system/smartptr/begin/) yöntemine sahip bir alt koleksiyon için erişimci. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | [begin()](../../system/smartptr/begin/) yöntemine sahip bir alt koleksiyon için erişimci. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| [BitArrayPtr](./bitarrayptr/)() | null göstericiyi başlatır. |
| [BitArrayPtr](./bitarrayptr/)(const [SharedPtr](../../system/sharedptr/)\<[BitArray](../bitarray/)\>\&) | Dönüşüm yapıcı. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Göstericiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Göstericiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Göstericiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Göstericiyi dynamic_cast kullanarak türetilmiş tipe dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | [cbegin()](../../system/smartptr/cbegin/) yöntemine sahip bir alt koleksiyon için erişimci. Yalnızca SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | [cend()](../../system/smartptr/cend/) yöntemine sahip bir alt koleksiyon için erişimci. Yalnızca SmartPtr_ [cend()](../../system/smartptr/cend/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Göstericiyi işaret edilen nesne üzerinde const_cast kullanarak farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Göstericiyi işaret edilen nesne üzerinde dynamic_cast kullanarak farklı bir tipe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | [end()](../../system/smartptr/end/) yöntemine sahip bir alt koleksiyon için erişimci. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| auto [end](../../system/smartptr/end/)() const | [end()](../../system/smartptr/end/) yöntemine sahip bir alt koleksiyon için erişimci. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) yöntemine sahip bir özelleştirme türü ise derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Gösterici modunu alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak göstericinin paylaşımlı modda olduğunu varsayar. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut olan paylaşımlı göstericilerin sayısını (mevcut olan da dahil) alır. Mevcut göstericinin paylaşımlı modda olduğunu varsayar. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | İşaret edilen nesne üzerinde [GetHashCode()](../../system/smartptr/gethashcode/)'yi çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır ya da hata fırlatır. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır ya da nullptr döner. [get()](../../system/smartptr/get/) ile aynıdır. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır ya da nullptr döner. [get()](../../system/smartptr/get/) ile aynıdır. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipe ya da onun alt tipine ait olup olmadığını kontrol eder. C# 'is' semantiğini izler. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Göstericinin sahibi (aliasing yapıcıyla oluşturulan) nesne dışında bir nesneye işaret edip etmediğini kontrol eder. |
| **bool** [IsNull](./isnull/)() const | Belirli değerin null olup olmadığını kontrol eder. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Göstericinin paylaşımlı modda olup olmadığını kontrol eder. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Göstericinin zayıf (weak) modda olup olmadığını kontrol eder. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Göstericinin null olmadığını kontrol eder. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Göstericinin null olup olmadığını kontrol eder. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaret edilen nesneye referans alır. Göstericinin null olmadığını varsayar. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için daha az karşılaştırma semantiği sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için daha az karşılaştırma semantiği sağlar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesine move-atama yapar. x kullanılamaz hâle gelir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya-atama yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya-atama yapar. Gerekli tip dönüşümlerini gerçekleştirir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Ham göstericiyi [SmartPtr](../../system/smartptr/) nesnesine atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Gösterici değerini nullptr olarak ayarlar. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Göstericinin nullptr'ye işaret edip etmediğini kontrol eder. |
| **BitArray::Reference** [operator[]](./operator[]/)(int) const | Bit erişicisi. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Göstericiden aliasing'i (aliasing yapıcıyla oluşturulan) kaldırır, işaret ettiği aynı nesneyi (paylaşımlı ise yönetir, zayıf ise izler) sağladığından emin olur. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | Göstericiyi nullptr'ye işaret edecek şekilde yapar. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Gösterici modunu ayarlar. Referans verilen nesnenin referans sayısını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne üzerinde (varsa) SetTemplateWeakPtr() yöntemini çağırır. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gerekli modda [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gerekli modda null gösterici [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Belirtilen nesneyi işaret eden [SmartPtr](../../system/smartptr/) oluşturur ya da ham göstericiyi [SmartPtr](../../system/smartptr/)'ye dönüştürür. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcıyla oluşturur. Her iki gösterici de ardından aynı nesneyi işaret eder. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcıyla oluşturur. Her iki gösterici de ardından aynı nesneyi işaret eder. İzin verildiğinde tip dönüşümü yapar. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini move yapıcıyla oluşturur. Etkin olarak, iki göstericiyi (aynı modda ise) takas eder. x çağrı sonrası kullanılamaz hâle gelebilir. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Referans verilen dizinin tipini farklı bir tipte yeni bir dizi oluşturarak dönüştürür. C#'ta desteklenmeyen bir dizi tip dönüşümü C++'ta faydalı olabilir. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) oluşturur; ptr'nin başlangıç değerinin sahiplik bilgisini paylaşır, ancak ilişkili olmayan ve yönetsiz bir p göstericiyi tutar. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Göstericiyi işaret edilen nesne üzerinde static_cast kullanarak farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Herhangi bir gösterici tipini [Object](../../system/object/)'ye göstericiye dönüştürür. Pointee_ tipinin tam olmasını gerektirmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) nesnesini Pointee_ tipi için almanın kısayolu. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerekirse, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../system/smartptr/)
* Ad alanı [System::Collections](../)
* Kütüphane [Aspose.Slides](../../)