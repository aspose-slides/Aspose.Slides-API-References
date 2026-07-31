---
title: Write()
second_title: Referensi API Aspose.Slides untuk C++
description: Jika mode wrapping adalah binary, menulis ke aliran subrange byte yang ditentukan dari array byte yang ditentukan, jika tidak mengonversi subrange byte yang ditentukan dari array byte yang ditentukan ke tipe char_type dan kemudian menulis hasilnya ke aliran.
type: docs
weight: 79
url: /id/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Jika mode wrapping adalah binary, menulis ke stream subrange byte yang ditentukan dari array byte yang ditentukan, jika tidak mengkonversi subrange byte yang ditentukan dari array byte yang ditentukan ke tipe char_type dan kemudian menulis hasil ke stream.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Array yang berisi byte yang akan ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrange yang akan ditulis dimulai |
| count | **int32_t** | Jumlah elemen dalam subrange yang akan ditulis |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Menulis subrange byte yang ditentukan dari array byte yang ditentukan ke stream.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampilan array yang berisi byte yang akan ditulis |
| offset | **int32_t** | Indeks berbasis 0 dari elemen dalam **buffer** tempat subrange yang akan ditulis dimulai |
| count | **int32_t** | Jumlah elemen dalam subrange yang akan ditulis |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BasicSTDOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)