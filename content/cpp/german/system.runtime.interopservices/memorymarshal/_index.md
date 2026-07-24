---
title: MemoryMarshal
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Implementierung für Speicher-Marshalling bereit. Nur zur Kompatibilität mit übersetztem Code, da auf der C++-Seite kein verwalteter Code unterstützt wird. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erzeugen.
type: docs
weight: 27
url: /de/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal Klasse


Stellt eine Implementierung für Speicher-Marshalling bereit. Nur zur Kompatibilität mit übersetztem Code, da auf der C++-Seite kein verwalteter Code unterstützt wird. Dies ist ein statischer Typ ohne Instanzdienste. Sie sollten niemals Instanzen davon auf irgendeine Weise erzeugen.

```cpp
class MemoryMarshal
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Wandelt ein [Span](../../system/span/) eines primitiven Typs T in [Span](../../system/span/) von Bytes um. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Wandelt ein [Span](../../system/span/) eines primitiven Typs TFrom in einen anderen primitiven Typ TTo um. |
## Siehe auch

* Namensraum [System::Runtime::InteropServices](../)
* Bibliothek [Aspose.Slides](../../)