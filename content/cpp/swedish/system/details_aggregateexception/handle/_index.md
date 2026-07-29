---
title: Handle()
second_title: Aspose.Slides för C++ API-referens
description: Anropar en hanteringsfunktion för varje inre undantag och kastar om eventuella ohanterade undantag.
type: docs
weight: 66
url: /sv/system/details_aggregateexception/handle/
---
## Detaljer_AggregateException::Handle(const Func\<Exception, bool\>\&) method

Anropar en hanteringsfunktion för varje inre undantag och kastar om eventuella ohanterade undantag.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | En funktion som tar ett Exception och returnerar true om det hanteras. |
## Anmärkningar

Om alla undantag hanteras, returnerar metoden normalt; annars kastas ett nytt AggregateException som innehåller de ohanterade undantagen. 

## Se även

* Typdefinition [Exception](../../exception/)
* Klass [Func](../../func/)
* Klass [Details_AggregateException](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)