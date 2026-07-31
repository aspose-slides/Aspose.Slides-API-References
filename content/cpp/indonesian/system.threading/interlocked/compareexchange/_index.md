---
title: CompareExchange()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menukarkan nilai pada variabel: memeriksa apakah variabel sama dengan nilai tertentu dan menyimpan nilai baru hanya jika nilai yang tersimpan cocok dengan yang diharapkan."
type: docs
weight: 79
url: /id/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T&, T, T) Metode


Menukar nilai pada variabel: memeriksa apakah variabel sama dengan nilai tertentu dan menyimpan nilai baru hanya jika nilai yang tersimpan cocok dengan yang diharapkan.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T | Variable type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location1 | T& | Variable reference to change. |
| value | T | Value to store. |
| comparand | T | Value to compare variable's value to before exchanging. |

### Nilai Kembalian

Value of variable on operation start regardless whether it was changed or not.

## Interlocked::CompareExchange(T&, T, T) Metode


Menukar nilai pada variabel: memeriksa apakah variabel sama dengan nilai tertentu dan menyimpan nilai baru hanya jika nilai yang tersimpan cocok dengan yang diharapkan. Not implemented.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| T | Variable type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location1 | T& | Variable reference to change. |
| value | T | Value to store. |
| comparand | T | Value to compare variable's value to before exchanging. |

### Nilai Kembalian

Value of variable on operation start regardless whether it was changed or not.

## Interlocked::CompareExchange(int32_t&, int32_t, int32_t, bool&) Metode


Menukar nilai pada variabel: memeriksa apakah variabel sama dengan nilai tertentu dan menyimpan nilai baru hanya jika nilai yang tersimpan cocok dengan yang diharapkan.

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location1 | **int32_t**& | Variable reference to change. |
| value | **int32_t** | Value to store. |
| comparand | **int32_t** | Value to compare variable's value to before exchanging. |
| succeeded | **bool**& | Referensi ke variabel yang diatur menjadi true jika pertukaran terjadi dan menjadi false sebaliknya. |

### Nilai Kembalian

Value of variable on operation start regardless whether it was changed or not.

## Lihat Juga

* Kelas [Interlocked](../)
* Ruang Nama [System::Threading](../../)
* Perpustakaan [Aspose.Slides](../../../)