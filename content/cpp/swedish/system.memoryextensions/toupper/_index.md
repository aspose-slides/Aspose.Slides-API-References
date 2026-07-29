---
title: ToUpper()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar tecken till versaler med angiven kultur.
type: docs
weight: 469
url: /sv/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) funktion

Konverterar tecken till versaler med angiven kultur.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Källspannet att konvertera |
| destination | [Span](../../system/span/)\<char16_t\>\& | Destinationspannet för att lagra konverterade tecken |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Kulturen som ska användas för konvertering (nullptr för aktuell kultur) |

### Returvärde

Antal konverterade tecken, eller -1 om destinationen är för liten

## Se även

* Typedef [SharedPtr](../../system/sharedptr/)
* Klass [ReadOnlySpan](../../system/readonlyspan/)
* Klass [Span](../../system/span/)
* Klass [CultureInfo](../../system.globalization/cultureinfo/)
* Namnrymd [System::MemoryExtensions](../)
* Bibliotek [Aspose.Slides](../../)