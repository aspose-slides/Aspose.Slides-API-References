---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Om omslagsläget är binärt läses det angivna antalet byte från strömmen, annars läses det angivna antalet tecken och konverteras till uint8_t-typen. Skriver resultatet av läsningen till den angivna byte-arrayen.
type: docs
weight: 66
url: /sv/system.io/basicstdistreamwrapper/read/
---
## BasicSTDIStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod

Om omslagsläget är binärt läses det angivna antalet byte från strömmen, annars läses det angivna antalet tecken och konverteras till **uint8_t**-typen. Skriver resultatet av läsningen till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Byte-arrayen att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antal lästa byte eller tecken

## BasicSTDIStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod

Läser det angivna antalet byte från strömmen och skriver dem till den angivna byte-arrayen.

```cpp
virtual int32_t System::IO::BasicSTDIStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Byte-arrayvyn att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** att börja skriva på |
| count | **int32_t** | Antalet byte att läsa |

### Returvärde

Antalet lästa byte

## Se också

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [BasicSTDIStreamWrapper](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)