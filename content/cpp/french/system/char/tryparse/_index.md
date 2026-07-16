---
title: TryParse()
second_title: Référence API Aspose.Slides pour C++
description: Tente de convertir une chaîne composée d'un seul caractère en caractère UTF-16. La fonction ne réussit que lorsque la chaîne d'entrée n'est pas nulle et a une longueur d'exactement un caractère.
type: docs
weight: 300
url: /fr/system/char/tryparse/
---
## Char::TryParse(const System::String\&, char_t\&) méthode

Tente de convertir une chaîne contenant un seul caractère en caractère UTF-16. La fonction réussit uniquement lorsque la chaîne d'entrée n'est pas null et a une longueur d'exactement un caractère.

```cpp
static bool System::Char::TryParse(const System::String &s, char_t &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [System::String](../../string/)\& | [String](../../string/) à convertir |
| result | char_t\& | La variable de sortie qui contiendra le résultat de la conversion si la conversion réussit |

### Valeur de retour

True si la conversion a réussi, sinon - false

## Voir aussi

* Classe [String](../../string/)
* Classe [Char](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)