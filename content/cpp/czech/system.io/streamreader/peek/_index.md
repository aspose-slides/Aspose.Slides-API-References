---
title: Peek()
second_title: Aspose.Slides pro C++ dokumentace API
description: Přečte jeden znak ze streamu, aniž by změnil čtecí kurzor streamu.
type: docs
weight: 27
url: /cs/system.io/streamreader/peek/
---
## StreamReader::Peek() metoda


Přečte jeden znak ze streamu, aniž by změnil čtecí kurzor streamu.

```cpp
virtual int System::IO::StreamReader::Peek() override
```


### Návratová hodnota

Přečtený znak zakódovaný v kódování UTF-16; pokud je přečtený znak reprezentován dvěma kódpunkty v kódování UTF-16, je vrácen pouze vysoký surrogate; pokud nebyl přečten žádný znak, je vráceno -1

## Viz také

* Class [StreamReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)