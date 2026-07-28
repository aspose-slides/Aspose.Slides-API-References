---
title: FlushAsync()
second_title: Aspose.Slides dla interfejsu API C++
description: Asynchronicznie opróżnia wszystkie bufory tego strumienia, powoduje zapisanie wszelkich danych buforowanych do leżącego pod spodem urządzenia oraz monitoruje żądania anulowania.
type: docs
weight: 157
url: /pl/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) metoda

Asynchronicznie opróżnia wszystkie bufory tego strumienia, powoduje zapisanie wszelkich danych buforowanych do leżącego pod spodem urządzenia oraz monitoruje żądania anulowania.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token monitorujący żądania anulowania. |

### Wartość zwracana

Zadanie reprezentujące asynchroniczną operację opróżniania.

## Zobacz także

* Typedef [TaskPtr](../../../system/taskptr/)
* Klasa [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasa [FileStream](../)
* Przestrzeń nazw [System::IO](../../)
* Biblioteka [Aspose.Slides](../../../)