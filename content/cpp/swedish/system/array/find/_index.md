---
title: Find()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet.
type: docs
weight: 651
url: /sv/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) metod

Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) för att söka ett element i |
| match | [System::Predicate](../../predicate/)\<T\> | Ett predikat som definierar villkoren för att matcha arrayelement mot |

### Returvärde

Kopia av det första elementet i arrayen som uppfyller villkoren definierade av predikatet, annars standardvärdet för typen T

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)