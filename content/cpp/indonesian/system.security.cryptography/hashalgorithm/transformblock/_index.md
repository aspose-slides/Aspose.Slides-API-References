---
title: TransformBlock()
second_title: Aspose.Slides untuk Referensi API C++
description: Memproses blok data dan menyalin data ke array keluaran.
type: docs
weight: 66
url: /id/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metode

Memproses blok data dan menyalin data ke array keluaran.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca data dari. |
| inputOffset | int | Offset buffer input. |
| inputCount | int | Jumlah byte yang diproses. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer keluaran untuk menyalin data ke dalamnya; nullptr untuk tidak menyalin. |
| outputOffset | int | Offset buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)