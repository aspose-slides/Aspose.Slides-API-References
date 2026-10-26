---
title: Write()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit des données dans le flux.
type: docs
weight: 27
url: /fr/system.security.cryptography/cryptostream/write/
---
## CryptoStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Écrit des données dans le flux.

```cpp
void System::Security::Cryptography::CryptoStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tampon de données source. |
| offset | **int32_t** | Décalage dans le tampon source. |
| count | **int32_t** | Nombre d'octets à écrire. |

## CryptoStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Écrit des données dans le flux.

```cpp
void System::Security::Cryptography::CryptoStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Tampon de données source. |
| offset | **int32_t** | Décalage dans le tampon source. |
| count | **int32_t** | Nombre d'octets à écrire. |

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CryptoStream](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)