---
title: TransformBlock()
second_title: Référence API Aspose.Slides pour C++
description: Traite un bloc de données et copie les données dans le tableau de sortie.
type: docs
weight: 1
url: /fr/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) méthode

Traite un bloc de données et copie les données dans le tableau de sortie.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les données depuis. |
| inputOffset | int | Décalage du tampon d'entrée. |
| inputCount | int | Nombre d'octets à traiter. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Tampon de sortie dans lequel copier les données ; nullptr pour ne pas copier. |
| outputOffset | int | Décalage du tampon de sortie. |

### Valeur de retour

Nombre d'octets écrits.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)