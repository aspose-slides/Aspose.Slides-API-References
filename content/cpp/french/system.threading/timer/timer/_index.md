---
title: Timer()
second_title: Référence de l'API Aspose.Slides pour C++
description: Constructeur.
type: docs
weight: 1
url: /fr/system.threading/timer/timer/
---
## Timer::Timer(TimerCallback) constructeur

Constructeur.

```cpp
System::Threading::Timer::Timer(TimerCallback callback)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Fonction à appeler par le minuteur. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, int64_t, int64_t) constructeur

Constructeur.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, int64_t dueTime, int64_t period)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Fonction à appeler par le minuteur. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument de la fonction de rappel. |
| dueTime | **int64_t** | [Timeout](../../timeout/) avant la première invocation de la fonction de rappel, en millisecondes ; les valeurs négatives ne programment pas le minuteur après la création afin qu'il puisse être reprogrammé ultérieurement. |
| period | **int64_t** | [Timeout](../../timeout/) entre les invocations consécutives de la fonction de rappel, en millisecondes ; les valeurs non positives signifient que le minuteur ne doit être exécuté qu'une seule fois. |

## Timer::Timer(TimerCallback, const System::SharedPtr\<System::Object\>\&, System::TimeSpan, System::TimeSpan) constructeur

Constructeur.

```cpp
System::Threading::Timer::Timer(TimerCallback callback, const System::SharedPtr<System::Object> &state, System::TimeSpan dueTime, System::TimeSpan period)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| callback | [TimerCallback](../../timercallback/) | Fonction à appeler par le minuteur. |
| state | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Argument de la fonction de rappel. |
| dueTime | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) avant la première invocation de la fonction de rappel ; les valeurs négatives ne programment pas le minuteur après la création afin qu'il puisse être reprogrammé ultérieurement. |
| period | [System::TimeSpan](../../../system/timespan/) | [Timeout](../../timeout/) entre les invocations consécutives de la fonction de rappel ; les valeurs non positives signifient que le minuteur ne doit être exécuté qu'une seule fois. |

## Voir aussi

* Typedef [TimerCallback](../../timercallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Timer](../)
* Classe [Object](../../../system/object/)
* Classe [TimeSpan](../../../system/timespan/)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)