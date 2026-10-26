---
title: FromException()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy zadanie, które zakończyło się określonym wyjątkiem.
type: docs
weight: 131
url: /pl/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) function

Tworzy zadanie, które zakończyło się określonym wyjątkiem.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Wyjątek, którym należy zakończyć zadanie. |

### Wartość zwracana

Zadanie zakończone niepowodzeniem.

## System::Threading::Tasks::FromException(const Exception\&) function

Tworzy zadanie, które zakończyło się określonym wyjątkiem i typem wyniku.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TResult | Typ wyniku zadania. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Wyjątek, którym należy zakończyć zadanie. |

### Wartość zwracana

Zadanie zakończone niepowodzeniem z określonym typem wyniku.

## Zobacz także

* Definicja typu [TaskPtr](../../system/taskptr/)
* Definicja typu [Exception](../../system/exception/)
* Definicja typu [RTaskPtr](../../system/rtaskptr/)
* Przestrzeń nazw [System::Threading::Tasks](../)
* Biblioteka [Aspose.Slides](../../)