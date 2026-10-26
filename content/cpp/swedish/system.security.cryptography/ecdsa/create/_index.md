---
title: Create()
second_title: Aspose.Slides för C++ API-referens
description: Skapar standardimplementation av ECDSA-algoritmen.
type: docs
weight: 131
url: /sv/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() metod


Skapar standardimplementation av ECDSA-algoritmen.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```


### Returvärde

ECDSA-algoritmobjekt.

## ECDsa::Create(const ECCurve\&) metod


Skapar standardimplementation av ECDSA-algoritmen med nyckel som skapats över den specificerade kurvan.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Kurva som ska användas för nyckelgenerering. |

### Returvärde

ECDSA-algoritmobjekt.

## ECDsa::Create(const ECParameters\&) metod


Skapar standardimplementation av ECDSA-algoritmen med de angivna parametrarna.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parametrar som representerar nyckeln. |

### Returvärde

ECDSA-algoritmobjekt.

## ECDsa::Create(const String\&) metod


Skapar den specificerade ECDSA-algoritmen.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Algoritmens namn. |

### Returvärde

ECDSA-algoritmobjekt.

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ECDsa](../)
* Klass [String](../../../system/string/)
* Struktur [ECCurve](../../eccurve/)
* Struktur [ECParameters](../../ecparameters/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)