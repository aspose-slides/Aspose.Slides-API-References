---
title: ResultTask()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat ResultTask dengan fungsi yang mengembalikan nilai.
type: docs
weight: 1
url: /id/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask(const Func\<T\>\&) konstruktor


Membuat [ResultTask](../) dengan fungsi yang mengembalikan nilai.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| function | const [Func](../../../system/func/)\<T\>\& | Fungsi yang dieksekusi secara asynchronous yang mengembalikan hasil |

## ResultTask::ResultTask() konstruktor


Implementasi internal. Tidak untuk kode pengguna.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Catatan


Konstruktor internal untuk membuat tugas hasil yang belum diinisialisasi 

## ResultTask::ResultTask(const T\&) konstruktor


Konstruktor internal untuk membuat tugas hasil dengan hasil yang ditentukan.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Lihat Juga

* Kelas [Func](../../../system/func/)
* Kelas [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Pustaka [Aspose.Slides](../../../)