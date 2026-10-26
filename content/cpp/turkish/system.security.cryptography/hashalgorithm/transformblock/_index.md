---
title: TransformBlock()
second_title: Aspose.Slides için C++ API Referansı
description: Veri bloğunu işler ve verileri çıktı dizisine kopyalar.
type: docs
weight: 66
url: /tr/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) yöntemi

Veri bloğunu işler ve verileri çıktı dizisine kopyalar.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) veriyi okumak için. |
| inputOffset | int | Giriş tamponu ofseti. |
| inputCount | int | İşlenecek bayt sayısı. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verileri kopyalamak için kullanılacak çıktı tamponu; kopyalama yapılmaması için nullptr. |
| outputOffset | int | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan bayt sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [HashAlgorithm](../)
* Ad alanı [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)