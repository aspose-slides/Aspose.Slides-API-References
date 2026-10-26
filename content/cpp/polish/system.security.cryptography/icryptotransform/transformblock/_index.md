---
title: TransformBlock()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Przetwarza blok danych i kopiuje dane do tablicy wyjściowej.
type: docs
weight: 1
url: /pl/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metoda


Przetwarza blok danych i kopiuje dane do tablicy wyjściowej.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu danych. |
| inputOffset | int | Przesunięcie bufora wejściowego. |
| inputCount | int | Liczba bajtów do przetworzenia. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor wyjściowy, do którego kopiowane są dane; nullptr aby nie kopiować. |
| outputOffset | int | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)