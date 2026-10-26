---
title: TransformBlock()
second_title: Référence API Aspose.Slides pour C++
description: Traite un bloc de données et copie les données dans le tableau de sortie.
type: docs
weight: 53
url: /fr/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) method


Traite un bloc de données et copie les données dans le tableau de sortie.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) à partir duquel lire les données. |
| inputOffset | **int32_t** | Décalage du tampon d'entrée. |
| inputCount | **int32_t** | Nombre d'octets à traiter. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tampon de sortie dans lequel copier les données ; nullptr pour ne rien copier. |
| outputOffset | **int32_t** | Décalage du tampon de sortie. |

### Valeur de retour

Nombre d'octets écrits.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ToBase64Transform](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)