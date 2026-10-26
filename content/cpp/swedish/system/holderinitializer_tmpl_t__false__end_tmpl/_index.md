---
title: HolderInitializer< T, false >
second_title: Aspose.Slides för C++ API-referens
description: HolderInitializer-specialisering för fallet då T är en värdetyp. Användningskontexten tillåter att returnera referens till temporära objekt, eftersom det är garanterat att instansen kommer att kopieras av anroparen. Så används denna specialisering bara som en stub och gör ingenting.
type: docs
weight: 1652
url: /sv/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct

[HolderInitializer](../holderinitializer/) specialisering för fallet då T är en värdetyp. Användningskontexten tillåter att returnera referens till temporära objekt, eftersom det är garanterat att instansen kommer att kopieras av anroparen. Så används denna specialisering bara som en stub och gör inget.

```cpp
template<typename T>class HolderInitializer< T, false >
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |
## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)