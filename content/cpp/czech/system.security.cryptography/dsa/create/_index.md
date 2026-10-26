---
title: Create()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří výchozí implementaci algoritmu DSA.
type: docs
weight: 105
url: /cs/system.security.cryptography/dsa/create/
---
## DSA::Create() metoda

Vytvoří výchozí implementaci algoritmu [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Návratová hodnota

[DSA](../) objekt algoritmu.

## DSA::Create(const String\&) metoda

Vytvoří výchozí implementaci algoritmu [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Musí být "System.Security.Cryptography.DSACryptoServiceProvider". |

### Návratová hodnota

[DSA](../) objekt algoritmu.

## DSA::Create(int32_t) metoda

Vytvoří výchozí implementaci algoritmu [DSA](../) se specifikovanou velikostí klíče.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Velikost klíče v bitech. |

## DSA::Create(const DSAParameters\&) metoda

Vytvoří výchozí implementaci algoritmu [DSA](../) se specifikovanými parametry.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Parametry pro algoritmus [DSA](../). |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DSA](../)
* Class [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)