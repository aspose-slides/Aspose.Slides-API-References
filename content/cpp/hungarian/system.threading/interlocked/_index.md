---
title: Interlocked
second_title: Aspose.Slides for C++ API Referenciája
description: API-t biztosít a szálbiztos műveletekhez. Ez egy statikus típus, amely nem rendelkezik példányszolgáltatásokkal. Soha ne hozzon létre példányokat belőle semmilyen módon.
type: docs
weight: 131
url: /hu/system.threading/interlocked/
---
## Interlocked osztály

Provides API for thread-safe operations. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Interlocked
```

## Metódusok

| Módszer | Leírás |
| --- | --- |
| static **int32_t** [Add](./add/)(**int32_t**\&, **int32_t**) | Növeli az értéket atomikusan. |
| static **int64_t** [Add](./add/)(**int64_t**\&, **int64_t**) | Növeli az értéket atomikusan. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Összehasonlítja és kicseréli a változó értékét: ellenőrzi, hogy a változó megegyezik-e a megadott értékkel, és csak akkor tárolja az új értéket, ha a tárolt érték megfelel a vártnak. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [CompareExchange](./compareexchange/)(T\&, T, T) | Összehasonlítja és kicseréli a változó értékét: ellenőrzi, hogy a változó megegyezik-e a megadott értékkel, és csak akkor tárolja az új értéket, ha a tárolt érték megfelel a vártnak. Nem implementált. |
| static **int32_t** [CompareExchange](./compareexchange/)(**int32_t**\&, **int32_t**, **int32_t**, **bool**\&) | Összehasonlítja és kicseréli a változó értékét: ellenőrzi, hogy a változó megegyezik-e a megadott értékkel, és csak akkor tárolja az új értéket, ha a tárolt érték megfelel a vártnak. |
| static **int32_t** [Decrement](./decrement/)(**int32_t**\&) | Csökkenti az értéket atomikusan. |
| static **int64_t** [Decrement](./decrement/)(**int64_t**\&) | Csökkenti az értéket atomikusan. |
| static std::enable_if\<IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Kicseréli a változó értékét: tárolja az új értéket, és visszaadja a változó korábban tárolt értékét a tárolás előtt. |
| static std::enable_if<\!IsSupportedInt\<T\>, T\>::type [Exchange](./exchange/)(T\&, T) | Kicseréli a változó értékét: tárolja az új értéket, és visszaadja a változó korábban tárolt értékét a tárolás előtt. Nem implementált. |
| static **int32_t** [ExchangeAdd](./exchangeadd/)(**int32_t**\&, **int32_t**) | Növeli az értéket atomikusan az exchange-add eljárás segítségével. |
| static **int64_t** [ExchangeAdd](./exchangeadd/)(**int64_t**\&, **int64_t**) | Növeli az értéket atomikusan az exchange-add eljárás segítségével. |
| static **int32_t** [Increment](./increment/)(**int32_t**\&) | Növeli az értéket atomikusan. |
| static **int64_t** [Increment](./increment/)(**int64_t**\&) | Növeli az értéket atomikusan. |
| static **int64_t** [Read](./read/)(**int64_t**\&) | Visszaad egy 64 bites értéket, amely atomikus műveletként van betöltve. |

## Lásd még

* Névtér [System::Threading](../)
* Könyvtár [Aspose.Slides](../../)