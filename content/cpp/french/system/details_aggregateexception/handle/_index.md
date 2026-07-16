---
title: Handle()
second_title: Référence API Aspose.Slides pour C++
description: Invoque une fonction de gestionnaire sur chaque exception interne et relance les exceptions non traitées.
type: docs
weight: 66
url: /fr/system/details_aggregateexception/handle/
---
## Détails_AggregateException::Handle(const Func\<Exception, bool\>\&) méthode

Invoque une fonction de gestionnaire sur chaque exception interne et relance toute exception non prise en charge.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Une fonction qui prend une Exception et renvoie true si elle est prise en charge. |

## Remarques

Si toutes les exceptions sont traitées, la méthode se termine normalement ; sinon, une nouvelle AggregateException contenant les exceptions non traitées est levée.

## Voir aussi

* Typedef [Exception](../../exception/)
* Classe [Func](../../func/)
* Classe [Details_AggregateException](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)