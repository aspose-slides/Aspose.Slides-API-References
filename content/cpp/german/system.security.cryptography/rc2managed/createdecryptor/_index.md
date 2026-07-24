---
title: CreateDecryptor()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Entschlüsselungsobjekt mit expliziten Parametern.
type: docs
weight: 14
url: /de/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Erstellt ein Entschlüsselungsobjekt mit expliziten Parametern.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verschlüsselungsschlüssel in Byte-Array-Form. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initialwert in Byte-Array-Form. |

### Rückgabewert

Neu erstelltes Entschlüsselungsobjekt.

## RC2Managed::CreateDecryptor() Methode

Erstellt ein Entschlüsselungsobjekt mit vom Algorithmusobjekt definierten Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Erstellt ein Entschlüsselungsobjekt mit vom Algorithmusobjekt definierten Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RC2Managed](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)