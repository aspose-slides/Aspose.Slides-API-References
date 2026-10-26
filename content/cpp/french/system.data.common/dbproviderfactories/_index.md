---
title: DbProviderFactories
second_title: Référence de l'API Aspose.Slides pour C++
description: "API pour obtenir les factories de fournisseurs de bases de données. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction System::MakeObject(). Ne créez jamais d’instance de ce type sur la pile ou avec l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des fautes d’assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le transmettre aux fonctions en tant qu’argument."
type: docs
weight: 53
url: /fr/system.data.common/dbproviderfactories/
---
## DbProviderFactories classe

API pour obtenir les factories de fournisseurs de bases de données. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou avec l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des fautes d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu’argument.

```cpp
class DbProviderFactories
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[DbProviderFactory](../dbproviderfactory/)\> [GetFactory](./getfactory/)(const [String](../../system/string/)\&) | Obtient la factory du fournisseur de DB par nom. |

## Voir aussi

* Espace de noms [System::Data::Common](../)
* Library [Aspose.Slides](../../)