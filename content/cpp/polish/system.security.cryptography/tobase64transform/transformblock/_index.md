---
title: TransformBlock()
second_title: Aspose.Slides dla C++ - Referencja API
description: Przetwarza blok danych i kopiuje je do tablicy wyjściowej.
type: docs
weight: 53
url: /pl/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) method

Przetwarza blok danych i kopiuje dane do tablicy wyjściowej.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu danych z. |
| inputOffset | **int32_t** | Przesunięcie bufora wejściowego. |
| inputCount | **int32_t** | Liczba bajtów do przetworzenia. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bufor wyjściowy, do którego kopiowane są dane; nullptr, aby nie kopiować. |
| outputOffset | **int32_t** | Przesunięcie bufora wyjściowego. |

### Wartość zwracana

Liczba zapisanych bajtów.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [ToBase64Transform](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)