---
title: Subtract()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie une nouvelle instance de la classe DateTime représentant la valeur de date et d'heure qui est le résultat de la soustraction de l'intervalle de temps spécifié de la valeur représentée par l'objet actuel.
type: docs
weight: 326
url: /fr/system/datetime/subtract/
---
## DateTime::Subtract(TimeSpan) const méthode

Renvoie une nouvelle instance de la classe [DateTime](../) représentant la valeur de date et d'heure qui est le résultat de la soustraction de l'intervalle de temps spécifié de la valeur représentée par l'objet actuel.

```cpp
DateTime System::DateTime::Subtract(TimeSpan duration) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| duration | [TimeSpan](../../timespan/) | Un intervalle de temps à soustraire |

### Valeur de retour

Une nouvelle instance de la classe [DateTime](../) représentant la valeur de date et d'heure qui est le résultat de la soustraction de **duration** de la valeur représentée par l'objet actuel.

## DateTime::Subtract(DateTime) const méthode

Renvoie une instance de la classe [TimeSpan](../../timespan/) représentant l'intervalle de temps entre les valeurs de date et d'heure représentées par l'objet actuel et l'objet spécifié.

```cpp
constexpr TimeSpan System::DateTime::Subtract(DateTime value) const
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [DateTime](../) | Une instance de la classe [DateTime](../) qui marque une extrémité de l'intervalle à calculer |

### Valeur de retour

Une instance de la classe [TimeSpan](../../timespan/) représentant l'intervalle de temps entre les valeurs de date et d'heure représentées par l'objet actuel et **value**.

## Voir aussi

* Classe [DateTime](../)
* Classe [TimeSpan](../../timespan/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)