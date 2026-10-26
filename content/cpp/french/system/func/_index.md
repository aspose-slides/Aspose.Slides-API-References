---
title: Func
second_title: Référence de l'API Aspose.Slides pour C++
description: "Délegate de fonction. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 859
url: /fr/system/func/
---
## Func classe

Délegate de fonction. Ce type doit être alloué sur la pile et passé aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer les objets de ce type.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Args | Arguments d'appel, puis type de retour obligatoire. |

## Méthodes

| Méthode | Description |
| --- | --- |
|  [Func](./func/)() | Constructeur par défaut qui crée un null-Func. |
|  [Func](./func/)(T\&&) | Constructeur qui construit un objet [Func](./) et lui assigne une valeur (soit le rappel réel, soit nullptr) à celui-ci. |
|  [Func](./func/)(const [Func](./)\&) | Constructeur de copie. |
|  [Func](./func/)([Func](./)\&&) | Constructeur de déplacement. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | Assignation par copie. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | Assignation par déplacement. |
|  [~Func](./~func/)() | Destructeur. |

## Remarques

```cpp
#include "system/func.h"
#include <iostream>

// Cette fonction accepte une instance du délégué System::Func en tant que paramètre.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // Créez une instance du délégué System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // Passez l'instance créée en tant qu'argument de fonction.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
1
4
9
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)