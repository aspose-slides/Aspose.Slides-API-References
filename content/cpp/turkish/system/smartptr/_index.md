---
title: SmartPtr
second_title: Aspose.Slides for C++ API Referansı
description: "Yığın üzerinde tahsis edilen tipleri sarmak için işaretçi sınıfı. Object sınıfından türeten sınıfların belleğini yönetmek için kullanın. Bu işaretçi tipi girişimsel işaretçi semantiğini izler. Referans sayacı ya Object'in içinde ya da Object örneğine sıkı bağlı bir sayaç yapısında tutulur. Her durumda, tüm SmartPtr örnekleri nasıl oluşturulmuş olurlarsa olsunlar tek bir sahiplik grubu oluşturur; bu, std::shared_ptr sınıfının davranışının tersidir. Ham işaretçinin SmartPtr'e dönüştürülmesi, aynı nesneye paylaşımlı referanslar tutan diğer SmartPtr örnekleri olduğu sürece güvenlidir. SmartPtr sınıf örneği iki durumdan birinde olabilir: paylaşımlı işaretçi ve zayıf işaretçi. Nesnenin yaşamasını sağlamak için paylaşımlı referans sayısının pozitif olması gerekir. Hem zayıf hem de paylaşımlı işaretçiler işaret edilen nesneye (metot çağırmak, alanları okumak veya yazmak vb.) erişmek için kullanılabilir, ancak zayıf işaretçiler paylaşımlı işaretçi referans sayımına katılmaz. Nesne, ona son 'paylaşımlı' SmartPtr işaretçi yok edildiğinde silinir. Bu yüzden, nesne oluşturulurken veya yok edilirken başka paylaşımlı SmartPtr işaretçi yoksa bunun gerçekleşmemesine dikkat edin. Bu sorunu düzeltmek için System::Object::ThisProtector gözcü nesnelerini (C++ kodunda) veya CppCTORSelfReference ya da CppSelfReference özniteliğini (çevrilen C# kodunda) kullanın. Benzer şekilde, döngü referanslarını kırmak için System::WeakPtr işaretçi sınıfını veya System::SmartPtrMode::Weak işaretçi modunu (C++ kodunda) ya da CppWeakPtr özniteliğini (çevrilen C# kodunda) kullanın. İki veya daha fazla nesne birbirini 'paylaşımlı' işaretçilerle referans alırsa, hiç silinmezler. İşaretçi tipi (zayıf veya paylaşımlı) çalışma zamanında değiştirilmesi gerekiyorsa, System::SmartPtr<T>::set_Mode() metodunu veya System::DynamicWeakPtr sınıfını kullanın. SmartPtr sınıfı herhangi bir sanal metoda sahip değildir. Kendi bellek yönetim stratejinizi oluşturuyorsanız yalnızca bu sınıftan türetmelisiniz. Bu tip, diğer nesnenin silinmesini yönetmek için bir işaretçidir. Yığında (stack) tahsis edilmeli ve fonksiyonlara değer ya da const referans olarak geçirilmelidir."
type: docs
weight: 1236
url: /tr/system/smartptr/
---
## SmartPtr sınıfı

Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting [Object](../object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](../object/) itself or in counter structure which is tied to [Object](../object/) instance tightly. In any case, all [SmartPtr](./) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./) is safe given there are other [SmartPtr](./) instances holding shared references to the same object. [SmartPtr](./) sınıf örneği can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](../object/) is being deleted when the last 'shared' [SmartPtr](./) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](../weakptr/) pointer class or [System::SmartPtrMode::Weak](../smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./set_mode/) method or [System::DynamicWeakPtr](../dynamicweakptr/) class. [SmartPtr](./) sınıf doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class SmartPtr
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İşaret edilen nesnenin türü. [System::Object](../object/) veya onun alt sınıfı olmalıdır. |

## Metotlar

