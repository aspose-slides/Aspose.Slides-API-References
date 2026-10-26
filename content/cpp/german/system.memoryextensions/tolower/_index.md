---
title: ToLower()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert Zeichen in Kleinbuchstaben mithilfe der angegebenen Kultur.
type: docs
weight: 443
url: /de/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) Funktion

Konvertiert Zeichen in Kleinbuchstaben unter Verwendung der angegebenen Kultur.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Der Quellzeichen-Span, der konvertiert werden soll |
| destination | [Span](../../system/span/)\<char16_t\>\& | Der Ziel-Span, in dem die konvertierten Zeichen gespeichert werden |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Die für die Konvertierung zu verwendende Kultur (nullptr für die aktuelle Kultur) |

### Rückgabewert

Anzahl der konvertierten Zeichen oder -1, wenn das Ziel zu klein ist

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasse [ReadOnlySpan](../../system/readonlyspan/)
* Klasse [Span](../../system/span/)
* Klasse [CultureInfo](../../system.globalization/cultureinfo/)
* Namensraum [System::MemoryExtensions](../)
* Bibliothek [Aspose.Slides](../../)