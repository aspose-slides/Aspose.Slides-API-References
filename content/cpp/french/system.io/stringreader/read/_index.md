---
title: Read()
second_title: Référence API Aspose.Slides pour C++
description: Lit un caractère unique du flux.
type: docs
weight: 40
url: /fr/system.io/stringreader/read/
---
## StringReader::Read() méthode

Lit un caractère unique du flux.

```cpp
virtual int System::IO::StringReader::Read() override
```

### Valeur de retour

Un caractère lu ou -1 si aucun caractère n’a été lu

## StringReader::Read(ArrayPtr\<char_t\>, int, int) méthode

Lit le nombre spécifié de caractères du flux dans le tableau de caractères spécifié en commençant à la position spécifiée.

```cpp
virtual int System::IO::StringReader::Read(ArrayPtr<char_t> buffer, int index, int count) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Le tableau de caractères dans lequel écrire les caractères lus du flux |
| index | int | Un indice basé à 0 dans **buffer** où commencer l'écriture |
| count | int | Le nombre de caractères à lire depuis le flux |

### Valeur de retour

Le nombre de caractères lus du flux

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [StringReader](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)