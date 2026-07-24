---
title: TransformFinalBlock()
second_title: Aspose.Slides için C++ API Referansı
description: Verinin son bloğunu işler ve çıktı değerini hesaplar.
type: docs
weight: 14
url: /tr/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metot

Verinin son bloğunu işler ve çıktı değerini hesaplar.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) verileri okumak için. |
| inputOffset | int | Girdi tamponu ofseti. |
| inputCount | int | İşlenecek bayt sayısı. |

### Dönüş Değeri

Tüm girdi dizisi için hesaplanan çıktı.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICryptoTransform](../)
* Ad alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)