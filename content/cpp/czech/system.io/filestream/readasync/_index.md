---
title: ReadAsync()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Asynchronně načte sekvenci bajtů ze současného streamu, posune pozici ve streamu o počet načtených bajtů a sleduje požadavky na zrušení.
type: docs
weight: 196
url: /cs/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metoda

Asynchronně načte sekvenci bajtů z aktuálního streamu, posune pozici v streamu o počet načtených bajtů a monitoruje požadavky na zrušení.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, do kterého se zapíší načtené bajty. |
| offset | **int32_t** | Pozice založená na nule v **buffer**, od které se začne zapisovat. |
| count | **int32_t** | Počet bajtů k načtení. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token pro sledování požadavků na zrušení. |

### Návratová hodnota

Úloha, která představuje asynchronní operaci čtení. Hodnota parametru TResult obsahuje celkový počet bajtů načtených do bufferu. Hodnota výsledku může být menší než požadovaný počet bajtů, pokud je aktuálně dostupných bajtů méně, než bylo požadováno, nebo může být 0 (nula), pokud byl dosažen konec streamu.

## Viz také

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [CancellationToken](../../../system.threading/cancellationtoken/)
* Třída [FileStream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)