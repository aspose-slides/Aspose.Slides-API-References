---
title: TransformFinalBlock()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Przetwarza ostatni blok danych i oblicza skrót.
type: docs
weight: 79
url: /pl/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) metoda

Przetwarza ostatni blok danych i oblicza skrót.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) do odczytu danych. |
| inputOffset | int | Przesunięcie bufora wejściowego. |
| inputCount | int | Liczba bajtów do przetworzenia. |

### Wartość zwracana

Skrót obliczony dla całej sekwencji danych.

## Zobacz także

* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [HashAlgorithm](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)