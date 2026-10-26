---
title: DynamicWeakPtr()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat smart pointer null.
type: docs
weight: 1
url: /id/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) constructor

Membuat smart pointer null.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) constructor

Membuat smart pointer yang menunjuk ke objek yang diberikan.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Objek yang ditunjuk. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) constructor

Membuat salinan smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | Smart pointer untuk menyalin informasi pointee dari. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) constructor

Membuat salinan smart pointer.

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe pointee penunjuk sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Smart pointer untuk menyalin informasi pointee dari. |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) constructor

Membuat salinan smart pointer.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | Smart pointer untuk menyalin informasi pointee dari. |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) constructor

Membuat smart pointer dengan memindahkan.

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Smart pointer untuk memindahkan informasi pointee dari. Menjadi tidak dapat digunakan setelah pemanggilan. |

## Lihat Juga

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)