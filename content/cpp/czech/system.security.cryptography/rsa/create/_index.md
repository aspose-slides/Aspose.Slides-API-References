---
title: Create()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Vytvoří výchozí implementaci algoritmu RSA.
type: docs
weight: 183
url: /cs/system.security.cryptography/rsa/create/
---
## RSA::Create() metoda


Vytvoří výchozí implementaci algoritmu [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) metoda


Vytvoří výchozí implementaci algoritmu [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Musí být "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) metoda


Vytvoří výchozí implementaci algoritmu [RSA](../) s určenou velikostí klíče.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Velikost klíče, v bitech. |

## RSA::Create(const RSAParameters\&) metoda


Vytvoří výchozí implementaci algoritmu [RSA](../) s určenými parametry.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Parametry pro algoritmus [RSA](../). |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [RSA](../)
* Třída [String](../../../system/string/)
* Struktura [RSAParameters](../../rsaparameters/)
* Jmenný prostor [System::Security::Cryptography](../../)
* Knihovna [Aspose.Slides](../../../)