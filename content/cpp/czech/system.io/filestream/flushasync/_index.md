---
title: FlushAsync()
second_title: Aspose.Slides pro C++ – API reference
description: Asynchronně vyprázdní všechny vyrovnávací paměti tohoto proudu, způsobí, že se veškerá vyrovnaná data zapíšou na podkladové zařízení, a monitoruje požadavky na zrušení.
type: docs
weight: 157
url: /cs/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) method

Asynchronně vyprázdní všechny vyrovnávací paměti tohoto proudu, způsobí, že se veškerá vyrovnaná data zapíšou na podkladové zařízení, a monitoruje požadavky na zrušení.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token, který se má sledovat pro požadavky na zrušení. |

### Návratová hodnota

Úloha, která představuje asynchronní operaci vyprázdnění.

## Viz také

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)