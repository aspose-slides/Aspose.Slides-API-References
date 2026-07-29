---
title: Create()
second_title: Aspose.Slides för C++ API-referens
description: Skapar standard RSA-algoritmimplementation.
type: docs
weight: 183
url: /sv/system.security.cryptography/rsa/create/
---
## RSA::Create() metod

Skapar standard [RSA](../) algoritmimplementation.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) metod

Skapar standard [RSA](../) algoritmimplementation.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Måste vara "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) metod

Skapar standard [RSA](../) algoritmimplementation med angiven nyckelstorlek.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Nyckelstorleken i bitar. |

## RSA::Create(const RSAParameters\&) metod

Skapar standard [RSA](../) algoritmimplementation med angivna parametrar.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Parametrarna för [RSA](../)-algoritmen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSA](../)
* Class [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)