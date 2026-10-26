---
title: Read()
second_title: Aspose.Slides för C++ API-referens
description: Om inkapslingsläge är binärt läses det angivna antalet byte från strömmen, annars läses det angivna antalet tecken och konverteras till uint8_t-typ. Skriver resultatet av läsningen till den angivna bytearrayen.
type: docs
weight: 66
url: /sv/system.io/basicstdiostreamwrapper/read/
---
## BasicSTDIOStreamWrapper::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metod


Om inkapslingsläge är binärt läses det angivna antalet byte från strömmen, annars läses det angivna antalet tecken och konverteras till **uint8_t**-typ. Skriver resultatet av läsningen till den angivna bytearrayen.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bytearrayen att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** där skrivning ska börja |
| count | **int32_t** | Antalet byte som ska läsas |

### Returvärde

Antal lästa byte eller tecken

## BasicSTDIOStreamWrapper::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metod


Läser det angivna antalet byte från strömmen och skriver dem till den angivna bytearrayen.

```cpp
virtual int32_t System::IO::BasicSTDIOStreamWrapper<T, typename>::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Bytearray-vyn att skriva de lästa byten till |
| offset | **int32_t** | En 0-baserad position i **buffer** där skrivning ska börja |
| count | **int32_t** | Antalet byte som ska läsas |

### Returvärde

Antalet lästa byte

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [BasicSTDIOStreamWrapper](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)