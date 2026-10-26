---
title: Task()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah Task dengan aksi yang akan dijalankan.
type: docs
weight: 1
url: /id/system.threading.tasks/task/task/
---
## Task::Task(const Action<>\&) konstruktor


Membuat sebuah [Task](../) dengan aksi yang akan dijalankan.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Aksi yang akan dijalankan secara asinkron |

## Task::Task(const Action<>\&, const CancellationToken\&) konstruktor


Membuat sebuah [Task](../) dengan aksi dan token pembatalan.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| action | const [Action](../../../system/action/)<>\& | Aksi yang akan dijalankan secara asinkron |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token untuk memantau permintaan pembatalan |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) konstruktor


Membuat sebuah [Task](../) dengan aksi berstatus dan objek status.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Aksi yang akan dijalankan (menerima objek status) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objek status yang didefinisikan pengguna dan diteruskan ke aksi |

## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) konstruktor


Membuat sebuah [Task](../) dengan aksi berstatus, objek status, dan token pembatalan.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| action | const [Action](../../../system/action/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\& | Aksi yang akan dijalankan (menerima objek status) |
| state | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objek status yang didefinisikan pengguna dan diteruskan ke aksi |
| cancellationToken | const [CancellationToken](../../../system.threading/cancellationtoken/)\& | Token untuk memantau permintaan pembatalan |

## Task::Task() konstruktor


Konstruktor internal untuk membuat tugas yang belum diinisialisasi.

```cpp
System::Threading::Tasks::Task::Task()
```

## Lihat Juga

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Task](../)
* Kelas [CancellationToken](../../../system.threading/cancellationtoken/)
* Kelas [Object](../../../system/object/)
* Ruang nama [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)