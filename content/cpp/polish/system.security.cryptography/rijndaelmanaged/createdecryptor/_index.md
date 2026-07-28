---
title: CreateDecryptor()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy obiekt deszyfratora z podanymi jawnie parametrami.
type: docs
weight: 14
url: /pl/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Tworzy obiekt deszyfratora z podanymi jawnie parametrami.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Klucz szyfrowania w postaci tablicy bajtów. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Wartość początkowa w postaci tablicy bajtów. |

### Wartość zwracana

Nowo utworzony obiekt deszyfratora.

## RijndaelManaged::CreateDecryptor() metoda


Tworzy obiekt deszyfratora z parametrami określonymi przez obiekt algorytmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) metoda


Tworzy obiekt deszyfratora z parametrami określonymi przez obiekt algorytmu.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [ICryptoTransform](../../icryptotransform/)
* Klasa [RijndaelManaged](../)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)