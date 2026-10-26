---
title: ToChar()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar två byte från den angivna arrayen med start på det angivna indexet till ett char_t-värde.
type: docs
weight: 40
url: /sv/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) method

Konverterar två byte från den angivna arrayen med start från det angivna indexet till ett char_t-värde.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där byte ska tas för konvertering |

## Returvärde

char_t-värde som erhålls efter konvertering

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) method

Konverterar två byte från den angivna arrayen med start från det angivna indexet till ett char_t-värde.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView som innehåller byte att konvertera |
| startIndex | int | [Index](../../index/) i arrayen där byte ska tas för konvertering |

## Returvärde

char_t-värde som erhålls efter konvertering

## Se även

* Typdefinition [ArrayPtr](../../arrayptr/)
* Klass [BitConverter](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)