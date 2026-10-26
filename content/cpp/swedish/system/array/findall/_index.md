---
title: FindAll()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar alla element som matchar de villkor som definieras av det angivna predikatet.
type: docs
weight: 664
url: /sv/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metod

Hämtar alla element som matchar de villkor som definieras av det angivna predikatet.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) för att söka element i |
| match | [System::Predicate](../../predicate/)\<T\> | Ett predikat som definierar villkoren för att matcha array-element mot |

### Returvärde

En [Array](../) som innehåller alla element som matchar de villkor som definieras av det angivna predikatet, om den hittas; annars en tom [Array](../).

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)