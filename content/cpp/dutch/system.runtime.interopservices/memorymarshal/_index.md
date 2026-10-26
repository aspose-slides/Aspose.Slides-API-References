---
title: MemoryMarshal
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt een implementatie voor geheugenmarshalling. Alleen voor compatibiliteit met vertaalde code, aangezien er geen beheerde code wordt ondersteund aan de C++-kant. Dit is een statisch type zonder instantie services. U mag nooit op welke manier ook instanties ervan maken.
type: docs
weight: 27
url: /nl/system.runtime.interopservices/memorymarshal/
---
## MemoryMarshal klasse

Provides memory marshalling implementation. For compatibility with translated code only, as no managed code is supported on C++ side. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class MemoryMarshal
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [Span](../../system/span/)\<**uint8_t**\> [AsBytes](./asbytes/)(const [Span](../../system/span/)\<T\>\&) | Converteert een [Span](../../system/span/) van één primitief type T naar [Span](../../system/span/) van bytes. |
| static [Span](../../system/span/)\<TTo\> [Cast](./cast/)(const [Span](../../system/span/)\<TFrom\>\&) | Converteert een [Span](../../system/span/) van één primitief type TFrom naar een ander primitief type TTo. |

## Zie ook

* Namespace [System::Runtime::InteropServices](../)
* Bibliotheek [Aspose.Slides](../../)