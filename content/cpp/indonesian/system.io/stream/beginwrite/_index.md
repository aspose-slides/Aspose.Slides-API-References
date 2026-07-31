---
title: BeginWrite()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi penulisan asinkron.
type: docs
weight: 170
url: /id/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metode


Memulai operasi penulisan asinkron.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer yang berisi data yang akan ditulis |
| offset | int | Offset berbasis-0 dalam **buffer** yang menunjukkan posisi di mana data yang akan ditulis dimulai |
| count | int | Jumlah byte yang akan ditulis |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Callback yang dipanggil ketika operasi selesai |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Data yang disediakan pengguna dan digunakan untuk mengidentifikasi secara unik setiap operasi penulisan asinkron |

### Nilai Kembalian

Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi penulisan asinkron yang dimulai

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [Stream](../)
* Ruang Nama [System::IO](../../)
* Pustaka [Aspose.Slides](../../../)