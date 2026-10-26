---
title: ReadAsync()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przemieszcza pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania.
type: docs
weight: 196
url: /pl/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metoda

Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przemieszcza pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty. |
| offset | **int32_t** | Pozycja indeksowana od zera w **buffer**, od której rozpocząć zapisywanie. |
| count | **int32_t** | Liczba bajtów do odczytania. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token monitorujący żądania anulowania. |

### Wartość zwracana

Zadanie reprezentujące asynchroniczną operację odczytu. Wartość parametru TResult zawiera całkowitą liczbę bajtów odczytanych do bufora. Wartość wyniku może być mniejsza niż liczba żądanych bajtów, jeśli aktualnie dostępna liczba bajtów jest mniejsza niż żądana, albo może być równa 0 (zero), jeśli osiągnięto koniec strumienia.

## Zobacz także

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasa [FileStream](../)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)