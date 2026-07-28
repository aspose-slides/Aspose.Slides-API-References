---
title: Trace
second_title: Referencja API Aspose.Slides dla C++
description: Udostępnia interfejs do dostępu do śladu debugera (jeśli istnieje). Działa tylko w trybie Debug. Jest to typ statyczny bez usług instancji. Nie należy tworzyć jego instancji w żaden sposób.
type: docs
weight: 131
url: /pl/system.diagnostics/trace/
---
## Trace struct

Provides interface to access debugger trace (if any). Works in [Debug](../debug/) mode only. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Trace
```

## Metody

| Metoda | Opis |
| --- | --- |
| static void [Flush](./flush/)() | Opróżnia bufor wyjściowy i powoduje zapis buforowanych danych do słuchaczy. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Zapisuje linię do śladu debugera. |

## Zobacz także

* Przestrzeń nazw [System::Diagnostics](../)
* Biblioteka [Aspose.Slides](../../)