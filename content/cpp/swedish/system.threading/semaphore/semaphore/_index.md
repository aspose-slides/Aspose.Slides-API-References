---
title: Semaphore()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en namnlös semaphore.
type: docs
weight: 1
url: /sv/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) konstruktor


Skapar en namnlös semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| initialCount | int | Initialt antal aktiva poster. |
| maximumCount | int | Maximalt tillåtet antal poster. |

## Semaphore::Semaphore(int, int, const String\&) konstruktor


Skapar en namngiven semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| initialCount | int | Initialt antal aktiva poster. |
| maximumCount | int | Maximalt tillåtet antal poster. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) namn. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) konstruktor


Skapar en namngiven semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| initialCount | int | Initialt antal aktiva poster. |
| maximumCount | int | Maximalt tillåtet antal poster. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) namn. |
| createdNew | **bool**\& | Referens till variabel som sätts till true om semaphore skapades och till false om en befintlig med samma namn återanvändes |

## Se även

* Klass [Semaphore](../)
* Klass [String](../../../system/string/)
* Namnrymd [System::Threading](../../)
* Bibliotek [Aspose.Slides](../../../)