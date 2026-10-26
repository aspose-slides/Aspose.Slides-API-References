---
title: Func()
second_title: Referensi API Aspose.Slides untuk C++
description: Konstruktor default yang membuat null-Func.
type: docs
weight: 1
url: /id/system/func/func/
---
## Func::Func() konstruktor

Konstruktor default yang membuat null-Func.

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) konstruktor

Konstruktor yang membuat objek [Func](../) dan menetapkan nilai (baik callback aktual atau nullptr) padanya.

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe argumen. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg | T\&& | Argumen. |

## Func::Func(const Func\&) konstruktor

Konstruktor salin.

```cpp
System::Func<Args>::Func(const Func &func)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) untuk menyalin data dari. |

## Func::Func(Func\&&) konstruktor

Konstruktor pindah.

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) untuk memindahkan data dari. |

## Lihat Juga

* Kelas [Func](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)