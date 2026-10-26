---
title: Read()
second_title: Référence API Aspose.Slides pour C++
description: Lit un seul caractère depuis le flux.
type: docs
weight: 40
url: /fr/system.io/streamreader/read/
---
## StreamReader::Read() méthode


Lit un seul caractère depuis le flux.

```cpp
virtual int System::IO::StreamReader::Read() override
```


### Valeur de retour

Caractère lu encodé en UTF-16 ; si le caractère lu est représenté par deux points de code en encodage UTF-16, alors seule la surrogat haute est renvoyée.

## StreamReader::Read(ArrayPtr\<char_t\>, int, int) méthode


Lit le nombre spécifié de caractères depuis le flux, les convertit en encodage UTF-16 et écrit les caractères UTF-16 résultants dans le tableau de caractères spécifié à partir de la position indiquée.

```cpp
virtual int System::IO::StreamReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Le tableau de caractères UTF-16 dans lequel écrire les caractères lus depuis le flux |
| index | int | Un indice basé sur 0 dans **buffer** à partir duquel commencer l'écriture |
| count | int | Le nombre de caractères à lire depuis le flux |

### Valeur de retour

Le nombre de caractères lus depuis le flux

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StreamReader](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)