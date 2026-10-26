---
title: Create()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří výchozí implementaci algoritmu ECDSA.
type: docs
weight: 131
url: /cs/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() metoda

Vytvoří výchozí implementaci algoritmu ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Návratová hodnota

Objekt algoritmu ECDSA.

## ECDsa::Create(const ECCurve\&) metoda

Vytvoří výchozí implementaci algoritmu ECDSA s nově vytvořeným klíčem na zadané křivce.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Křivka použitá pro vytvoření klíče. |

### Návratová hodnota

Objekt algoritmu ECDSA.

## ECDsa::Create(const ECParameters\&) metoda

Vytvoří výchozí implementaci algoritmu ECDSA pomocí zadaných parametrů.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Parametry představující klíč. |

### Návratová hodnota

Objekt algoritmu ECDSA.

## ECDsa::Create(const String\&) metoda

Vytvoří specifikovanou implementaci algoritmu ECDSA.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Název algoritmu. |

### Návratová hodnota

Objekt algoritmu ECDSA.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ECDsa](../)
* Třída [String](../../../system/string/)
* Struktura [ECCurve](../../eccurve/)
* Struktura [ECParameters](../../ecparameters/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)