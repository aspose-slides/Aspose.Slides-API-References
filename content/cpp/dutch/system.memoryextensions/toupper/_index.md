---
title: ToUpper()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert tekens naar hoofdletters met behulp van de opgegeven cultuur.
type: docs
weight: 469
url: /nl/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) functie

Converteert tekens naar hoofdletters met behulp van de opgegeven cultuur.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | De bron-karakter-span om te converteren |
| destination | [Span](../../system/span/)\<char16_t\>\& | De bestemmings-span om geconverteerde tekens op te slaan |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | De cultuur die moet worden gebruikt voor conversie (nullptr voor de huidige cultuur) |

### Retourwaarde

Aantal geconverteerde tekens, of -1 als de bestemming te klein is

## Zie ook

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Klasse [CultureInfo](../../system.globalization/cultureinfo/)
* Namespace [System::MemoryExtensions](../)
* Bibliotheek [Aspose.Slides](../../)