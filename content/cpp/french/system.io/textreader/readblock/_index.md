---
title: ReadBlock()
second_title: Aspose.Slides for C++ Référence de l'API
description: Lit le nombre maximum spécifié de caractères depuis le lecteur de texte actuel et écrit les données dans un tampon, en commençant à l'index spécifié.
type: docs
weight: 53
url: /fr/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) méthode

Lit le nombre maximum spécifié de caractères depuis le lecteur de texte actuel et écrit les données dans un tampon, en commençant à l'index spécifié.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Un tampon de caractères dans lequel écrire les données lues |
| index | int | Un indice basé à 0 dans **buffer** où commencer l'écriture |
| count | int | Le nombre maximum de caractères à lire |

### Valeur de retour

Le nombre réel de caractères lus

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [TextReader](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)