---
title: TransformFinalBlock()
second_title: Referensi API Aspose.Slides untuk C++
description: Memproses blok data terakhir dan menghitung hash.
type: docs
weight: 79
url: /id/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metode


Memproses blok data terakhir dan menghitung hash.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca data dari. |
| inputOffset | int | Offset buffer masukan. |
| inputCount | int | Jumlah byte yang diproses. |

### Nilai Kembalian

Hash yang dihitung untuk seluruh urutan data.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Pustaka [Aspose.Slides](../../../)