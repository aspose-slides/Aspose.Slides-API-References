---
title: TrueForAll()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om alla element i den angivna arrayen uppfyller villkoren som definieras av det angivna predikatet.
type: docs
weight: 677
url: /sv/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metod


Bestämmer om alla element i den angivna arrayen uppfyller villkoren som definieras av det angivna predikatet.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) element som ska matchas mot villkoren |
| match | [System::Predicate](../../predicate/)\<T\> | Ett predikat som definierar villkoren för att matcha array-element mot |

### Returvärde

true om alla element i arrayen arr uppfyller villkoren som definieras av predikatet match, annars false

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)