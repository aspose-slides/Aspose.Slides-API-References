---
title: operator-()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une nouvelle instance de la classe DateTime représentant la valeur de date et d'heure qui est le résultat de la soustraction de l'intervalle de temps spécifié de la valeur représentée par l'objet actuel.
type: docs
weight: 651
url: /fr/system/datetime/operator_minus/
---
## DateTime::operator-(TimeSpan) const méthode


Renvoie une nouvelle instance de la classe [DateTime](../) représentant la valeur de date et d'heure qui est le résultat de la soustraction de l'intervalle de temps spécifié de la valeur représentée par l'objet actuel.

```cpp
DateTime System::DateTime::operator-(TimeSpan value) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TimeSpan](../../timespan/) | Un intervalle de temps à soustraire |

### Valeur de retour

Une nouvelle instance de la classe [DateTime](../) représentant la valeur de date et d'heure qui est le résultat de la soustraction de **value** de la valeur représentée par l'objet actuel.

## DateTime::operator-(DateTime) const méthode


Renvoie une instance de la classe [TimeSpan](../../timespan/) qui représente l'intervalle de temps entre les valeurs de date et d'heure représentées par l'objet actuel et l'objet spécifié.

```cpp
constexpr TimeSpan System::DateTime::operator-(DateTime value) const
```


### Arguments

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