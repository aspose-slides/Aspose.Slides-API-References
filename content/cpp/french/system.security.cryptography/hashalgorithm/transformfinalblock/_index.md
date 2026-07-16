---
title: TransformFinalBlock()
second_title: Référence de l'API Aspose.Slides pour C++
description: Traite le dernier bloc de données et calcule le hachage.
type: docs
weight: 79
url: /fr/system.security.cryptography/hashalgorithm/transformfinalblock/
---
## HashAlgorithm::TransformFinalBlock(ArrayPtr\<uint8_t\>, int, int) méthode


Traite le dernier bloc de données et calcule le hachage.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::TransformFinalBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) pour lire les données depuis. |
| inputOffset | int | Décalage du tampon d'entrée. |
| inputCount | int | Nombre d'octets à traiter. |

### Valeur de retour

Hachage calculé pour l'ensemble de la séquence de données.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [HashAlgorithm](../)
* Espace de noms [System::Security::Cryptography](../../)
* Bibliothèque [Aspose.Slides](../../../)