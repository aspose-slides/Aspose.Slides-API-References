---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika mode pembungkus adalah biner, menulis ke aliran subrentang byte yang ditentukan dari array byte yang ditentukan, jika tidak mengonversi subrentang byte yang ditentukan dari array byte yang ditentukan ke tipe char_type dan kemudian menulis hasil ke aliran. Tidak didukung!
type: docs
weight: 79
url: /id/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metode

Jika mode pembungkus adalah biner, menulis ke aliran subrentang byte yang ditentukan dari array byte yang ditentukan, jika tidak mengonversi subrentang byte yang ditentukan dari array byte yang ditentukan ke tipe char_type dan kemudian menulis hasil ke aliran. Tidak didukung!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis. |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai. |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metode

Menulis subrentang byte yang ditentukan dari array byte yang ditentukan ke aliran.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array yang berisi byte yang akan ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrentang yang akan ditulis dimulai |
| count | **int32_t** | Jumlah elemen dalam subrentang yang akan ditulis |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [BasicSTDIStreamWrapper](../)
* Namespace [System::IO](../../)
* Perpustakaan [Aspose.Slides](../../../)