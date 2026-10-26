---
title: Create()
second_title: Aspose.Slides C++ API referenciája
description: Létrehozza az alapértelmezett DSA algoritmus implementációját.
type: docs
weight: 105
url: /hu/system.security.cryptography/dsa/create/
---
## DSA::Create() metódus


Létrehozza az alapértelmezett [DSA](../) algoritmus implementációját.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```


### Visszatérési érték

[DSA](../) algorithm object.

## DSA::Create(const String\&) metódus


Létrehozza az alapértelmezett [DSA](../) algoritmus implementációját.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | \"System.Security.Cryptography.DSACryptoServiceProvider\" kell legyen. |

### Visszatérési érték

[DSA](../) algorithm object.

## DSA::Create(int32_t) metódus


Létrehozza az alapértelmezett [DSA](../) algoritmus implementációt a megadott kulcsmérettel.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | A kulcs mérete bitekben. |

## DSA::Create(const DSAParameters\&) metódus


Létrehozza az alapértelmezett [DSA](../) algoritmus implementációt a megadott paraméterekkel.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | A [DSA](../) algoritmus paraméterei. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* osztály [DSA](../)
* osztály [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* névtér [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)