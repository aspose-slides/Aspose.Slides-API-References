---
title: ECDsaBotan()
second_title: Référence API Aspose.Slides pour C++
description: Constructeur. Utilise les paramètres par défaut.
type: docs
weight: 1
url: /fr/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() constructeur

Constructeur. Utilise les paramètres par défaut.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | Paramètres de l'algorithme. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | Courbe utilisée pour créer la paire de clés publique/privée. |

## ECDsaBotan::ECDsaBotan(int32_t) constructeur

Constructeur.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key_size | **int32_t** | Taille de la clé en bits. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Clé publique Botan. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) constructeur

Constructeur.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Clé privée Botan. |

## Voir aussi

* Classe [ECDsaBotan](../)
* Structure [ECParameters](../../ecparameters/)
* Structure [ECCurve](../../eccurve/)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)