---
title: WaitOne()
second_title: Référence de l'API Aspose.Slides pour C++
description: Verrouille le mutex. Effectue une attente illimitée si nécessaire.
type: docs
weight: 53
url: /fr/system.threading/mutex/waitone/
---
## Mutex::WaitOne() méthode

Locks mutex. Effectue une attente illimitée si nécessaire.

```cpp
virtual bool System::Threading::Mutex::WaitOne() override
```

### Valeur de retour

Renvoie toujours true car il ne retourne pas tant que le mutex n'est pas verrouillé.

## Mutex::WaitOne(int) méthode

Locks mutex. Effectue une attente si nécessaire.

```cpp
virtual bool System::Threading::Mutex::WaitOne(int millisecondsTimeout) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Délai d'attente en millisecondes. |

### Valeur de retour

Renvoie true si le mutex a été verrouillé ou false si le délai d'attente est dépassé.

## Mutex::WaitOne(TimeSpan) méthode

Locks mutex. Effectue une attente si nécessaire.

```cpp
virtual bool System::Threading::Mutex::WaitOne(TimeSpan timeout) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [System::TimeSpan](../../../system/timespan/) qui représente le nombre de millisecondes à attendre, ou un [System::TimeSpan](../../../system/timespan/) qui représente -1 millisecondes pour une attente indéfinie. |

### Valeur de retour

Renvoie true si le mutex a été verrouillé ou false si le délai d'attente est dépassé.

## Voir aussi

* Classe [Mutex](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)