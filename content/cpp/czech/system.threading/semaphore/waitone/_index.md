---
title: WaitOne()
second_title: Aspose.Slides pro C++ API Reference
description: Zamkne semafor. Provádí neomezené čekání, pokud je to nutné.
type: docs
weight: 40
url: /cs/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() metoda


Zamkne semafor. Provádí neomezené čekání, pokud je to nutné.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```


### Návratová hodnota

Vždy vrací true, protože se nevrátí, dokud není semafor zamčen.

## Semaphore::WaitOne(int) metoda


Zamkne semafor. Provádí čekání, pokud je to nutné.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| millisecondsTimeout | int | Čekací časový limit v milisekundách. |

### Návratová hodnota

Vrátí true, pokud byl semafor zamčen, nebo false, pokud byl překročen časový limit.

## Viz také

* Třída [Semaphore](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)