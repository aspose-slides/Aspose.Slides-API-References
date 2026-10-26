---
title: SmartPtr()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek SmartPtr dengan mode yang diperlukan.
type: docs
weight: 1
url: /id/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) konstruktor


Membuat objek [SmartPtr](../) dengan mode yang diperlukan.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) konstruktor


Membuat objek [SmartPtr](../) dengan null-pointer dan mode yang diperlukan.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mode | std::nullptr_t | Pointer mode. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) konstruktor


Membuat [SmartPtr](../) yang menunjuk ke objek yang ditentukan, atau mengonversi pointer mentah menjadi [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | Pointee. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) konstruktor


Membuat salinan [SmartPtr](../). Kedua pointer menunjuk ke objek yang sama setelahnya.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) konstruktor


Membuat salinan [SmartPtr](../). Kedua pointer menunjuk ke objek yang sama setelahnya. Melakukan konversi tipe jika diizinkan.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Type of object pointed by x. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | Pointer to copy. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) konstruktor


Membuat [SmartPtr](../) dengan konstruksi pindah. Secara efektif, menukar dua pointer, bila keduanya berada dalam mode yang sama. x mungkin tidak dapat digunakan setelah pemanggilan.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Pointer to move. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) konstruktor


Mengonversi tipe array yang direferensikan dengan membuat array baru dengan tipe yang berbeda. Berguna jika di C# terdapat konversi tipe array yang tidak didukung di C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Y | Type of source array. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | Pointer to array to create a copy of, but with different type of elements. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. |

## SmartPtr::SmartPtr(const Y\&) konstruktor


Menginisialisasi array kosong. Digunakan untuk menerjemahkan beberapa konstruksi kode C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Y | Placeholder of EmptyArrayInitializer type. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) konstruktor


Membuat [SmartPtr](../) yang berbagi informasi kepemilikan dengan nilai awal ptr, tetapi memegang pointer p yang tidak terkait dan tidak dikelola.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | Another smart pointer to share the ownership to the ownership from. |
| p | [Pointee_](../pointee_/) * | Pointer to an object to manage. |
| mode | [SmartPtrMode](../../smartptrmode/) | Pointer mode. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream"

// Kelas ini berisi sebuah field yang akan dicetak.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// Kelas ini berisi sebuah instance dari kelas Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// Digunakan untuk mencetak sebuah string dari instance kelas Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// Mencetak jumlah shared pointer yang menunjuk ke objek.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Membuat SharedPtr ke sebuah instance kelas Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Membuat SharedPtr yang akan menunjuk ke field dari instance kelas Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // Membuat pointer 'bar' menunjuk ke nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data masih ada dan pointer 'foo' valid.
  PrintMessage(foo);

  return 0;
}
/*
Contoh kode ini menghasilkan output berikut:
Jumlah pointer berbagi: 1
Jumlah pointer berbagi: 2
Jumlah pointer berbagi: 0
Halo, dunia!
*/
``` |

## Lihat Juga

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)