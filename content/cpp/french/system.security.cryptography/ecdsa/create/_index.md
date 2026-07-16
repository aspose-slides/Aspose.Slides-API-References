---
title: Create()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une implémentation d'algorithme ECDSA par défaut.
type: docs
weight: 131
url: /fr/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() méthode

Crée une implémentation d'algorithme ECDSA par défaut.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### Valeur de retour

Objet d'algorithme ECDSA.

## ECDsa::Create(const ECCurve\&) méthode

Crée une implémentation d'algorithme ECDSA par défaut avec une clé nouvellement créée sur la courbe spécifiée.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Courbe à utiliser pour la création de la clé. |

### Valeur de retour

Objet d'algorithme ECDSA.

## ECDsa::Create(const ECParameters\&) méthode

Crée une implémentation d'algorithme ECDSA par défaut en utilisant les paramètres spécifiés.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Paramètres représentant la clé. |

### Valeur de retour

Objet d'algorithme ECDSA.

## ECDsa::Create(const String\&) méthode

Crée l'implémentation d'algorithme ECDSA spécifiée.

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | Nom de l'algorithme. |

### Valeur de retour

Objet d'algorithme ECDSA.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ECDsa](../)
* Classe [String](../../../system/string/)
* Struct [ECCurve](../../eccurve/)
* Struct [ECParameters](../../ecparameters/)
* Espace de noms [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)