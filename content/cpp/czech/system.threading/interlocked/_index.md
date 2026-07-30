---
title: Interlocked
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje rozhraní API pro operace bezpečné pro vlákna. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem.
type: docs
weight: 131
url: /cs/system.threading/interlocked/
---
## Interlocked třída

Poskytuje rozhraní API pro operace bezpečné pro vlákna. Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem.

```cpp
class Interlocked
```

## Metody

| Metoda | Popis |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Zvyšuje hodnotu atomicky. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Zvyšuje hodnotu atomicky. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Porovná a vymění hodnotu v proměnné: kontroluje, zda je proměnná rovna konkrétní hodnotě, a uloží novou hodnotu pouze pokud se uložená hodnota shoduje s očekávanou. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Porovná a vymění hodnotu v proměnné: kontroluje, zda je proměnná rovna konkrétní hodnotě, a uloží novou hodnotu pouze pokud se uložená hodnota shoduje s očekávanou. Není implementováno. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Porovná a vymění hodnotu v proměnné: kontroluje, zda je proměnná rovna konkrétní hodnotě, a uloží novou hodnotu pouze pokud se uložená hodnota shoduje s očekávanou. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Snižuje hodnotu atomicky. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Snižuje hodnotu atomicky. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Vymění hodnotu v proměnné: uloží novou hodnotu a vrátí hodnotu, kterou proměnná měla okamžitě před uložením. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Vymění hodnotu v proměnné: uloží novou hodnotu a vrátí hodnotu, kterou proměnná měla okamžitě před uložením. Není implementováno. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Zvyšuje hodnotu atomicky pomocí procedury exchange-add. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Zvyšuje hodnotu atomicky pomocí procedury exchange-add. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Zvyšuje hodnotu atomicky. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Zvyšuje hodnotu atomicky. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Vrací 64-bitovou hodnotu načtenou jako atomická operace. |

## Viz také

* Jmenný prostor [System::Threading](../)
* Knihovna [Aspose.Slides](../../)