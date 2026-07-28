---
title: Semaphore()
second_title: Odwołanie API Aspose.Slides dla C++
description: Tworzy nienazwany semafor.
type: docs
weight: 1
url: /pl/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) konstruktor

Tworzy nienazwany semafor.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| initialCount | int | Początkowa liczba aktywnych wpisów. |
| maximumCount | int | Maksymalna liczba dozwolonych wpisów. |

## Semaphore::Semaphore(int, int, const String\&) konstruktor

Tworzy nazwany semafor.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| initialCount | int | Początkowa liczba aktywnych wpisów. |
| maximumCount | int | Maksymalna liczba dozwolonych wpisów. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nazwa. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) konstruktor

Tworzy nazwany semafor.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| initialCount | int | Początkowa liczba aktywnych wpisów. |
| maximumCount | int | Maksymalna liczba dozwolonych wpisów. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) nazwa. |
| createdNew | **bool**\& | Odniesienie do zmiennej, która jest ustawiana na true, jeśli semafor został utworzony, oraz na false, jeśli został użyty istniejący o tej samej nazwie |

## Zobacz także

* Klasa [Semaphore](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)