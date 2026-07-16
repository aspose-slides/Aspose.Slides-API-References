---
title: Read()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit les données du flux.
type: docs
weight: 14
url: /fr/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Lit les données du flux.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tampon de données de destination. |
| offset | **int32_t** | Décalage dans le tampon de destination. |
| count | **int32_t** | Nombre d'octets à lire. |

### Valeur de retour

Nombre d'octets réellement lus.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) méthode

Lit les données du flux.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampon de données de destination. |
| offset | **int32_t** | Décalage dans le tampon de destination. |
| count | **int32_t** | Nombre d'octets à lire. |

### Valeur de retour

Nombre d'octets réellement lus.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CryptoStream](../)
* Espace de noms [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)