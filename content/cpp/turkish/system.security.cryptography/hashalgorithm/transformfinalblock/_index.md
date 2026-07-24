---
title: TransformFinalBlock()
second_title: Aspose.Slides for C++ API Referansı
description: Verinin son bloğunu işler ve karmayı hesaplar.
type: docs
weight: 79
url: /tr/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) method

Verinin son bloğunu işler ve karmayı hesaplar.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) okunacak veri. |
| inputOffset | int | Giriş tamponu ofseti. |
| inputCount | int | İşlenecek bayt sayısı. |

### Dönüş Değeri

Tüm veri dizisi için hesaplanan karma.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [HashAlgorithm](../)
* Ad Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)