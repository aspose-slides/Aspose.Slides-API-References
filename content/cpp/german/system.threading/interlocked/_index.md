---
title: Interlocked
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine API für thread-sichere Operationen bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.
type: docs
weight: 131
url: /de/system.threading/interlocked/
---
## Interlocked Klasse

Stellt eine API für thread-sichere Operationen bereit. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erstellen.

```cpp
class Interlocked
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Erhöht den Wert atomar. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Erhöht den Wert atomar. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Vergleicht-und tauscht den Wert einer Variablen aus: prüft, ob die Variable einem bestimmten Wert entspricht und speichert den neuen Wert nur, wenn der gespeicherte Wert dem erwarteten entspricht. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Vergleicht-und tauscht den Wert einer Variablen aus: prüft, ob die Variable einem bestimmten Wert entspricht und speichert den neuen Wert nur, wenn der gespeicherte Wert dem erwarteten entspricht. Nicht implementiert. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Vergleicht-und tauscht den Wert einer Variablen aus: prüft, ob die Variable einem bestimmten Wert entspricht und speichert den neuen Wert nur, wenn der gespeicherte Wert dem erwarteten entspricht. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Dekrementiert den Wert atomar. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Dekrementiert den Wert atomar. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Tauscht den Wert einer Variablen aus: speichert den neuen Wert und gibt den Wert zurück, den die Variable unmittelbar vor dem Speichern hatte. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Tauscht den Wert einer Variablen aus: speichert den neuen Wert und gibt den Wert zurück, den die Variable unmittelbar vor dem Speichern hatte. Nicht implementiert. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Erhöht den Wert atomar mittels Austausch-Add-Verfahren. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Erhöht den Wert atomar mittels Austausch-Add-Verfahren. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Inkrementiert den Wert atomar. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Inkrementiert den Wert atomar. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Gibt einen 64-Bit-Wert zurück, der als atomare Operation geladen wurde. |

## Siehe auch

* Namensraum [System::Threading](../)
* Bibliothek [Aspose.Slides](../../)