---
title: Predicate
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un pointeur vers un prédicat - une entité invoquable qui accepte un seul argument et renvoie une valeur bool.
type: docs
weight: 4148
url: /fr/system/predicate/
---
## Predicate typedef


Représente un pointeur vers un prédicat - une entité invoquable qui accepte un seul argument et renvoie une valeur bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## Remarques



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // Remplir le tableau.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // Créer le prédicat qui renvoie un élément du tableau supérieur à 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // Trouver le premier élément du tableau en utilisant le prédicat créé et l'afficher.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
5
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)