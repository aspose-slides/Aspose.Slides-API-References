---
title: FromException()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří úlohu, která byla dokončena s určenou výjimkou.
type: docs
weight: 131
url: /cs/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) funkce

Vytvoří úlohu, která byla dokončena s určenou výjimkou.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Výjimka, kterou má úloha dokončit. |

### Návratová hodnota

Úloha s chybou.

## System::Threading::Tasks::FromException(const Exception\&) funkce

Vytvoří úlohu, která byla dokončena s určenou výjimkou a typem výsledku.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| TResult | Typ výsledku úlohy. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | Výjimka, kterou má úloha dokončit. |

### Návratová hodnota

Úloha s chybou a určeným typem výsledku.

## Viz také

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)