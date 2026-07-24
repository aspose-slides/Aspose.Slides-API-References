---
title: SmartPtr()
second_title: Aspose.Slides için C++ API Referansı
description: Gerekli modda SmartPtr nesnesi oluşturur.
type: docs
weight: 1
url: /tr/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) yapıcı

Gerekli modda [SmartPtr](../) nesnesi oluşturur.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) yapıcı

Gerekli modda null işaretçi [SmartPtr](../) nesnesi oluşturur.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer mode. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) yapıcı

[SmartPtr](../) nesnesi oluşturur ve belirtilen nesneye işaret eder, ya da ham işaretçiyi [SmartPtr](../)'e dönüştürür.

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) yapıcı

[SmartPtr](../) nesnesini kopya yapıcıyla oluşturur. Her iki işaretçi de daha sonra aynı nesneyi işaret eder.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) yapıcı

[SmartPtr](../) nesnesini kopya yapıcıyla oluşturur. Her iki işaretçi de daha sonra aynı nesneyi işaret eder. İzin verildiğinde tip dönüşümü yapar.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Q | Type of object pointed by x. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) yapıcı

[SmartPtr](../) nesnesini taşıma yapıcıyla oluşturur. Aslında, iki işaretçi aynı moddaysa takas edilir. x, çağrıdan sonra kullanılamaz olabilir.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) yapıcı

Referans verilen dizinin tipini, farklı tipte yeni bir dizi oluşturarak dönüştürür. C#'ta desteklenmeyen bir dizi tip dönüşümü C++'ta kullanılabilir.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Y | Type of source array. |

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Pointer to array to create a copy of, but with different type of elements. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const Y\&) yapıcı

Boş bir dizi başlatır. Bazı C# kod yapılarının çevrilmesinde kullanılır.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Y | Placeholder of EmptyArrayInitializer type. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) yapıcı

[SmartPtr](../) nesnesi, ptr'nin başlangıç değerinin sahiplik bilgisini paylaşır, ancak ilişkili olmayan ve yönetilmeyen p işaretçisini tutar.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Another smart pointer to share the ownership to the ownership from. |
| p | [Pointee_](../pointee_/) * | Pointer to an object to manage. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// Bu sınıf, yazdırılacak bir alan içerir.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Bu sınıf, Foo sınıfının bir örneğini içerir.
class Bar : public System::Object
{
public:
  Foo data;
};

// Foo sınıfı örneğinden bir dizeyi yazdırmak için kullanılır.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Nesneyi işaret eden paylaşımlı işaretçilerin sayısını yazdırır.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Bar sınıfının bir örneğine SharedPtr oluştur.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Bar sınıfı örneğinin alanına işaret edecek SharedPtr oluştur.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // 'bar' işaretçisini nullptr yap.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data hâlâ var ve 'foo' işaretçisi geçerlidir.
  PrintMessage(foo);

  return 0;
}
/*
Bu kod örneği aşağıdaki çıktıyı üretir:
Paylaşımlı işaretçilerin sayısı: 1
Paylaşımlı işaretçilerin sayısı: 2
Paylaşımlı işaretçilerin sayısı: 0
Merhaba, dünya!
*/
```

## Ayrıca Bakınız

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Sınıf [SmartPtr](../)
* Sınıf [Array](../../array/)
* Ad alanı [System](../../)
* Library [Aspose.Slides](../../../)