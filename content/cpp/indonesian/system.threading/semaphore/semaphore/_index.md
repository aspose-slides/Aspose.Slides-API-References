---
title: Semaphore()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat semaphore tanpa nama.
type: docs
weight: 1
url: /id/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) konstruktor


Membuat semaphore tanpa nama.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| initialCount | int | Jumlah awal entri aktif. |
| maximumCount | int | Jumlah maksimum entri yang diizinkan. |

## Semaphore::Semaphore(int, int, const String\&) konstruktor


Membuat semaphore bernama.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| initialCount | int | Jumlah awal entri aktif. |
| maximumCount | int | Jumlah maksimum entri yang diizinkan. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nama. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) konstruktor


Membuat semaphore bernama.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| initialCount | int | Jumlah awal entri aktif. |
| maximumCount | int | Jumlah maksimum entri yang diizinkan. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nama. |
| createdNew | **bool**\& | Referensi ke variabel yang diatur menjadi true jika semaphore dibuat dan menjadi false jika semaphore yang ada dengan nama yang sama digunakan kembali |

## Lihat Juga

* Kelas [Semaphore](../)
* Kelas [String](../../../system/string/)
* Ruang nama [System::Threading](../../)
* Perpustakaan [Aspose.Slides](../../../)