---
title: PeekChar()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit un seul caractère du flux d'entrée sans modifier le curseur de lecture du flux.
type: docs
weight: 53
url: /fr/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() méthode

Lit un seul caractère du flux d'entrée sans modifier le curseur de lecture du flux.

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### Valeur de retour

Caractère lu encodé en UTF-16 ; si le caractère lu est représenté par deux points de code en encodage UTF-16, alors seul le surrogate haut est retourné ; si aucun caractère n'a été lu, -1 est retourné

## Voir aussi

* Classe [BinaryReader](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)