---
title: Create()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een standaard RSA-algoritme-implementatie.
type: docs
weight: 183
url: /nl/system.security.cryptography/rsa/create/
---
## RSA::Create() methode

Maakt een standaard [RSA](../) algoritme-implementatie.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) methode

Maakt een standaard [RSA](../) algoritme-implementatie.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Moet \"System.Security.Cryptography.RSACryptoServiceProvider\" zijn. |

## RSA::Create(int32_t) methode

Maakt een standaard [RSA](../) algoritme-implementatie met opgegeven sleutelgrootte.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | De sleutelgrootte, in bits. |

## RSA::Create(const RSAParameters\&) methode

Maakt een standaard [RSA](../) algoritme-implementatie met opgegeven parameters.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | De parameters voor het [RSA](../) algoritme. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [RSA](../)
* Klasse [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)