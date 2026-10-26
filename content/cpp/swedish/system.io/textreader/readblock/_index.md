---
title: ReadBlock()
second_title: Aspose.Slides för C++ API-referens
description: Läser det angivna maximala antalet tecken från den aktuella textläsaren och skriver data till en buffert, med början vid det angivna indexet.
type: docs
weight: 53
url: /sv/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) metod


Läser det angivna maximala antalet tecken från den aktuella textläsaren och skriver data till en buffert, med början vid det angivna indexet.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | En teckenbuffert att skriva de lästa data till |
| index | int | Ett 0-baserat index i **buffer** att börja skriva vid |
| count | int | Det maximala antalet tecken att läsa |

### Returvärde

Det faktiska antalet tecken som lästs

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)