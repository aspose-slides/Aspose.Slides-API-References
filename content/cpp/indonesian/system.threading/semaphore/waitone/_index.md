---
title: WaitOne()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengunci semaphore. Melakukan penantian tanpa batas jika diperlukan.
type: docs
weight: 40
url: /id/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() metode


Mengunci semaphore. Melakukan penantian tanpa batas jika diperlukan.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Nilai Kembali

Selalu mengembalikan true karena tidak mengembalikan hingga semaphore terkunci.

## Semaphore::WaitOne(int) metode


Mengunci semaphore. Melakukan penantian jika diperlukan.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| millisecondsTimeout | int | Batas waktu penantian dalam milidetik. |

### Nilai Kembali

Mengembalikan true jika semaphore terkunci atau false jika batas waktu terlampaui.

## Lihat Juga

* Kelas [Semaphore](../)
* Ruang Nama [System::Threading](../../)
* Library [Aspose.Slides](../../../)