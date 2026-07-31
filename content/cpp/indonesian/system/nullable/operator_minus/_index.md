---
title: operator-()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengurangi nilai nullable dan nilai yang menunjuk ke null.
type: docs
weight: 222
url: /id/system/nullable/operator_minus/
---
## Nullable::operator-(T1) const metode

Subtracts nullable and null-pointed values.

```cpp
template<typename T1,typename> Nullable<T> System::Nullable<T>::operator-(T1) const
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Right operand type, should be nullptr_t. |

### Nilai Kembali

Empty [Nullable](../) object.

## Nullable::operator-(const T1\&) const metode

Subtracts nullable and non-nullable values.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator-(const T1 &other) const -> Nullable<decltype(get_Value() - other)>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Right operand type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const T1\& | value to subtract. |

### Nilai Kembali

Subtraction result.

## Nullable::operator-(const Nullable\<T1\>\&) const metode

Subtracts nullable values.

```cpp
template<typename T1> auto System::Nullable<T>::operator-(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value() - other.get_Value())>
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Right operand type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | value to subtract. |

### Nilai Kembali

Subtraction result.

## Lihat Juga

* Kelas [Nullable](../)
* Ruangnama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)