---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver den angivna delsektionen av byte från den angivna bytearrayen till strömmen.
type: docs
weight: 53
url: /sv/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Skriver den angivna delsektionen av byte från den angivna bytearrayen till strömmen.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Arrayen som innehåller byte som ska skrivas |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där den skrivna delsektionen börjar |
| count | **int32_t** | Antalet element i delsektionen som ska skrivas |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod


Skriver den angivna delsektionen av byte från den angivna bytearrayen till strömmen.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Arrayvyn som innehåller byte som ska skrivas |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där den skrivna delsektionen börjar |
| count | **int32_t** | Antalet element i delsektionen som ska skrivas |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metod


Skriver den angivna delsektionen av byte från den angivna bytearrayen till strömmen.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Mallparametrar

| Parameter | Description |
| --- | --- |
| N | Storleken på stackarrayen |

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Stackarrayen som innehåller byte som ska skrivas |
| offset | **int32_t** | Ett 0-baserat index för elementet i **buffer** där den skrivna delsektionen börjar |
| count | **int32_t** | Antalet element i delsektionen som ska skrivas |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) metod


Skriver den angivna delsektionen av byte från den angivna byteintervallen till strömmen.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | Byteintervallen att läsa de skrivna byten från |

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Stream](../)
* Class [ReadOnlySpan](../../../system/readonlyspan/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)