---
title: Create()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza az alapértelmezett ECDSA algoritmus megvalósítását.
type: docs
weight: 131
url: /hu/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() metódus

Létrehozza az alapértelmezett ECDSA algoritmus megvalósítását.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Visszatérési érték

ECDSA algorithm object.

## ECDsa::Create(const ECCurve\&) metódus

Létrehozza az alapértelmezett ECDSA algoritmus megvalósítását, újonnan létrehozott kulccsal a megadott görbén.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | A kulcs létrehozásához használandó görbe. |

### Visszatérési érték

ECDSA algorithm object.

## ECDsa::Create(const ECParameters\&) metódus

Létrehozza az alapértelmezett ECDSA algoritmus megvalósítását a megadott paraméterekkel.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | A kulcsot képviselő paraméterek. |

### Visszatérési érték

ECDSA algorithm object.

## ECDsa::Create(const String\&) metódus

Létrehozza a megadott ECDSA algoritmus megvalósítását.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Algoritmus neve. |

### Visszatérési érték

ECDSA algorithm object.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ECDsa](../)
* Osztály [String](../../../system/string/)
* Struktúra [ECCurve](../../eccurve/)
* Struktúra [ECParameters](../../ecparameters/)
* Névtere [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)