---
title: CreateEncryptor()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy obiekt szyfrujący z podanymi parametrami.
type: docs
weight: 1
url: /pl/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Tworzy obiekt szyfrujący z podanymi parametrami.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Klucz szyfrowania w formie tablicy bajtów. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Wartość początkowa w formie tablicy bajtów. |

### Wartość zwracana

Nowo utworzony obiekt szyfrujący.

## TripleDESManaged::CreateEncryptor() metoda


Tworzy obiekt szyfrujący z parametrami określonymi przez obiekt algorytmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Tworzy obiekt szyfrujący z parametrami określonymi przez obiekt algorytmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICryptoTransform](../../icryptotransform/)
* Klasa [TripleDESManaged](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)