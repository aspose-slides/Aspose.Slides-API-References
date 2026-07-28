---
title: TransformFinalBlock()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Przetwarza ostatni blok danych i oblicza wartość wyjściową.
type: docs
weight: 14
url: /pl/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metoda

Przetwarza ostatni blok danych i oblicza wartość wyjściową.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu danych. |
| inputOffset | int | Przesunięcie bufora wejściowego. |
| inputCount | int | Liczba bajtów do przetworzenia. |

### Wartość zwracana

Wyjście obliczone dla całej sekwencji wejściowej.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICryptoTransform](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)