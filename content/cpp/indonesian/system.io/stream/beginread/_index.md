---
title: BeginRead()
second_title: Referensi API Aspose.Slides untuk C++
description: Memulai operasi baca asinkron.
type: docs
weight: 157
url: /id/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) metode


Memulai operasi baca asinkron.

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer untuk dibaca |
| offset | int | Offset berbasis 0 dalam **buffer** yang menunjukkan posisi mulai menulis data yang dibaca |
| count | int | Jumlah byte yang akan dibaca |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | Callback yang akan dipanggil ketika operasi selesai |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | Data yang disediakan pengguna yang digunakan untuk mengidentifikasi secara unik setiap operasi baca asinkron |

### Nilai Kembali

Objek [IAsyncResult](../../../system/iasyncresult/) yang mewakili operasi baca asinkron yang dimulai

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Kelas [IAsyncResult](../../../system/iasyncresult/)
* Kelas [Object](../../../system/object/)
* Kelas [Stream](../)
* Ruang Nama [System::IO](../../)
* Library [Aspose.Slides](../../../)