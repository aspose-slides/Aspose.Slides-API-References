---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.
type: docs
weight: 209
url: /id/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte untuk ditulis. |
| offset | **int32_t** | Offset dalam byte pada array yang ditentukan. |
| size | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode

Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array yang berisi byte untuk ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** di mana subrentang yang akan ditulis dimulai |
| size | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)