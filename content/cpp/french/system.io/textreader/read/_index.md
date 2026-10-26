---
title: Read()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit un seul caractère du flux.
type: docs
weight: 40
url: /fr/system.io/textreader/read/
---
## TextReader::Read() méthode

Lit un seul caractère du flux.

```cpp
virtual int System::IO::TextReader::Read()
```

### Valeur de retour

Caractère lu encodé en UTF-16 ; si le caractère lu est représenté par deux points de code en encodage UTF-16, alors seul le surrogat haut est renvoyé.

## TextReader::Read(ArrayPtr\<char_t\>, int, int) méthode

Lit le nombre spécifié de caractères du flux et les écrit dans le tableau de caractères spécifié en commençant à la position spécifiée.

```cpp
virtual int System::IO::TextReader::Read(ArrayPtr<char_t> buffer, int index, int count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Le tableau de caractères UTF-16 dans lequel écrire les caractères lus du flux |
| index | int | Un indice basé à 0 dans **buffer** à partir duquel commencer l’écriture |
| count | int | Le nombre de caractères à lire du flux |

### Valeur de retour

Le nombre de caractères lus du flux

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [TextReader](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)