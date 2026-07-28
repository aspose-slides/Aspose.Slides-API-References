---
title: CancellationToken
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Rozgłasza powiadomienie, że operacje powinny zostać anulowane. Ta klasa zapewnia mechanizm kooperacyjnego anulowania między wątkami, umożliwiając jednemu wątkowi powiadomienie innych, że operacja powinna zostać anulowana.
type: docs
weight: 14
url: /pl/system.threading/cancellationtoken/
---
## CancellationToken klasa

Rozgłasza powiadomienie, że operacje powinny zostać anulowane. Ta klasa zapewnia mechanizm kooperacyjnego anulowania między wątkami, umożliwiając jednemu wątkowi powiadomienie innych, że operacja powinna zostać anulowana.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Opis |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Domyślny konstruktor. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Zwraca, czy ten token może znajdować się w stanie anulowanym. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Zwraca, czy dla tego tokena zażądano anulowania. |
| static [CancellationToken](./) [get_None](./get_none/)() | Zwraca pustą wartość [System::Threading::CancellationToken](./). |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Rejestruje wywołanie zwrotne, które zostanie wywołane, gdy zostanie zażądane anulowanie. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Rzuca wyjątek OperationCanceledException, jeśli anulowanie zostało zażądane. |

## Uwagi

Obiekt [CancellationToken](./) może zostać anulowany wyłącznie przez powiązany [CancellationTokenSource](../cancellationtokensource/).

## Zobacz także

* Przestrzeń nazw [System::Threading](../)
* Biblioteka [Aspose.Slides](../../)