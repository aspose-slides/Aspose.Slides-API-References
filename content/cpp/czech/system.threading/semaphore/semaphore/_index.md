---
title: Semaphore()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří nepojmenovaný semafor.
type: docs
weight: 1
url: /cs/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) konstruktor

Vytvoří nepojmenovaný semafor.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| initialCount | int | Počáteční počet aktivních položek. |
| maximumCount | int | Maximální povolený počet položek. |

## Semaphore::Semaphore(int, int, const String\&) konstruktor

Vytvoří pojmenovaný semafor.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| initialCount | int | Počáteční počet aktivních položek. |
| maximumCount | int | Maximální povolený počet položek. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) název. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) konstruktor

Vytvoří pojmenovaný semafor.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| initialCount | int | Počáteční počet aktivních položek. |
| maximumCount | int | Maximální povolený počet položek. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) název. |
| createdNew | **bool**\& | Reference na proměnnou, která je nastavena na true, pokud byl semafor vytvořen, a na false, pokud byl znovu použit existující se stejným názvem |

## Viz také

* Třída [Semaphore](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)