---
title: operator=()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan penugasan pindah pada smart pointer.
type: docs
weight: 27
url: /id/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_\&&) metode

Melakukan penugasan pindah pada smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | Penunjuk nilai yang akan dipindahkan penugasan. |

### Nilai Kembalian

Referensi diri.

## DynamicWeakPtr::operator=(const SmartPtr_\&) metode

Menyalin penugasan smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | Penunjuk nilai yang akan disalin penugasan. |

### Nilai Kembalian

Referensi diri.

## DynamicWeakPtr::operator=(const SmartPtr\<Q\>\&) metode

Menyalin penugasan smart pointer.

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe pointee sumber. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | Penunjuk nilai yang akan disalin penugasan. |

### Nilai Kembalian

Referensi diri.

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) metode

Menetapkan smart pointer.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | Nilai penunjuk. |

### Nilai Kembalian

Referensi diri.

## DynamicWeakPtr::operator=(std::nullptr_t) metode

Mengatur smart pointer menjadi null.

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### Nilai Kembalian

Referensi diri.

## Lihat Juga

* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../../smartptr/pointee_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)