---
title: CreateDecryptor()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy obiekt deszyfratora z określonymi parametrami.
type: docs
weight: 14
url: /pl/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Creates decryptor object with explicit parameters.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Klucz szyfrowania w postaci tablicy bajtów. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Wartość początkowa w postaci tablicy bajtów. |

### Wartość zwracana

Nowo utworzony obiekt deszyfratora.

## RC2Managed::CreateDecryptor() metoda


Creates decryptor object with parameters defined by algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Creates decryptor object with parameters defined by algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICryptoTransform](../../icryptotransform/)
* Klasa [RC2Managed](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)