---
title: ToLower()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Konwertuje znaki na małe litery przy użyciu określonej kultury.
type: docs
weight: 443
url: /pl/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) funkcja

Konwertuje znaki na małe litery przy użyciu określonej kultury.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | Zakres znaków źródłowych do konwersji |
| destination | [Span](../../system/span/)\<char16_t\>\& | Zakres docelowy do przechowywania przekonwertowanych znaków |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | Kultura używana do konwersji (nullptr dla bieżącej kultury) |

### Wartość zwracana

Liczba przekonwertowanych znaków lub -1, jeśli docelowy zakres jest zbyt mały

## Zobacz także

* Typedef [SharedPtr](../../system/sharedptr/)
* Klasa [ReadOnlySpan](../../system/readonlyspan/)
* Klasa [Span](../../system/span/)
* Klasa [CultureInfo](../../system.globalization/cultureinfo/)
* Przestrzeń nazw [System::MemoryExtensions](../)
* Biblioteka [Aspose.Slides](../../)