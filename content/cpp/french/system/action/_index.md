---
title: Action
second_title: Référence API Aspose.Slides pour C++
description: Type de délégué qui référence des méthodes qui n'ont pas de valeur de retour.
type: docs
weight: 3563
url: /fr/system/action/
---
## Typedef d'action


Type de délégué qui référence des méthodes qui n'ont pas de valeur de retour.

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## Remarques



```cpp
#include <system/action.h>

using namespace System;

// La fonction qui affiche la chaîne passée.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // Créer une instance de Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // Appeler l'action.
  action(u"Hello, world!");

  return 0;
}
/*
Cet exemple de code produit la sortie suivante :
Hello, world!
*/
```

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)