---
title: CancellationTokenRegistration
second_title: Aspose.Slides pro C++ - reference API
description: Představuje registraci pro zpětné volání tokenu zrušení.
type: docs
weight: 27
url: /cs/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration třída

Představuje registraci pro zpětné volání tokenu zrušení.

```cpp
class CancellationTokenRegistration
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Dispose](./dispose/)() | Zruší registraci a odstraní zpětné volání z přidruženého [CancellationTokenSource](../cancellationtokensource/). Po zavolání této metody již nebude registrované zpětné volání vyvoláno, když je přidružený [CancellationTokenSource](../cancellationtokensource/) zrušen. |
## Poznámky

Tato třída umožňuje odregistrování zpětného volání z tokenu zrušení. Při zrušení odstraní zpětné volání z přidruženého [CancellationTokenSource](../cancellationtokensource/). Tuto třídu by nemělo být vytvářeno přímo – je vrácena metodami registrace [CancellationToken](../cancellationtoken/). 

## Viz také

* Jmenný prostor [System::Threading](../)
* Knihovna [Aspose.Slides](../../)