---
title: CreateEncryptor()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Verschlüsselungsobjekt mit expliziten Parametern.
type: docs
weight: 1
url: /de/system.security.cryptography/rijndaelmanaged/createencryptor/
---
## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode


Erstellt ein Verschlüsselungsobjekt mit expliziten Parametern.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verschlüsselungsschlüssel in Byte-Array-Form. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initialwert in Byte-Array-Form. |

### Rückgabewert

Neu erstelltes Verschlüsselungsobjekt.

## RijndaelManaged::CreateEncryptor() Methode


Erstellt ein Verschlüsselungsobjekt mit vom Algorithmusobjekt definierten Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode


Erstellt ein Verschlüsselungsobjekt mit vom Algorithmusobjekt definierten Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../../icryptotransform/)
* Klasse [RijndaelManaged](../)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)