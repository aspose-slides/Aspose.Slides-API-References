---
title: FlushAsync()
second_title: Aspose.Slides pro C++ – reference API
description: Asynchronně vymaže všechny vyrovnávací paměti tohoto proudu, způsobí, že se veškerá vyrovnaná data zapíší do podkladového zařízení, a monitoruje požadavky na zrušení.
type: docs
weight: 118
url: /cs/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) metoda


Asynchronně vymaže všechny vyrovnávací paměti tohoto proudu, způsobí, že se veškerá vyrovnaná data zapíší do podkladového zařízení, a monitoruje požadavky na zrušení.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token, který se sleduje pro požadavky na zrušení. |

### Návratová hodnota

Úloha, která představuje asynchronní operaci vyprázdnění.

## Stream::FlushAsync() metoda


Asynchronně vymaže všechny vyrovnávací paměti tohoto proudu, způsobí, že se veškerá vyrovnaná data zapíší do podkladového zařízení, a monitoruje požadavky na zrušení.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### Návratová hodnota

Úloha, která představuje asynchronní operaci vyprázdnění.

## Viz také

* Typedef [TaskPtr](../../../system/taskptr/)
* Třída [CancellationToken](../../../system.threading/cancellationtoken/)
* Třída [Stream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)