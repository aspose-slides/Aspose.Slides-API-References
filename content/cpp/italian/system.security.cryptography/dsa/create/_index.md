---
title: Create()
second_title: Riferimento API Aspose.Slides per C++
description: Crea l'implementazione predefinita dell'algoritmo DSA.
type: docs
weight: 105
url: /it/system.security.cryptography/dsa/create/
---
## DSA::Create() metodo

Crea l'implementazione predefinita dell'algoritmo [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Valore di ritorno

[DSA](../) algorithm object.

## DSA::Create(const String\&) metodo

Crea l'implementazione predefinita dell'algoritmo [DSA](../).

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Deve essere \"System.Security.Cryptography.DSACryptoServiceProvider\". |

### Valore di ritorno

[DSA](../) algorithm object.

## DSA::Create(int32_t) metodo

Crea l'implementazione predefinita dell'algoritmo [DSA](../) con dimensione della chiave specificata.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | La dimensione della chiave, in bit. |

## DSA::Create(const DSAParameters\&) metodo

Crea l'implementazione predefinita dell'algoritmo [DSA](../) con parametri specificati.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | I parametri per l'algoritmo [DSA](../). |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [DSA](../)
* Classe [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)