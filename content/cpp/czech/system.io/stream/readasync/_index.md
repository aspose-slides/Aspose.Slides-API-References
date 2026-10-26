---
title: ReadAsync()
second_title: Aspose.Slides – referenční příručka API pro C++
description: Asynchronně načte sekvenci bajtů ze současného proudu, posune pozici v proudu o počet načtených bajtů a monitoruje žádosti o zrušení.
type: docs
weight: 40
url: /cs/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Asynchronně načte sekvenci bajtů ze současného proudu, posune pozici v proudu o počet načtených bajtů a monitoruje žádosti o zrušení.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíšou načtené bajty. |
| offset | **int32_t** | Pozice v **buffer** počínající od nuly, kde začít zapisovat. |
| count | **int32_t** | Počet bajtů k načtení. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token, který se používá k monitorování žádostí o zrušení. |

### Návratová hodnota

Úloha, která představuje asynchronní operaci čtení. Hodnota parametru TResult obsahuje celkový počet bajtů načtených do bufferu. Výsledná hodnota může být menší než požadovaný počet bajtů, pokud je aktuálně dostupných bajtů méně než požadovaný počet, nebo může být 0 (nula), pokud byl dosažen konec proudu.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Asynchronně načte sekvenci bajtů ze současného proudu, posune pozici v proudu o počet načtených bajtů a monitoruje žádosti o zrušení.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíšou načtené bajty. |
| offset | **int32_t** | Pozice v **buffer** počínající od nuly, kde začít zapisovat. |
| count | **int32_t** | Počet bajtů k načtení. |

### Návratová hodnota

Úloha, která představuje asynchronní operaci čtení. Hodnota parametru TResult obsahuje celkový počet bajtů načtených do bufferu. Výsledná hodnota může být menší než požadovaný počet bajtů, pokud je aktuálně dostupných bajtů méně než požadovaný počet, nebo může být 0 (nula), pokud byl dosažen konec proudu.

## Viz také

* Definice typu [RTaskPtr](../../../system/rtaskptr/)
* Definice typu [ArrayPtr](../../../system/arrayptr/)
* Třída [CancellationToken](../../../system.threading/cancellationtoken/)
* Třída [Stream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)