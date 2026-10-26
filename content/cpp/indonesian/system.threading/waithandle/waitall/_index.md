---
title: WaitAll()
second_title: Referensi API Aspose.Slides untuk C++
description: Menunggu semua handle dipicu.
type: docs
weight: 1
url: /id/system.threading/waithandle/waitall/
---
## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, int) method


Menunggu semua handle dipicu.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, int millisecondsTimeout)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles yang akan ditunggu. |
| millisecondsTimeout | int | [Timeout](../../timeout/) untuk menunggu, dalam milidetik; -1 berarti menunggu tak terbatas, 0 berarti periksa dan kembali, nilai positif merupakan batas waktu. |

### Nilai Kembali

True if all handles fired, false if timeout exceeded.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&, TimeSpan) method


Menunggu semua handle dipicu.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles, TimeSpan timeout)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles yang akan ditunggu. |
| timeout | [TimeSpan](../../../system/timespan/) | Sebuah [System::TimeSpan](../../../system/timespan/) yang mewakili jumlah milidetik untuk menunggu, atau sebuah [System::TimeSpan](../../../system/timespan/) yang mewakili -1 milidetik untuk menunggu tanpa batas. |

### Nilai Kembali

True if all handles fired, false if timeout exceeded.

## WaitHandle::WaitAll(const System::ArrayPtr\<System::SharedPtr\<WaitHandle\>\>\&) method


Menunggu semua handle dipicu.

```cpp
static bool System::Threading::WaitHandle::WaitAll(const System::ArrayPtr<System::SharedPtr<WaitHandle>> &waitHandles)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| waitHandles | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[WaitHandle](../)\>\>\& | Handles yang akan ditunggu. |

### Nilai Kembali

True ketika setiap elemen dalam waitHandles telah menerima sinyal; jika tidak, metode tidak pernah mengembalikan nilai.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [WaitHandle](../)
* Class [TimeSpan](../../../system/timespan/)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)