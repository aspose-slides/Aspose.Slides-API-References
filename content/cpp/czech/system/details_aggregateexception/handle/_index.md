---
title: Handle()
second_title: Aspose.Slides pro C++ API Reference
description: Vyvolá funkci obsluhy pro každou vnitřní výjimku a znovu vyhodí všechny neobsloužené výjimky.
type: docs
weight: 66
url: /cs/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) metoda


Vyvolá funkci obsluhy pro každou vnitřní výjimku a znovu vyhodí všechny neobsloužené výjimky.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```


### Parametry

| Parametr | Typ | Popis |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Funkce, která přijímá výjimku Exception a vrací true, pokud je obsloužena. |
## Poznámky



Pokud jsou všechny výjimky obslouženy, metoda se vrátí normálně; jinak je vyhozena nová výjimka AggregateException obsahující neobsloužené výjimky. 

## Viz také

* Typedef [Exception](../../exception/)
* Třída [Func](../../func/)
* Třída [Details_AggregateException](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)