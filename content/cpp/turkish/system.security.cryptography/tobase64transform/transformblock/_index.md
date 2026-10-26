---
title: TransformBlock()
second_title: Aspose.Slides için C++ API Referansı
description: Veri bloğunu işler ve veriyi çıkış dizisine kopyalar.
type: docs
weight: 53
url: /tr/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) method

Veri bloğunu işler ve veriyi çıkış dizisine kopyalar.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) veri okumak için. |
| inputOffset | **int32_t** | Giriş tamponu ofseti. |
| inputCount | **int32_t** | İşlenecek bayt sayısı. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verinin kopyalanacağı çıktı tamponu; kopyalama yapılmaması için nullptr. |
| outputOffset | **int32_t** | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ToBase64Transform](../)
* İsim Alanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)