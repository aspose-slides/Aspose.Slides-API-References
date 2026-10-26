---
title: Change()
second_title: Référence de l'API Aspose.Slides pour C++
description: Replanifie ou annule le minuteur.
type: docs
weight: 14
url: /fr/system.threading/timer/change/
---
## Timer::Change(int64_t, int64_t) méthode


Replanifie ou annule le minuteur.

```cpp
bool System::Threading::Timer::Change(int64_t dueTime, int64_t period)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dueTime | **int64_t** | [Timeout](../../timeout/) avant la prochaine invocation de la fonction de rappel, en millisecondes ; les valeurs négatives annulent le minuteur même s'il était programmé. |
| period | **int64_t** | [Timeout](../../timeout/) entre les invocations consécutives de la fonction de rappel, en millisecondes ; les valeurs non positives signifient que le minuteur ne doit être exécuté qu'une seule fois. |

## Timer::Change(System::TimeSpan, System::TimeSpan) méthode


Replanifie ou annule le minuteur.

```cpp
bool System::Threading::Timer::Change(System::TimeSpan dueTime, System::TimeSpan period)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) avant la prochaine invocation de la fonction de rappel ; les valeurs négatives annulent le minuteur même s'il était programmé. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) entre les invocations consécutives de la fonction de rappel ; les valeurs non positives signifient que le minuteur ne doit être exécuté qu'une seule fois. |

## Voir aussi

* Classe [Timer](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)