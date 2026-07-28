---
title: WriteAsync()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów i monitoruje żądania anulowania.
type: docs
weight: 66
url: /pl/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metoda


Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów i monitoruje żądania anulowania.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
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

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Asynchronicznie zapisuje sekwencję bajtów do bieżącego strumienia, przesuwa bieżącą pozycję w tym strumieniu o liczbę zapisanych bajtów i monitoruje żądania anulowania.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica zawierająca bajty do zapisania. |
| offset | **int32_t** | Indeks zerowy elementu w **buffer**, od którego zaczyna się podzakres do zapisania. |
| count | **int32_t** | Liczba elementów w podzakresie do zapisania. |

### Wartość zwracana

Zadanie reprezentujące asynchroniczną operację zapisu.

## Zobacz również

* Definicja typu [TaskPtr](../../../system/taskptr/)
* Definicja typu [ArrayPtr](../../../system/arrayptr/)
* Klasa [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasa [Stream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)