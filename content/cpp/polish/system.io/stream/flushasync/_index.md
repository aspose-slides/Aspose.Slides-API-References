---
title: FlushAsync()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Asynchronicznie usuwa wszystkie bufory tego strumienia, powoduje zapisanie wszelkich buforowanych danych do urządzenia podstawowego i monitoruje żądania anulowania.
type: docs
weight: 118
url: /pl/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) metoda


Asynchronicznie usuwa wszystkie bufory tego strumienia, powoduje zapisanie wszelkich buforowanych danych do urządzenia podstawowego i monitoruje żądania anulowania.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token monitorujący żądania anulowania. |

### Wartość zwracana

Zadanie reprezentujące asynchroniczną operację opróżniania.

## Stream::FlushAsync() metoda


Asynchronicznie usuwa wszystkie bufory tego strumienia, powoduje zapisanie wszelkich buforowanych danych do urządzenia podstawowego i monitoruje żądania anulowania.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### Wartość zwracana

Zadanie reprezentujące asynchroniczną operację opróżniania.

## Zobacz także

* Definicja typu [TaskPtr](../../../system/taskptr/)
* Klasa [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasa [Stream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)