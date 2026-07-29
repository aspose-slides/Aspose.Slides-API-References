---
title: Create()
second_title: Aspose.Slides för C++ API-referens
description: Skapar standard DSA-algoritmimplementation.
type: docs
weight: 105
url: /sv/system.security.cryptography/dsa/create/
---
## DSA::Create() metod

Skapar standard [DSA](../) algoritmimplementation.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Returvärde

[DSA](../) algoritmobjekt.

## DSA::Create(const String\&) metod

Skapar standard [DSA](../) algoritmimplementation.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Måste vara \"System.Security.Cryptography.DSACryptoServiceProvider\". |

### Returvärde

[DSA](../) algoritmobjekt.

## DSA::Create(int32_t) metod

Skapar standard [DSA](../) algoritmimplementation med specificerad nyckelstorlek.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Nyckelstorleken i bit. |

## DSA::Create(const DSAParameters\&) metod

Skapar standard [DSA](../) algoritmimplementation med specificerade parametrar.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Parametrarna för [DSA](../)-algoritmen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [DSA](../)
* Klass [String](../../../system/string/)
* Struktur [DSAParameters](../../dsaparameters/)
* Namnrymd [System::Security::Cryptography](../../)
* Bibliotek [Aspose.Slides](../../../)