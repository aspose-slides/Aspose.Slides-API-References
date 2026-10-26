---
title: WeakPtr()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat pointer null.
type: docs
weight: 1
url: /id/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) konstruktor


Membuat pointer null.

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) konstruktor


Membuat weak pointer ke objek yang diberikan.

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) untuk membuat weak pointer ke. |

## WeakPtr::WeakPtr(const SmartPtr_\&) konstruktor


Membuat weak pointer yang merujuk ke pointer yang sama yang ditunjuk oleh ptr.

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | Pointer untuk menyalin nilai pointee dari. |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) konstruktor


Membuat weak pointer yang merujuk ke pointer yang sama yang ditunjuk oleh x.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe pointee dari pointer sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Pointer untuk menyalin nilai pointee dari. |

## WeakPtr::WeakPtr(const WeakPtr_\&) konstruktor


Membuat salinan weak pointer.

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | Pointer untuk menyalin nilai pointee dari. |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) konstruktor


Membuat salinan weak pointer.

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe pointee sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | Pointer untuk menyalin nilai pointee dari. |

## WeakPtr::WeakPtr(SmartPtr_\&&) konstruktor


Membuat weak pointer dengan memindahkan.

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | Pointer untuk memindahkan nilai pointee dari. |

## Lihat Juga

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../../smartptr/smartptr_/)
* Typedef [WeakPtr_](../weakptr_/)
* Class [WeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)