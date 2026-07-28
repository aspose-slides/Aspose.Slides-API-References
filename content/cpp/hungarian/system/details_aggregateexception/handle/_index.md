---
title: Handle()
second_title: Aspose.Slides for C++ API-referencia
description: Minden belső kivételen meghív egy kezelő függvényt, és újra dobja a nem kezelt kivételeket.
type: docs
weight: 66
url: /hu/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) metódus


Minden belső kivételen meghív egy kezelő függvényt, és újra dobja a nem kezelt kivételeket.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Egy függvény, amely egy Exception-t kap, és igazat ad vissza, ha az kezelve van. |
## Megjegyzések



Ha az összes kivétel kezelve van, a metódus normál módon visszatér; ellenkező esetben egy új AggregateException kerül dobásra, amely a nem kezelt kivételeket tartalmazza. 

## Lásd még

* Typedef [Exception](../../exception/)
* Osztály [Func](../../func/)
* Osztály [Details_AggregateException](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)