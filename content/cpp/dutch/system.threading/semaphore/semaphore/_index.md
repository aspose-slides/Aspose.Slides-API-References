---
title: Semaphore()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een niet-genaamde semaphore aan.
type: docs
weight: 1
url: /nl/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) constructor


Maakt een niet-genaamde semaphore aan.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| initialCount | int | Initiële telling van actieve items. |
| maximumCount | int | Maximum toegestaan aantal items. |

## Semaphore::Semaphore(int, int, const String\&) constructor


Maakt een benoemde semaphore aan.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| initialCount | int | Initiële telling van actieve items. |
| maximumCount | int | Maximum toegestaan aantal items. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) naam. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) constructor


Maakt een benoemde semaphore aan.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| initialCount | int | Initiële telling van actieve items. |
| maximumCount | int | Maximum toegestaan aantal items. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) naam. |
| createdNew | **bool**\& | Referentie naar een variabele die true wordt ingesteld als de semaphore is gemaakt en false als een bestaande met dezelfde naam is hergebruikt |

## Zie ook

* Klasse [Semaphore](../)
* Klasse [String](../../../system/string/)
* Namespace [System::Threading](../../)
* Bibliotheek [Aspose.Slides](../../../)