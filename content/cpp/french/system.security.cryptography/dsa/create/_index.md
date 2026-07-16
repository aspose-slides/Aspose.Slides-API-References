---
title: Create()
second_title: Référence API Aspose.Slides pour C++
description: Crée une implémentation d'algorithme DSA par défaut.
type: docs
weight: 105
url: /fr/system.security.cryptography/dsa/create/
---
## DSA::Create() méthode

Crée une implémentation d'algorithme [DSA](../) par défaut.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### Valeur de retour

[DSA](../) algorithm object.

## DSA::Create(const String\&) méthode

Crée une implémentation d'algorithme [DSA](../) par défaut.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | Doit être "System.Security.Cryptography.DSACryptoServiceProvider". |

### Valeur de retour

[DSA](../) algorithm object.

## DSA::Create(int32_t) méthode

Crée une implémentation d'algorithme [DSA](../) par défaut avec la taille de clé spécifiée.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | La taille de la clé, en bits. |

## DSA::Create(const DSAParameters\&) méthode

Crée une implémentation d'algorithme [DSA](../) par défaut avec les paramètres spécifiés.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Les paramètres pour l'algorithme [DSA](../). |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DSA](../)
* Class [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)