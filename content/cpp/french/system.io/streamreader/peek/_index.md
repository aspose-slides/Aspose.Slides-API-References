---
title: Peek()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit un seul caractère du flux sans modifier le curseur de lecture du flux.
type: docs
weight: 27
url: /fr/system.io/streamreader/peek/
---
## StreamReader::Peek() méthode

Lit un seul caractère du flux sans modifier le curseur de lecture du flux.

```cpp
virtual int System::IO::StreamReader::Peek() override
```

### Valeur de retour

Caractère lu encodé en UTF-16 ; si le caractère lu est représenté par deux points de code en encodage UTF-16, alors seul le surrogat haut est renvoyé ; si aucun caractère n’a été lu, -1 est renvoyé

## Voir aussi

* Classe [StreamReader](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)