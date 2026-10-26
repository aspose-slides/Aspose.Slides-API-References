---
title: Semaphore()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un semaforo senza nome.
type: docs
weight: 1
url: /it/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) costruttore

Crea un semaforo senza nome.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| initialCount | int | Conteggio iniziale delle voci attive. |
| maximumCount | int | Conteggio massimo delle voci consentite. |

## Semaphore::Semaphore(int, int, const String\&) costruttore

Crea un semaforo con nome.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| initialCount | int | Conteggio iniziale delle voci attive. |
| maximumCount | int | Conteggio massimo delle voci consentite. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nome. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) costruttore

Crea un semaforo con nome.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| initialCount | int | Conteggio iniziale delle voci attive. |
| maximumCount | int | Conteggio massimo delle voci consentite. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nome. |
| createdNew | **bool**\& | Riferimento a una variabile impostata su true se il semaforo è stato creato e su false se è stato riutilizzato uno esistente con lo stesso nome |

## Vedi anche

* Classe [Semaphore](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)