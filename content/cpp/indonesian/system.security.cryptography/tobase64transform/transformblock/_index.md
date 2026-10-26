---
title: TransformBlock()
second_title: Referensi API Aspose.Slides untuk C++
description: Memproses blok data dan menyalin data ke array output.
type: docs
weight: 53
url: /id/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) metode

Memproses blok data dan menyalin data ke array output.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca data dari. |
| inputOffset | **int32_t** | Offset buffer input. |
| inputCount | **int32_t** | Jumlah byte yang akan diproses. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer output untuk menyalin data ke dalam; nullptr untuk tidak menyalin. |
| outputOffset | **int32_t** | Offset buffer output. |

### Nilai Kembalian

Jumlah byte yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ToBase64Transform](../)
* Ruang Nama [System::Security::Cryptography](../../)
* Perpustakaan [Aspose.Slides](../../../)