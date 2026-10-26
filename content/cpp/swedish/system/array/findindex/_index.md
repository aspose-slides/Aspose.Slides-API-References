---
title: FindIndex()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för det angivna predikatet.
type: docs
weight: 638
url: /sv/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) metod

Söker efter det första elementet i den angivna arrayen som uppfyller villkoren för den angivna predikatet.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) för att söka ett element i |
| match | [System::Predicate](../../predicate/)\<T\> | Ett predikat som definierar villkoren för att matcha array-element mot |

### Returvärde

Indexet för det första elementet i arrayen som uppfyller villkoren som definieras av predikatet, annars -1

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)