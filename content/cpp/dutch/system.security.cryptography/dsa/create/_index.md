---
title: Create()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een standaard DSA-algoritme-implementatie.
type: docs
weight: 105
url: /nl/system.security.cryptography/dsa/create/
---
## DSA::Create() methode

Maakt een standaard [DSA](../) algoritme-implementatie.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Retourwaarde

[DSA](../) algoritme-object.

## DSA::Create(const String\&) methode

Maakt een standaard [DSA](../) algoritme-implementatie.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Moet "System.Security.Cryptography.DSACryptoServiceProvider" zijn. |

### Retourwaarde

[DSA](../) algoritme-object.

## DSA::Create(int32_t) methode

Maakt een standaard [DSA](../) algoritme-implementatie met opgegeven sleutelgrootte.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | De sleutelgrootte, in bits. |

## DSA::Create(const DSAParameters\&) methode

Maakt een standaard [DSA](../) algoritme-implementatie met opgegeven parameters.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | De parameters voor het [DSA](../) algoritme. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DSA](../)
* Class [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)