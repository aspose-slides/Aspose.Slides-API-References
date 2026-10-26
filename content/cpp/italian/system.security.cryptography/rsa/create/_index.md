---
title: Create()
second_title: Riferimento API Aspose.Slides per C++
description: Crea l'implementazione predefinita dell'algoritmo RSA.
type: docs
weight: 183
url: /it/system.security.cryptography/rsa/create/
---
## RSA::Create() metodo

Crea l'implementazione predefinita dell'algoritmo [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) metodo

Crea l'implementazione predefinita dell'algoritmo [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Deve essere \"System.Security.Cryptography.RSACryptoServiceProvider\". |

## RSA::Create(int32_t) metodo

Crea l'implementazione predefinita dell'algoritmo [RSA](../) con dimensione della chiave specificata.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | La dimensione della chiave, in bit. |

## RSA::Create(const RSAParameters\&) metodo

Crea l'implementazione predefinita dell'algoritmo [RSA](../) con parametri specificati.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | I parametri per l'algoritmo [RSA](../). |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [RSA](../)
* Classe [String](../../../system/string/)
* Struttura [RSAParameters](../../rsaparameters/)
* Spazio dei nomi [System::Security::Cryptography](../../)
* Libreria [Aspose.Slides](../../../)