---
title: WaitOne()
second_title: Aspose.Slides för C++ API-referens
description: Låser semafor. Utför obegränsad väntan om nödvändigt.
type: docs
weight: 40
url: /sv/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() metod


Låser semafor. Utför obegränsad väntan om nödvändigt.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Returvärde

Returnerar alltid true eftersom den inte återgår förrän semaforen är låst.

## Semaphore::WaitOne(int) metod


Låser semafor. Utför väntan om nödvändigt.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsTimeout | int | Väntetidsgräns i millisekunder. |

### Returvärde

Returnerar true om semaforen var låst eller false om tidsgränsen överskreds.

## Se även

* Klass [Semaphore](../)
* Namnrymd [System::Threading](../../)
* Library [Aspose.Slides](../../../)