---
title: StringCollectionPtr
second_title: Aspose.Slides for C++ API Referansı
description: Erişim operatörüne sahip dize koleksiyon işaretçisi.
type: docs
weight: 40
url: /tr/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr sınıfı

Erişim operatörüne sahip dize koleksiyonu işaretçisi.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Altyapı koleksiyonunun [begin()](../../system/smartptr/begin/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| auto [begin](../../system/smartptr/begin/)() const | Altyapı koleksiyonunun [begin()](../../system/smartptr/begin/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [begin()](../../system/smartptr/begin/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi kendi tipine dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi static_cast kullanarak temel tipe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi derived tipe dynamic_cast ile dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | İşaretçiyi derived tipe dynamic_cast ile dönüştürür. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Altyapı koleksiyonunun [cbegin()](../../system/smartptr/cbegin/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| auto [cend](../../system/smartptr/cend/)() const | Altyapı koleksiyonunun [cend()](../../system/smartptr/cend/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [cend()](../../system/smartptr/cend/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | İşaretçiyi işaret edilen nesne üzerinde const_cast kullanarak farklı bir tipe dönüştürür. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | İşaretçiyi işaret edilen nesne üzerinde dynamic_cast kullanarak farklı bir tipe dönüştürür. |
| auto [end](../../system/smartptr/end/)() | Altyapı koleksiyonunun [end()](../../system/smartptr/end/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| auto [end](../../system/smartptr/end/)() const | Altyapı koleksiyonunun [end()](../../system/smartptr/end/) yöntemine erişim sağlayıcı. Yalnızca SmartPtr_ [end()](../../system/smartptr/end/) yöntemine sahip bir özelleştirme türü olduğunda derlenir. |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | İşaretçi kipini alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşılan kipte olduğunu doğrular. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Referans verilen nesneye mevcut olan paylaşımlı işaretçilerin sayısını (mevcut olan da dahil) alır. Mevcut işaretçinin paylaşılan kipte olduğunu doğrular. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | İşaret edilen nesne üzerinde [GetHashCode()](../../system/smartptr/gethashcode/) çağırır. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır veya bir istisna fırlatır. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](../../system/smartptr/get/) ile aynıdır. |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](../../system/smartptr/get/) ile aynıdır. |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tipte veya onun alt tipinde olup olmadığını denetler. C# 'is' semantiğini izler. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | İşaretçinin sahip olduğu nesne dışında başka bir nesneye işaret edip etmediğini denetler (aliasing yapıcı ile oluşturulmuş). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | İşaretçinin paylaşımlı kipte olup olmadığını denetler. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | İşaretçinin zayıf kipte olup olmadığını denetler. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | İşaretçinin null olmadığını denetler. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | İşaretçinin null olup olmadığını denetler. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | İşaret edilen nesneye referans döndürür. İşaretçinin null olmadığını doğrular. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare mantığını sağlar. |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) sınıfı için less-compare mantığını sağlar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) nesnesini taşıma ataması yapar. x kullanılamaz hale gelir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya ataması yapar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) nesnesine kopya ataması yapar. Gerekli tip dönüşümlerini gerçekleştirir. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | [SmartPtr](../../system/smartptr/) nesnesine ham işaretçi atar. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | İşaretçinin nullptr'a işaret edip etmediğini denetler. |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | Erişim işlevi. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | İşaretçiden aliasing'i (aliasing yapıcı tarafından oluşturulan) kaldırır, işaret ettiği nesnenin aynı olması (paylaşımlıysa yönetir, zayıfsa izler) garantilenir. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](../../system/smartptr/reset/)() | İşaretçiyi nullptr'a işaret edecek şekilde ayarlar. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | İşaretçi kipini ayarlar. Referans verilen nesnenin referans sayılarını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesne (varsa) üzerinde SetTemplateWeakPtr() yöntemini çağırır. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Gerekli kipte null işaretçi [SmartPtr](../../system/smartptr/) nesnesi oluşturur. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) oluşturur ve belirtilen nesneye işaret eder, ya da ham işaretçiyi [SmartPtr](../../system/smartptr/)'ye dönüştürür. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonrasında aynı nesneye işaret eder. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonrasında aynı nesneye işaret eder. İzin verildiğinde tip dönüşümü yapar. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) nesnesini taşıma yapıcı ile oluşturur. Etkili olarak, iki işaretçi aynı kipteyse takas eder. x çağrı sonrası kullanılamaz olabilir. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Referans verilen dizinin tipini yeni bir farklı tipte dizi oluşturarak dönüştürür. C#'ta desteklenmeyen bir dizi tip dönüşümü C++'ta faydalı olur. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Boş dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) oluşturur; bu, ptr'in ilk değeriyle sahiplik bilgisini paylaşır fakat alakalı olmayan ve yönetilmeyen p işaretçisini tutar. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak işaretçiyi farklı bir tipe dönüştürür. |
|  [StringCollectionPtr](./stringcollectionptr/)() | Null işaretçi oluşturur. |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | Belirli bir koleksiyona işaretçi oluşturur. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | [Object](../../system/object/)'ye işaretçi tipini dönüştürür. Pointee_ tipinin tam olması gerekmez. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) nesnesini Pointee_ tipi için almanın kısayolu. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) nesnesini yok eder. Gerekirse, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Ayrıca Bakınız

* Sınıf [SmartPtr](../../system/smartptr/)
* Ad alanı [System::Collections::Specialized](../)
* Library [Aspose.Slides](../../)