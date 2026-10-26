---
title: ExceptionWrapper()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah null-instance dari kelas ExceptionWrapper yang tidak mewakili pengecualian apa pun.
type: docs
weight: 14
url: /id/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) konstruktor


Membuat sebuah null-instance dari kelas [ExceptionWrapper](../) yang tidak mewakili pengecualian apa pun.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) konstruktor


Membuat sebuah instance dari kelas [ExceptionWrapper](../) yang berisi pointer yang diberikan.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Smart pointer ke instance kelas Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) konstruktor


Konstruktor salin.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Instance lain dari kelas pembungkus yang harus disalin. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) konstruktor


Konstruktor pindah.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Instance lain dari kelas pembungkus yang harus dipindahkan. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) konstruktor


Konstruktor yang meneruskan parameter ke konstruktor kelas Exception dan membuat smart pointer yang menyimpan instance baru kelas Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Lihat Juga

* Typedef [ExceptionPtr](../../exceptionptr/)
* Kelas [ExceptionWrapper](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)