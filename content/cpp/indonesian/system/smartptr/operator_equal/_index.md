---
title: operator=()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan move-assign pada objek SmartPtr. x menjadi tidak dapat digunakan.
type: docs
weight: 27
url: /id/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) metode

Melakukan move-assign pada objek [SmartPtr](../). x menjadi tidak dapat digunakan.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | Pointer untuk move-assign. |

### Nilai Kembali

Referensi ke objek ini.

## SmartPtr::operator=(const SmartPtr_&) metode

Menyalin-assign objek [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | Pointer untuk copy-assign. |

### Nilai Kembali

Referensi ke objek ini.

## SmartPtr::operator=(const SmartPtr<Q>&) metode

Menyalin-assign objek [SmartPtr](../). Melakukan konversi tipe yang diperlukan.

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Q | Tipe objek yang ditunjuk oleh x. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | const [SmartPtr](../)<Q>& | Pointer untuk copy-assign. |

### Nilai Kembali

Referensi ke objek ini.

## SmartPtr::operator=(Pointee_ *) metode

Menetapkan pointer mentah ke objek [SmartPtr](../).

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | Nilai pointer yang akan ditetapkan. |

### Nilai Kembali

Referensi ke objek ini.

## SmartPtr::operator=(std::nullptr_t) metode

Mengatur nilai pointer ke nullptr.

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### Nilai Kembali

Referensi ke objek ini.

## Lihat Juga

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Kelas [SmartPtr](../)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)