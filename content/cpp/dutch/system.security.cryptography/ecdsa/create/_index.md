---
title: Create()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt de standaard ECDSA-algoritme-implementatie.
type: docs
weight: 131
url: /nl/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() methode

Maakt de standaard ECDSA-algoritme-implementatie.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Retourwaarde

ECDSA-algoritme-object.

## ECDsa::Create(const ECCurve\&) methode

Maakt de standaard ECDSA-algoritme-implementatie met een nieuw aangemaakte sleutel op de opgegeven curve.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Curve die gebruikt wordt voor het aanmaken van de sleutel. |

### Retourwaarde

ECDSA-algoritme-object.

## ECDsa::Create(const ECParameters\&) methode

Maakt de standaard ECDSA-algoritme-implementatie met behulp van de opgegeven parameters.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parameters die de sleutel vertegenwoordigen. |

### Retourwaarde

ECDSA-algoritme-object.

## ECDsa::Create(const String\&) methode

Maakt de opgegeven ECDSA-algoritme-implementatie.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Algoritme-naam. |

### Retourwaarde

ECDSA-algoritme-object.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ECDsa](../)
* Klasse [String](../../../system/string/)
* Struct [ECCurve](../../eccurve/)
* Struct [ECParameters](../../ecparameters/)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)