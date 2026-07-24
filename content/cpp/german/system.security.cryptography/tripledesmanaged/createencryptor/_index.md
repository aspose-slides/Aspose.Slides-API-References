---
title: CreateEncryptor()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Verschlüsselungsobjekt mit expliziten Parametern.
type: docs
weight: 1
url: /de/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Erstellt ein Verschlüsselungsobjekt mit expliziten Parametern.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Verschlüsselungsschlüssel in Byte-Array-Form. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Initialer Wert in Byte-Array-Form. |

### Rückgabewert

Neu erstelltes Verschlüsselungsobjekt.

## TripleDESManaged::CreateEncryptor() Methode

Erstellt ein Verschlüsselungsobjekt mit von einem Algorithmusobjekt definierten Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Erstellt ein Verschlüsselungsobjekt mit von einem Algorithmusobjekt definierten Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## Siehe Auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../../icryptotransform/)
* Klasse [TripleDESManaged](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)