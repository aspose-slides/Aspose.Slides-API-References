---
title: BitVector32
second_title: Aspose.Slides C++ API Referenciája
description: Egyszerű, könnyű bitvektort biztosít, amely egyszerű egész vagy Boolean hozzáférést nyújt egy 32 bites tárolóhoz.
type: docs
weight: 1
url: /hu/system.collections.specialized/bitvector32/
---
## BitVector32 osztály

Egyszerű, könnyű bitvektort biztosít könnyű egész vagy [Boolean](../../system/boolean/) hozzáféréssel egy 32 bites tárolóhoz.

```cpp
class BitVector32
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Új üres példányt inicializál a [BitVector32](./)-ból. |
|  [BitVector32](./bitvector32/)(**int32_t**) | Új példányt inicializál a [BitVector32](./) struktúrából a megadott belső adatokkal. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Új példányt inicializál a [BitVector32](./) struktúrából a megadott értékben lévő információval. |
| static **int32_t** [CreateMask](./createmask/)() | Létrehozza a sorozat első maszkját. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Létrehozza a sorozat következő maszkját. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Létrehozza a sorozat első szekcióját a megadott maximális értékkel. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Létrehozza a sorozat következő szekcióját a megadott maximális értékkel. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Megállapítja, hogy a megadott objektum megegyezik-e a jelenlegivel. |
| **int32_t** [get_Data](./get_data/)() | visszaadja a bitvektorban tárolt nyers adatot... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumhoz. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Lekéri az értéket, amely jelzi, hogy az összes megadott bit be van-e állítva. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Lekéri a megadott szekció értékét. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Beállít egy értéket, amely jelzi, hogy az összes megadott bit be van-e állítva. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Beállítja a megadott szekció értékét. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Átalakítja a value paraméter által képviselt értéket karakterlánccá. |
| [String](../../system/string/) [ToString](./tostring/)() const | Átalakítja a jelenlegi objektum által képviselt értéket karakterlánccá. |

## Lásd még

* Névtér [System::Collections::Specialized](../)
* Könyvtár [Aspose.Slides](../../)