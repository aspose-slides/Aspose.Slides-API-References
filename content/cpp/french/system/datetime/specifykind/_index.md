---
title: SpecifyKind()
second_title: Référence API Aspose.Slides pour C++
description: Construit un nouvel objet DateTime qui représente le même nombre de ticks que l'objet DateTime spécifié et représente l'heure locale, l'heure UTC ou aucune des deux, selon l'argument kind.
type: docs
weight: 833
url: /fr/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) méthode

Construit un nouvel objet [DateTime](../) qui représente le même nombre de ticks que l'objet [DateTime](../) spécifié et représente l'heure locale, l'heure UTC ou aucune des deux, selon l'argument **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DateTime](../) | L'objet [DateTime](../) dont on copie le nombre de ticks |
| kind | [DateTimeKind](../../datetimekind/) | Spécifie si le nouvel objet doit représenter l'heure locale, l'heure UTC ou aucune des deux. |

### Valeur de retour

Un nouvel objet [DateTime](../) qui représente le même nombre de ticks que **value** et la valeur DateTimeKind spécifiée par **kind**.

## Voir aussi

* Enum [DateTimeKind](../../datetimekind/)
* Classe [DateTime](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)