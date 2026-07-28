---
title: Semaphore()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy névtelen szemafort.
type: docs
weight: 1
url: /hu/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) konstruktor


Létrehoz egy névtelen Semaphore-t.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| initialCount | int | Az aktív bejegyzések kezdeti száma. |
| maximumCount | int | A maximálisan megengedett bejegyzések száma. |

## Semaphore::Semaphore(int, int, const String\&) konstruktor


Létrehoz egy névvel rendelkező Semaphore-t.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| initialCount | int | Az aktív bejegyzések kezdeti száma. |
| maximumCount | int | A maximálisan megengedett bejegyzések száma. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) név. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) konstruktor


Létrehoz egy névvel rendelkező Semaphore-t.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| initialCount | int | Az aktív bejegyzések kezdeti száma. |
| maximumCount | int | A maximálisan megengedett bejegyzések száma. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) név. |
| createdNew | **bool**\& | Referenciát tartalmazó változó, amely true értékre lesz állítva, ha a Semaphore létre lett hozva, és false értékre, ha ugyanazzal a névvel már létező Semaphore-t használták újra |

## Lásd még

* Osztály [Semaphore](../)
* Osztály [String](../../../system/string/)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)