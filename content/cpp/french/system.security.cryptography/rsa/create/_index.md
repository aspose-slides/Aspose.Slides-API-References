---
title: Create()
second_title: Référence API Aspose.Slides pour C++
description: Crée l'implémentation par défaut de l'algorithme RSA.
type: docs
weight: 183
url: /fr/system.security.cryptography/rsa/create/
---
## RSA::Create() méthode


Crée l'implémentation d'algorithme par défaut [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) méthode


Crée l'implémentation d'algorithme par défaut [RSA](../).

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Must be "System.Security.Cryptography.RSACryptoServiceProvider". |

## RSA::Create(int32_t) méthode


Crée l'implémentation d'algorithme par défaut [RSA](../) avec la taille de clé spécifiée.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | The key size, in bits. |

## RSA::Create(const RSAParameters\&) méthode


Crée l'implémentation d'algorithme par défaut [RSA](../) avec les paramètres spécifiés.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | The parameters for the [RSA](../) algorithm. |

## Voir aussi

* typedef [SharedPtr](../../../system/sharedptr/)
* classe [RSA](../)
* classe [String](../../../system/string/)
* structure [RSAParameters](../../rsaparameters/)
* espace de noms [System::Security::Cryptography](../../)
* bibliothèque [Aspose.Slides](../../../)