| Metot | Açıklama |
| --- | --- |
| auto [begin](./begin/)() | Alt koleksiyonun [begin()](./begin/) metoduna erişim sağlayıcı. Sadece SmartPtr_, [begin()](./begin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [begin](./begin/)() const | Alt koleksiyonun [begin()](./begin/) metoduna erişim sağlayıcı. Sadece SmartPtr_, [begin()](./begin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | İşaretçiyi kendi türüne dönüştürür. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | İşaretçiyi static_cast kullanarak temel türe dönüştürür. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | İşaretçiyi dynamic_cast kullanarak türetilmiş türe dönüştürür. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | İşaretçiyi dynamic_cast ile türetilmiş türe dönüştürür. |
| auto [cbegin](./cbegin/)() const | Alt koleksiyonun [cbegin()](./cbegin/) metoduna erişim sağlayıcı. Sadece SmartPtr_, [cbegin()](./cbegin/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [cend](./cend/)() const | Alt koleksiyonun [cend()](./cend/) metoduna erişim sağlayıcı. Sadece SmartPtr_, [cend()](./cend/) metoduna sahip bir özelleştirme türü ise derlenir. |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | İşaret edilen nesne üzerinde const_cast kullanarak işaretçiyi farklı bir türe dönüştürür. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | İşaret edilen nesne üzerinde dynamic_cast kullanarak işaretçiyi farklı bir türe dönüştürür. |
| auto [end](./end/)() | Alt koleksiyonun [end()](./end/) metoduna erişim sağlayıcı. Sadece SmartPtr_, [end()](./end/) metoduna sahip bir özelleştirme türü ise derlenir. |
| auto [end](./end/)() const | Alt koleksiyonun [end()](./end/) metoduna erişim sağlayıcı. Sadece SmartPtr_, [end()](./end/) metoduna sahip bir özelleştirme türü ise derlenir. |
| [Pointee_](./pointee_/) * [get](./get/)() const | İşaret edilen nesneyi alır. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | İşaretçi modunu alır. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | İşaret edilen nesneyi alır, ancak işaretçinin paylaşımlı modda olduğunu doğrular. |
| int [get_shared_count](./get_shared_count/)() const | Referans verilen nesneye mevcut olan paylaşımlı işaretçilerin sayısını, mevcut işaretçiyi de dahil ederek alır. Mevcut işaretçinin paylaşımlı modda olduğunu doğrular. |
| int [GetHashCode](./gethashcode/)() const | İşaret edilen nesnede [GetHashCode()](./gethashcode/) metodunu çağırır. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Şu anda referans verilen nesneyi (varsa) alır veya bir istisna fırlatır. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](./get/) ile aynı. |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Referans verilen nesneyi alır. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | İşaret edilen nesneyi (varsa) alır veya nullptr döndürür. [get()](./get/) ile aynı. |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | İşaret edilen nesnenin belirli bir tür veya alt tür olup olmadığını kontrol eder. C# 'is' semantiğini takip eder. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | İşaretçinin, sahip olduğu (aliasing yapıcı tarafından oluşturulan) nesneden farklı bir nesneyi işaret edip etmediğini kontrol eder. |
| **bool** [IsShared](./isshared/)() const | İşaretçinin paylaşımlı modda olup olmadığını kontrol eder. |
| **bool** [IsWeak](./isweak/)() const | İşaretçinin zayıf (weak) modda olup olmadığını kontrol eder. |
| explicit  [operator bool](./operator_bool/)() const | İşaretçinin null olmadığını kontrol eder. |
| **bool** [operator!](./operator_not/)() const | İşaretçinin null olup olmadığını kontrol eder. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | İşaret edilen nesneye referans alır. İşaretçinin null olmadığını doğrular. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Referans verilen nesnenin üyelerine erişim sağlar. |
| **bool** [operator<](./operator_less/)(Y *) const | [SmartPtr](./) sınıfı için daha az karşılaştırma semantiği sağlar. |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | [SmartPtr](./) sınıfı için daha az karşılaştırma semantiği sağlar. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | [SmartPtr](./) nesnesini taşıma ataması yapar. x kullanılamaz hâle gelir. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | [SmartPtr](./) nesnesini kopya ataması yapar. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | [SmartPtr](./) nesnesini kopya ataması yapar. Gerekli tür dönüşümlerini gerçekleştirir. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Ham işaretçiyi [SmartPtr](./) nesnesine atar. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | İşaretçi değerini nullptr olarak ayarlar. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | İşaretçinin nullptr'a işaret edip etmediğini kontrol eder. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | İşaretçiden aliasing'i (aliasing yapıcı tarafından oluşturulan) kaldırır, işaret ettiği aynı nesneyi (paylaşımlı ise yönetir, zayıf ise izler) sağladığından emin olur. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | İşaret edilen nesneyi ayarlar. |
| void [reset](./reset/)() | İşaretçiyi nullptr'ye işaret edecek şekilde ayarlar. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | İşaretçi modunu ayarlar. Referans verilen nesnenin referans sayılarını değiştirebilir. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | İşaret edilen nesnede (varsa) SetTemplateWeakPtr() metodunu çağırır. |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Gerekli modda [SmartPtr](./) nesnesi oluşturur. |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Gerekli modda null işaretçi [SmartPtr](./) nesnesi oluşturur. |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Belirtilen nesneyi işaret eden [SmartPtr](./) oluşturur veya ham işaretçiyi [SmartPtr](./)'a dönüştürür. |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonradan aynı nesneyi işaret eder. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) nesnesini kopya yapıcı ile oluşturur. Her iki işaretçi de sonradan aynı nesneyi işaret eder. İzin verildiğinde tür dönüşümü yapar. |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) nesnesini taşımalı yapıcı ile oluşturur. Etkin bir şekilde, iki işaretçiyi aynı modda ise değiştirir. x çağrıdan sonra kullanılamaz hâle gelebilir. |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Referans verilen dizinin tipini farklı bir tipte yeni bir dizi oluşturarak dönüştürür. C#'ta desteklenmeyen dizi tip dönüşümü C++'ta yararlıdır. |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | Boş bir dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır. |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | ptr'nin ilk değeriyle mülkiyet bilgisini paylaşan, ancak alakasız ve yönetilmeyen bir işaretçi p tutan bir [SmartPtr](./) oluşturur. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | İşaret edilen nesne üzerinde static_cast kullanarak işaretçiyi farklı bir türe dönüştürür. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Herhangi bir işaretçi tipini [Object](../object/)'a işaretçi tipine dönüştürür. Pointee_ tipinin tam olmasına ihtiyaç duymaz. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Pointee_ tipi için [System::TypeInfo](../typeinfo/) nesnesini almanın kısayolu. |
|  [~SmartPtr](./~smartptr/)() | [SmartPtr](./) nesnesini yok eder. Gerekirse, işaret edilen nesnenin referans sayacını azaltır ve nesneyi siler. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Pointee_](./pointee_/) | İşaret edilen tür. |
| [SmartPtr_](./smartptr_/) | Özelleştirilmiş akıllı işaretçi türü. |
| [ArrayType](./arraytype/) | Pointee_ ile aynı, eğer [System::Array](../array/)'nin bir özelleştirmesi ise, aksi takdirde void. |
| [ValueType](./valuetype/) | İşaret edilen dizinin depolama türü. Yalnızca T, [System::Array](../array/)'nin bir özelleştirmesi ise anlamlıdır. |

## Ayrıca Bakınız

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)