---
title: FromException()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en task som har slutförts med ett specificerat undantag.
type: docs
weight: 131
url: /sv/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) function


Skapar en task som har slutförts med ett specificerat undantag.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Undantaget som används för att slutföra tasken. |

### Returvärde

En felaktig task.

## System::Threading::Tasks::FromException(const Exception\&) function


Skapar en task som har slutförts med ett specificerat undantag och resultattyp.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen av taskens resultat. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Undantaget som används för att slutföra tasken. |

### Returvärde

En felaktig task med den specificerade resultattypen.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)