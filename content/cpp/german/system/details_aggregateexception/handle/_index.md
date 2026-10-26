---
title: Handle()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft für jede innere Ausnahme eine Handler-Funktion auf und wirft nicht behandelte Ausnahmen erneut.
type: docs
weight: 66
url: /de/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) Methode

Ruft für jede innere Ausnahme eine Handler-Funktion auf und wirft nicht behandelte Ausnahmen erneut.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Eine Funktion, die eine Exception entgegennimmt und true zurückgibt, wenn sie behandelt wird. |

## Hinweise

Wenn alle Ausnahmen behandelt werden, gibt die Methode normal zurück; andernfalls wird eine neue AggregateException, die die nicht behandelten Ausnahmen enthält, geworfen. 

## Siehe auch

* Typedef [Exception](../../exception/)
* Klasse [Func](../../func/)
* Klasse [Details_AggregateException](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)