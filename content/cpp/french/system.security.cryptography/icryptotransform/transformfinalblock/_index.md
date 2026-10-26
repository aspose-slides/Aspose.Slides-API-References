---
title: TransformFinalBlock()
second_title: Référence de l'API Aspose.Slides pour C++
description: Traite le dernier bloc de données et calcule la valeur de sortie.
type: docs
weight: 14
url: /fr/system.security.cryptography/icryptotransform/transformfinalblock/
---
## ICryptoTransform::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) méthode

Traite le dernier bloc de données et calcule la valeur de sortie.

```cpp
virtual ArrayPtr<uint8_t> System::Security::Cryptography::ICryptoTransform::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les données. |
| inputOffset | int | Décalage du tampon d'entrée. |
| inputCount | int | Nombre d'octets à traiter. |

### Valeur de retour

Valeur de sortie calculée pour la séquence d'entrée complète.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [ICryptoTransform](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)