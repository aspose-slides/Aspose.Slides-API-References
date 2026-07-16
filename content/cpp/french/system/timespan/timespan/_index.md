---
title: TimeSpan()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit un objet TimeSpan qui représente un intervalle de temps nul.
type: docs
weight: 1
url: /fr/system/timespan/timespan/
---
## TimeSpan::TimeSpan() constructeur


Construit un objet [TimeSpan](../) qui représente un intervalle de temps nul.

```cpp
constexpr System::TimeSpan::TimeSpan()
```

## TimeSpan::TimeSpan(int64_t) constructeur


Construit une instance de la classe [TimeSpan](../) qui représente l'intervalle de temps spécifié.

```cpp
constexpr System::TimeSpan::TimeSpan(int64_t ticks)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| ticks | **int64_t** | L'intervalle de temps à représenter par l'instance en cours de construction, exprimé comme le nombre d'intervalles de 100 nanosecondes. |

## TimeSpan::TimeSpan(int, int, int) constructeur


Construit une instance de la classe [TimeSpan](../) qui représente l'intervalle de temps égal à la somme du nombre spécifié d'heures, de minutes et de secondes.

```cpp
System::TimeSpan::TimeSpan(int hours, int minutes, int seconds)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hours | int | Le nombre d'heures dans la composante heures de l'intervalle de temps à représenter par l'instance en cours de construction |
| minutes | int | Le nombre de minutes dans la composante minutes de l'intervalle de temps à représenter par l'instance en cours de construction |
| seconds | int | Le nombre de secondes dans la composante secondes de l'intervalle de temps à représenter par l'instance en cours de construction |

## TimeSpan::TimeSpan(int, int, int, int, int) constructeur


Construit une instance de la classe [TimeSpan](../) qui représente l'intervalle de temps égal à la somme du nombre spécifié d'heures, de minutes, de secondes et de millisecondes.

```cpp
System::TimeSpan::TimeSpan(int days, int hours, int minutes, int seconds, int milliseconds=0)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| days | int | Le nombre de jours dans la composante jours de l'intervalle de temps à représenter par l'instance en cours de construction |
| hours | int | Le nombre d'heures dans la composante heures de l'intervalle de temps à représenter par l'instance en cours de construction |
| minutes | int | Le nombre de minutes dans la composante minutes de l'intervalle de temps à représenter par l'instance en cours de construction |
| seconds | int | Le nombre de secondes dans la composante secondes de l'intervalle de temps à représenter par l'instance en cours de construction |
| milliseconds | int | Le nombre de millisecondes dans la composante millisecondes de l'intervalle de temps à représenter par l'instance en cours de construction |

## TimeSpan::TimeSpan(const TimeSpan\&) constructeur


Construit un objet [TimeSpan](../) qui représente l'intervalle de temps égal à l'intervalle de temps représenté par l'objet [TimeSpan](../) spécifié.

```cpp
constexpr System::TimeSpan::TimeSpan(const TimeSpan &)=default
```

## Voir aussi

* Classe [TimeSpan](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)