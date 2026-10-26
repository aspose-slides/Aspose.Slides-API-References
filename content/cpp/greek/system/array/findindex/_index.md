---
title: FindIndex()
second_title: Aspose.Slides για C++ - αναφορά API
description: Αναζητά το πρώτο στοιχείο στον καθορισμένο πίνακα που ικανοποιεί τις συνθήκες της καθορισμένης predicate.
type: docs
weight: 638
url: /el/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) method


Αναζητά το πρώτο στοιχείο στον καθορισμένο πίνακα που ικανοποιεί τις προϋποθέσεις της καθορισμένης predicate.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) για αναζήτηση ενός στοιχείου σε |
| match | [System::Predicate](../../predicate/)\<T\> | Μια συνθήκη που ορίζει τις προϋποθέσεις για την αντιστοίχιση των στοιχείων του πίνακα |

### Return Value

Ο δείκτης του πρώτου στοιχείου στον πίνακα που ικανοποιεί τις συνθήκες που ορίζονται από την predicate, διαφορετικά \-1

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)