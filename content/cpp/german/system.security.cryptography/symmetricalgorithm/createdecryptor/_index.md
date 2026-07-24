---
title: CreateDecryptor()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen Decryptor mit den dem Algorithmusobjekt zugehörigen Parametern.
type: docs
weight: 196
url: /de/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() Methode

Erstellt einen Decryptor mit den dem Algorithmusobjekt zugehörigen Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### Rückgabewert

Neu erstelltes Decryptor-Objekt.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Erstellt einen Decryptor mit expliziten Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu verwendender Schlüssel. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu verwendender Initialwert. |

### Rückgabewert

Neu erstelltes Decryptor-Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../../icryptotransform/)
* Klasse [SymmetricAlgorithm](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)