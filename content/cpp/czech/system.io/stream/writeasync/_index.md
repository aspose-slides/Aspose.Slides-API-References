---
title: WriteAsync()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Asynchronně zapisuje sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje požadavky na zrušení.
type: docs
weight: 66
url: /cs/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) metoda


Asynchronně zapisuje sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje požadavky na zrušení.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu. |
| offset | **int32_t** | Nulový index prvku v **buffer**, kde začíná podrozsah k zápisu. |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Token pro sledování požadavků na zrušení. |

### Návratová hodnota

Úkol, který představuje asynchronní operaci zápisu.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metoda


Asynchronně zapisuje sekvenci bajtů do aktuálního proudu, posouvá aktuální pozici v tomto proudu o počet zapsaných bajtů a monitoruje požadavky na zrušení.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole obsahující bajty k zápisu. |
| offset | **int32_t** | Nulový index prvku v **buffer**, kde začíná podrozsah k zápisu. |
| count | **int32_t** | Počet prvků v podrozsahu k zápisu. |

### Návratová hodnota

Úkol, který představuje asynchronní operaci zápisu.

## Viz také

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [CancellationToken](../../../system.threading/cancellationtoken/)
* Třída [Stream](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)