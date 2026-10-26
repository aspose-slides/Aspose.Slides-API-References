---
title: ToUpper()
second_title: Odwołanie API Aspose.Slides dla C++
description: Konwertuje znaki na wielkie litery przy użyciu określonej kultury.
type: docs
weight: 469
url: /pl/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) funkcja

Konwertuje znaki do wielkich liter przy użyciu określonej kultury.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zakres znaków źródłowych do konwersji |
| destination | [Span](../../system/span/)\<char16_t\>\& | Zakres docelowy do przechowywania przekształconych znaków |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Kultura używana do konwersji (nullptr dla bieżącej kultury) |

### Wartość zwracana

Liczba przekształconych znaków lub -1, jeśli docelowy zakres jest zbyt mały

## Zobacz także

* Definicja typu [SharedPtr](../../system/sharedptr/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Klasa [CultureInfo](../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)