---
title: CreateEncryptor()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen encryptor mit den mit dem Algorithmusobjekt verknüpften Parametern.
type: docs
weight: 183
url: /de/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() Methode

Erstellt einen encryptor mit den mit dem Algorithmusobjekt verknüpften Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### Rückgabewert

Neu erstelltes encryptor-Objekt.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) Methode

Erstellt einen encryptor mit expliziten Parametern.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu verwendender Schlüssel. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Zu verwendender Initialwert. |

### Rückgabewert

Neu erstelltes encryptor-Objekt.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICryptoTransform](../../icryptotransform/)
* Klasse [SymmetricAlgorithm](../)
* Namensraum [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)