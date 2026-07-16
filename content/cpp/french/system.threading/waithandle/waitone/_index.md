---
title: WaitOne()
second_title: Référence API Aspose.Slides pour C++
description: Attend que le handle se déclenche pendant une période illimitée.
type: docs
weight: 27
url: /fr/system.threading/waithandle/waitone/
---
## WaitHandle::WaitOne() méthode

Attend que le handle se déclenche pour une période illimitée.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne()
```

### Valeur de retour

Always returns true as no timeout occurs.

## WaitHandle::WaitOne(int) méthode

Attend que le handle se déclenche.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) d'attente, en millisecondes ; -1 signifie attente infinie, 0 signifie vérification et retour, les valeurs positives sont des délais d'attente. |

### Valeur de retour

True if handle fired, false if timeout exceeded.

## WaitHandle::WaitOne(TimeSpan) méthode

Attend que le handle se déclenche.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(TimeSpan timeout)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) qui représente le nombre de millisecondes à attendre, ou un [System::TimeSpan](../../../system/timespan/) qui représente -1 millisecondes pour attendre indéfiniment. |

### Valeur de retour

True if handle fired, false if timeout exceeded.

## WaitHandle::WaitOne(int, bool) méthode

Attend que le handle se déclenche.

```cpp
virtual bool System::Threading::WaitHandle::WaitOne(int millisecondsTimeout, bool exitContext)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | [Timeout](../../timeout/) d'attente, en millisecondes ; -1 signifie attente infinie, 0 signifie vérification et retour, les valeurs positives sont des délais d'attente. |
| exitContext | **bool** | Si true, l'attente doit libérer le verrou sur le handle avant d'attendre. |

### Valeur de retour

True if handle fired, false if timeout exceeded.

## Voir aussi

* Classe [WaitHandle](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)