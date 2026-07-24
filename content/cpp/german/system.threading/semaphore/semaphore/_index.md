---
title: Semaphore()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein unbenanntes Semaphore.
type: docs
weight: 1
url: /de/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) Konstruktor

Erstellt ein unbenanntes Semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| initialCount | int | Initiale Anzahl aktiver Einträge. |
| maximumCount | int | Maximale zulässige Anzahl von Einträgen. |

## Semaphore::Semaphore(int, int, const String\&) Konstruktor

Erstellt ein benanntes Semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| initialCount | int | Initiale Anzahl aktiver Einträge. |
| maximumCount | int | Maximale zulässige Anzahl von Einträgen. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) Name. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) Konstruktor

Erstellt ein benanntes Semaphore.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| initialCount | int | Initiale Anzahl aktiver Einträge. |
| maximumCount | int | Maximale zulässige Anzahl von Einträgen. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) Name. |
| createdNew | **bool**\& | Referenz auf die Variable, die auf true gesetzt wird, wenn das Semaphore erstellt wurde, und auf false, wenn ein vorhandenes mit demselben Namen wiederverwendet wurde. |

## Siehe auch

* Klasse [Semaphore](../)
* Klasse [String](../../../system/string/)
* Namensraum [System::Threading](../../)
* Bibliothek [Aspose.Slides](../../../)