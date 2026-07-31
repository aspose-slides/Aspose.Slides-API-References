---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.
type: docs
weight: 248
url: /id/system.io/filestream/write/
---
## FileStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode


Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
void System::IO::FileStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis. |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai. |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis. |

## FileStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode


Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
void System::IO::FileStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array yang berisi byte yang akan ditulis. |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai. |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis. |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)