---
title: ScopeGuard
second_title: Aspose.Slides C++ API Referencia
description: Az a szolgáltató osztály, amely egy adott függvényobjektum végrehajtását biztosítja, amikor az osztály egy példánya kilép a hatókörből.
type: docs
weight: 1886
url: /hu/system/scopeguard/
---
## ScopeGuard struct

Az a szolgáltató osztály, amely egy adott függvényobjektum végrehajtását biztosítja, amikor az osztály egy példánya kilép a hatókörből.

```cpp
template<typename F>class ScopeGuard
```

### Sablon paraméterek

| Paraméter | Leírás |
| --- | --- |
| F | A ScopedGuard osztály példányai által meghívott függvényobjektum típusa |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| void [Disable](./disable/)() | Letiltsa a védelmi meghívást. |
| [ScopeGuard](./scopeguard/)(F) | Létrehozza azt a példányt, amely be van állítva az adott függvényobjektum meghívására. |
| [~ScopeGuard](./~scopeguard/)() | Meghívja a konstruktorban átadott függvényobjektumot. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)