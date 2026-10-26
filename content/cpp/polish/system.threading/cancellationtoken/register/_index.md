---
title: Register()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Rejestruje wywołanie zwrotne, które zostanie wywołane, gdy żądane jest anulowanie.
type: docs
weight: 40
url: /pl/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const metoda

Rejestruje wywołanie zwrotne, które zostanie wywołane, gdy żądane jest anulowanie.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | Akcja<> do wykonania, gdy żądane jest anulowanie. |

### Wartość zwracana

Obiekt [CancellationTokenRegistration](../../cancellationtokenregistration/), który może być użyty do wyrejestrowania wywołania zwrotnego.

## Uwagi

Jeśli anulowanie zostało już zgłoszone, wywołanie zwrotne zostanie wywołane natychmiast.

Wywołanie zwrotne powinno być krótkotrwałe i nieblokujące, ponieważ będzie wykonywane w wątku, który wywołuje Cancel() na [CancellationTokenSource](../../cancellationtokensource/).

## Zobacz także

* Typedef [Action](../../../system/action/)
* Klasa [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Klasa [CancellationToken](../)
* Przestrzeń nazw [System::Threading](../../)
* Biblioteka [Aspose.Slides](../../../)