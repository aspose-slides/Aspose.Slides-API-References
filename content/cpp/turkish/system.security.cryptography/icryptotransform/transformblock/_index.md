---
title: TransformBlock()
second_title: Aspose.Slides for C++ API Referansı
description: Veri bloğunu işler ve verileri çıkış dizisine kopyalar.
type: docs
weight: 1
url: /tr/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metodu


Veri bloğunu işler ve verileri çıkış dizisine kopyalar.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) okuma için kullanılacak veri. |
| inputOffset | int | Giriş tamponu ofseti. |
| inputCount | int | İşlenecek bayt sayısı. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verileri kopyalamak için kullanılacak çıktı tamponu; kopyalama yapmamak için nullptr. |
| outputOffset | int | Çıktı tamponu ofseti. |

### Dönüş Değeri

Yazılan bayt sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICryptoTransform](../)
* Adalanı [System::Security::Cryptography](../../)
* Kütüphane [Aspose.Slides](../../../)