---
title: operator-()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une nouvelle instance de la classe DateTimeOffset représentant la valeur de date et d'heure résultant de la soustraction de l'intervalle de temps spécifié de la valeur représentée par l'objet actuel.
type: docs
weight: 521
url: /fr/system/datetimeoffset/operator_minus/
---
## DateTimeOffset::operator-(TimeSpan) const méthode

Retourne une nouvelle instance de la classe [DateTimeOffset](../) représentant la valeur de date et d'heure qui résulte de la soustraction de l'intervalle de temps spécifié de la valeur représentée par l'objet actuel.

```cpp
DateTimeOffset System::DateTimeOffset::operator-(TimeSpan value) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Un intervalle de temps à soustraire |

### Valeur de retour

Une nouvelle instance de la classe [DateTimeOffset](../) représentant la valeur de date et d'heure qui est le résultat de la soustraction de **value** de la valeur représentée par l'objet actuel.

## DateTimeOffset::operator-(const DateTimeOffset\&) const méthode

Retourne une instance de la classe [TimeSpan](../../timespan/) qui représente l'intervalle de temps entre les valeurs de date et d'heure représentées par l'objet actuel et l'objet spécifié.

```cpp
TimeSpan System::DateTimeOffset::operator-(const DateTimeOffset &other) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| other | const [DateTimeOffset](../)\& | Une instance de la classe [DateTime](../../datetime/) qui marque une extrémité de l'intervalle à calculer |

### Valeur de retour

Une instance de la classe [TimeSpan](../../timespan/) représentant l'intervalle de temps entre les valeurs de date et d'heure représentées par l'objet actuel et **other**.

## Voir aussi

* Classe [DateTimeOffset](../)
* Classe [TimeSpan](../../timespan/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)