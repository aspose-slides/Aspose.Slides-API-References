---
title: Create()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Tworzy domyślną implementację algorytmu RSA.
type: docs
weight: 183
url: /pl/system.security.cryptography/rsa/create/
---
## RSA::Create() metoda

Tworzy domyślną implementację [RSA](../) algorytmu.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) metoda

Tworzy domyślną implementację [RSA](../) algorytmu.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Musi być "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) metoda

Tworzy domyślną implementację [RSA](../) algorytmu z określonym rozmiarem klucza.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Rozmiar klucza w bitach. |

## RSA::Create(const RSAParameters\&) metoda

Tworzy domyślną implementację [RSA](../) algorytmu z określonymi parametrami.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | Parametry dla algorytmu [RSA](../). |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [RSA](../)
* Klasa [String](../../../system/string/)
* Struktura [RSAParameters](../../rsaparameters/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)