---
title: Boolean
second_title: Référence de l'API Aspose.Slides pour C++
description: Classe qui conserve les membres statiques du type System.Boolean .Net.
type: docs
weight: 79
url: /fr/system/boolean/
---
## Boolean classe


Classe qui conserve les membres statiques de [System.Boolean](./) .[Net](../../system.net/) type.

```cpp
class Boolean
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | Convertit la chaîne spécifiée en une valeur du type bool. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | Convertit la chaîne spécifiée en une valeur du type bool. |
## Champs

| Champ | Description |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) représentation de la valeur booléenne 'false'. |
| static [TrueString](./truestring/) | [String](../string/) représentation de la valeur booléenne 'true'. |
## Remarques



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // Crée la variable booléenne.
  bool isWeekend = false;

  // Analyse la chaîne d'entrée et affiche le résultat.
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
Is weekend: Yes
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)