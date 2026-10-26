---
title: WriteAsync()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów oraz monitoruje żądania anulowania.
type: docs
weight: 261
url: /pl/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metoda

Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów i monitoruje żądania anulowania.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania. |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisania. |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token służący do monitorowania żądań anulowania. |

### Wartość zwracana

Zadanie reprezentujące asynchroniczną operację zapisu.

## Zobacz także

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)