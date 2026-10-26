---
title: TransformBlock()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Przetwarza blok danych i kopiuje dane do tablicy wyjściowej.
type: docs
weight: 66
url: /pl/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) metoda

Przetwarza blok danych i kopiuje dane do tablicy wyjściowej.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu danych z. |
| inputOffset | int | Przesunięcie bufora wejściowego. |
| inputCount | int | Liczba bajtów do przetworzenia. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor wyjściowy, do którego kopiowane są dane; nullptr aby nie kopiować. |
| outputOffset | int | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [HashAlgorithm](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)