---
title: TransformBlock()
second_title: Referensi API Aspose.Slides untuk C++
description: Memproses blok data dan menyalin data ke array keluaran.
type: docs
weight: 1
url: /id/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


Memproses blok data dan menyalin data ke array keluaran.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca data dari. |
| inputOffset | int | Offset buffer input. |
| inputCount | int | Jumlah byte yang akan diproses. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer output untuk menyalin data ke dalam; nullptr untuk tidak menyalin. |
| outputOffset | int | Offset buffer output. |

### Nilai Kembali

Jumlah byte yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICryptoTransform](../)
* Ruang Nama [System::Security::Cryptography](../../)
* Perpustakaan [Aspose.Slides](../../../)