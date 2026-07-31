---
title: operator+()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan instance kelas Nullable<T> yang dibangun secara default.
type: docs
weight: 209
url: /id/system/nullable/operator_plus/
---
## Nullable::operator+(std::nullptr_t) const method


Mengembalikan instance kelas Nullable<T> yang dibangun secara default.

```cpp
Nullable<T> System::Nullable<T>::operator+(std::nullptr_t) const
```

## Nullable::operator+(const T1\&) const method


Menjumlahkan nilai nullable dan non-nullable.

```cpp
template<typename T1,typename> auto System::Nullable<T>::operator+(const T1 &other) const -> Nullable<decltype(get_Value()+other)>
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T1 | Tipe operand kanan. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | nilai untuk ditambahkan. |

### Nilai Kembali

Hasil penjumlahan.

## Nullable::operator+(const Nullable\<T1\>\&) const method


Menjumlahkan nilai nullable.

```cpp
template<typename T1> auto System::Nullable<T>::operator+(const Nullable<T1> &other) const -> System::Nullable<decltype(get_Value()+other.get_Value())>
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T1 | Tipe operand kanan. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [Nullable](../)\<T1\>\& | nilai untuk ditambahkan. |

### Nilai Kembali

Hasil penjumlahan.

## Lihat Juga

* Kelas [Nullable](../)
* Ruang nama [System](../../)
* Pustaka [Aspose.Slides](../../../)