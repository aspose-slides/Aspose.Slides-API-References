---
title: CreateDecryptor()
second_title: Aspose.Slides dla C++ API Reference
description: Tworzy deszyfrator z parametrami powiązanymi z obiektem algorytmu.
type: docs
weight: 196
url: /pl/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() metoda


Tworzy deszyfrator z parametrami powiązanymi z obiektem algorytmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### Wartość zwracana

Nowo utworzony obiekt deszyfratora.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Tworzy deszyfrator z jawnymi parametrami.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Klucz do użycia. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Wartość początkowa do użycia. |

### Wartość zwracana

Nowo utworzony obiekt deszyfratora.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICryptoTransform](../../icryptotransform/)
* Klasa [SymmetricAlgorithm](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)