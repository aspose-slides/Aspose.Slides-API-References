---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.
type: docs
weight: 27
url: /sv/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte-arrayen att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** där skrivning ska börja |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Byte-array-vyn att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** där skrivning ska börja |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) metod

Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| N | Storleken på stack-arrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | Byte-stack-arrayen att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** där skrivning ska börja |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## Stream::Read(const System::Span\<uint8_t\>\&) metod

Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-spannet.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | Byte-spannet att skriva de lästa byten till |

### Returvärde

Antalet lästa byte

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [Stream](../)
* Klass [Span](../../../system/span/)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)