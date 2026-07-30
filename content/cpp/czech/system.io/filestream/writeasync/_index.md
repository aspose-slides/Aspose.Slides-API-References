---
title: WriteAsync()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Asynchronně zapisuje sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a sleduje požadavky na zrušení.
type: docs
weight: 261
url: /cs/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metoda


Asynchronně zapisuje sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a sleduje požadavky na zrušení.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu. |
| offset | **int32_t** | Index založený na nule v **buffer**, od kterého začíná podrozsah k zápisu. |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token sledovaný pro požadavky na zrušení. |

### Návratová hodnota

Úloha reprezentující asynchronní operaci zápisu.

## Viz také

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [CancellationToken](../../../system.threading/cancellationtoken/)
* Třída [FileStream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)