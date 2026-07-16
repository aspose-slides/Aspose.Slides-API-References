---
title: operator-()
second_title: Référence API Aspose.Slides pour C++
description: Calcule le nombre de jours entre deux jours de la semaine.
type: docs
weight: 2146
url: /fr/system/operator_minus/
---
## System::operator-(DayOfWeek, DayOfWeek) fonction


Calcule le nombre de jours entre deux jours de la semaine.

```cpp
auto System::operator-(DayOfWeek a, DayOfWeek b)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| a | [DayOfWeek](../dayofweek/) | Le minuend |
| b | [DayOfWeek](../dayofweek/) | Le subtrahend |

### Valeur de retour

Le nombre de jours entre les jours de la semaine **a** et **b** ; la valeur de retour est un nombre négatif si *goes* after ****

## System::operator-(const T\&, const Decimal\&) fonction


Renvoie une nouvelle instance de la classe [Decimal](../decimal/) qui représente une valeur qui est le résultat de la soustraction de la valeur représentée par l'objet [Decimal](../decimal/) spécifié de la valeur spécifiée.

```cpp
template<typename T,typename _> Decimal System::operator-(const T &x, const Decimal &d)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | const T\& | La valeur à soustraire |
| d | const [Decimal](../decimal/)\& | L'objet [Decimal](../decimal/) représentant la valeur soustraite |

### Valeur de retour

Une nouvelle instance de la classe [Decimal](../decimal/) qui représente une valeur qui est le résultat de la soustraction de la valeur représentée par **d** de **x**.

## System::operator-(MulticastDelegate\<T\>, MulticastDelegate\<T\>) fonction


Déconnecte tous les rappels du délégué droit depuis la fin de la liste de rappels du délégué gauche.

```cpp
template<typename T> MulticastDelegate<T> System::operator-(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | Le délégué dont les rappels seront retirés. |
| rhv | MulticastDelegate\<T\> | Le délégué dont les rappels seront supprimés. |

### Valeur de retour

Renvoie un délégué qui contient les rappels de la valeur de gauche, mais sans ceux de la valeur de droite.

## System::operator-(const T1\&, const Nullable\<T2\>\&) fonction


Soustrait des valeurs non nullables et nullable.

```cpp
template<typename T1,typename T2,typename> auto System::operator-(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some - other.get_Value())>
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T1 | Type de l'opérande gauche. |
| T2 | Type de l'opérande droit. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| some | const T1\& | Opérande gauche. |
| other | const [Nullable](../nullable/)\<T2\>\& | Opérande droit. |

### Valeur de retour

Résultat de la soustraction.

## Voir aussi

* Énum [DayOfWeek](../dayofweek/)
* Classe [Decimal](../decimal/)
* Classe [Nullable](../nullable/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)