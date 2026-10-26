---
title: ToByteArray()
second_title: Aspose.Slides pour la référence API C++
description: Convertit une chaîne ou une sous-chaîne en tableau d'octets.
type: docs
weight: 508
url: /fr/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const méthode


Convertit une chaîne ou une sous-chaîne en un tableau d'octets.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| startIndex | **int32_t** | Indice de début de la sous-chaîne. |
| length | **int32_t** | Longueur de la sous-chaîne. |
| LE | **bool** | Si true, encode les caractères en little endianness ; sinon, utilise le big endianness. |

### Valeur de retour

[Array](../../array/) contenant des octets représentant les caractères de la chaîne.

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Classe [String](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)