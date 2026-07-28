---
title: ReadAsync()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przesuwa pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania.
type: docs
weight: 40
url: /pl/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metoda


Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przesuwa pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty. |
| offset | **int32_t** | Pozycja zaczynająca się od zera w **buffer**, od której rozpocząć zapisywanie. |
| count | **int32_t** | Liczba bajtów do odczytania. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token monitorujący żądania anulowania. |

### Wartość zwracana

Zadanie, które reprezentuje asynchroniczną operację odczytu. Wartość parametru TResult zawiera całkowitą liczbę bajtów odczytanych do bufora. Wartość wyniku może być mniejsza niż liczba żądanych bajtów, jeśli dostępna liczba bajtów jest mniejsza niż żądana, lub może wynosić 0 (zero), jeśli osiągnięto koniec strumienia.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Asynchronicznie odczytuje sekwencję bajtów z bieżącego strumienia, przesuwa pozycję w strumieniu o liczbę odczytanych bajtów i monitoruje żądania anulowania.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Tablica bajtów, do której zapisywane są odczytane bajty. |
| offset | **int32_t** | Pozycja zaczynająca się od zera w **buffer**, od której rozpocząć zapisywanie. |
| count | **int32_t** | Liczba bajtów do odczytania. |

### Wartość zwracana

Zadanie, które reprezentuje asynchroniczną operację odczytu. Wartość parametru TResult zawiera całkowitą liczbę bajtów odczytanych do bufora. Wartość wyniku może być mniejsza niż liczba żądanych bajtów, jeśli dostępna liczba bajtów jest mniejsza niż żądana, lub może wynosić 0 (zero), jeśli osiągnięto koniec strumienia.

## Zobacz także

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasa [Stream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)