---
title: HolderInitializer< T, false >
second_title: Aspose.Slides dla API C++
description: Specjalizacja HolderInitializer dla przypadku, gdy T jest typem wartościowym. Kontekst użycia pozwala zwrócić referencję do obiektów tymczasowych, ponieważ jest gwarantowane, że instancja zostanie skopiowana przez wywołującego. Dlatego ta specjalizacja jest używana jedynie jako szkielet i nie robi nic.
type: docs
weight: 1652
url: /pl/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct

[HolderInitializer](../holderinitializer/) specjalizacja dla przypadku, gdy T jest typem wartościowym. Kontekst użycia pozwala zwrócić referencję do obiektów tymczasowych, ponieważ gwarantowane jest, że instancja zostanie skopiowana przez wywołującego. Dlatego ta specjalizacja jest używana jedynie jako szkielet i nie robi nic.

```cpp
template<typename T>class HolderInitializer< T, false >
```

## Metody

| Metoda | Opis |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |

## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)