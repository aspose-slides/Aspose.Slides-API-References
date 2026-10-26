---
title: Trace
second_title: Aspose.Slides pro C++ referenční příručka API
description: Poskytuje rozhraní pro přístup k ladicímu trasování (pokud existuje). Funguje pouze v režimu Debug. Jedná se o statický typ bez instančních služeb. Nikdy byste ho neměli vytvářet žádnými prostředky.
type: docs
weight: 131
url: /cs/system.diagnostics/trace/
---
## Trace struct


Poskytuje rozhraní pro přístup k ladicímu trasování (pokud existuje). Funguje pouze v režimu [Debug](../debug/). Jedná se o statický typ bez instančních služeb. Nikdy byste neměli vytvářet jeho instance jakýmkoli způsobem.

```cpp
class Trace
```

## Metody

| Metoda | Popis |
| --- | --- |
| static void [Flush](./flush/)() | Vyprázdní výstupní buffer a způsobí, že bufferovaná data budou zapsána do posluchačů. |
| static void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Zapíše řádek do ladicího trasování. |
## Viz také

* Jmenný prostor [System::Diagnostics](../)
* Knihovna [Aspose.Slides](../../)