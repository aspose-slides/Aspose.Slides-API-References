---
title: Create()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy domyślną implementację algorytmu DSA.
type: docs
weight: 105
url: /pl/system.security.cryptography/dsa/create/
---
## DSA::Create() metoda

Tworzy domyślną implementację algorytmu [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Wartość zwracana

[DSA](../) obiekt algorytmu.

## DSA::Create(const String\&) metoda

Tworzy domyślną implementację algorytmu [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Must be "System.Security.Cryptography.DSACryptoServiceProvider". |

### Wartość zwracana

[DSA](../) obiekt algorytmu.

## DSA::Create(int32_t) metoda

Tworzy domyślną implementację algorytmu [DSA](../) z określonym rozmiarem klucza.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | Rozmiar klucza w bitach. |

## DSA::Create(const DSAParameters\&) metoda

Tworzy domyślną implementację algorytmu [DSA](../) z określonymi parametrami.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Parametry dla algorytmu [DSA](../). |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [DSA](../)
* Klasa [String](../../../system/string/)
* Struktura [DSAParameters](../../dsaparameters/)
* Przestrzeń nazw [System::Security::Cryptography](../../)
* Biblioteka [Aspose.Slides](../../../)