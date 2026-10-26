---
title: CancellationToken
second_title: Aspose.Slides pro C++ API Reference
description: Propaguje oznámení, že operace by měly být zrušeny. Třída poskytuje mechanismus pro kooperativní zrušení mezi vlákny, umožňující jednomu vláknu informovat ostatní, že operace by měla být zrušena.
type: docs
weight: 14
url: /cs/system.threading/cancellationtoken/
---
## CancellationToken třída

Propaguje oznámení, že operace by měly být zrušeny. Tato třída poskytuje mechanismus pro kooperativní zrušení mezi vlákny, umožňující jednomu vláknu informovat ostatní, že operace by měla být zrušena.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Výchozí konstruktor. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Získá, zda je tento token schopen být ve zrušeném stavu. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Získá, zda bylo pro tento token požadováno zrušení. |
| static [CancellationToken](./) [get_None](./get_none/)() | Vrátí prázdnou [System::Threading::CancellationToken](./) hodnotu. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Zaregistruje zpětné volání, které bude vyvoláno, když bude požadováno zrušení. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Vyhodí OperationCanceledException, pokud bylo požadováno zrušení. |

## Poznámky

[CancellationToken](./) lze zrušit pouze prostřednictvím jeho souvisejícího [CancellationTokenSource](../cancellationtokensource/).

## Viz také

* Jmenný prostor [System::Threading](../)
* Knihovna [Aspose.Slides](../../)