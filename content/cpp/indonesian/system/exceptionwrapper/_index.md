---
title: ExceptionWrapper
second_title: Referensi API Aspose.Slides untuk C++
description: Templat yang mewakili pembungkus pengecualian yang diturunkan dari kelas Exception.
type: docs
weight: 833
url: /id/system/exceptionwrapper/
---
## ExceptionWrapper kelas

Templat yang mewakili pembungkus pengecualian yang diturunkan dari kelas Exception.

```cpp
template<typename T>class ExceptionWrapper
```

## Metode

| Metode | Deskripsi |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Membuat instance null dari kelas [ExceptionWrapper](./) yang tidak mewakili pengecualian apa pun. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Membuat sebuah instance dari kelas [ExceptionWrapper](./) yang berisi pointer yang diberikan. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Konstruktor salin. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Konstruktor pindah. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Konstruktor yang meneruskan parameter ke konstruktor kelas Exception dan membuat smart pointer yang menyimpan instance baru kelas Exception. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Operator cast implisit ke SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Mengizinkan akses ke anggota objek Exception. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Operator penugasan. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Operator penugasan pindah. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Jalan pintas untuk mendapatkan objek [System::TypeInfo](../typeinfo/) untuk tipe Exception. |
## Typedefs

| Typedef | Deskripsi |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Digunakan untuk fungsi casting. |
## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)