---
title: Create()
second_title: Aspose.Slides C++ API-referencia
description: Létrehozza az alapértelmezett RSA algoritmus implementációt.
type: docs
weight: 183
url: /hu/system.security.cryptography/rsa/create/
---
## RSA::Create() metódus

Létrehozza az alapértelmezett [RSA](../) algoritmus implementációt.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) metódus

Létrehozza az alapértelmezett [RSA](../) algoritmus implementációt.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Ennek a "System.Security.Cryptography.RSACryptoServiceProvider"-nek kell lennie. |

## RSA::Create(int32_t) metódus

Létrehozza az alapértelmezett [RSA](../) algoritmus implementációt a megadott kulcsmérettel.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | A kulcsméret bitben. |

## RSA::Create(const RSAParameters\&) metódus

Létrehozza az alapértelmezett [RSA](../) algoritmus implementációt a megadott paraméterekkel.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | A [RSA](../) algoritmus paraméterei. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [RSA](../)
* Osztály [String](../../../system/string/)
* Struktúra [RSAParameters](../../rsaparameters/)
* Névtér [System::Security::Cryptography](../../)
* Könyvtár [Aspose.Slides](../../../)