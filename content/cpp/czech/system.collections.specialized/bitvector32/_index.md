---
title: BitVector32
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje jednoduchý lehký bitový vektor s snadným celočíselným nebo logickým přístupem k 32-bitovému úložišti.
type: docs
weight: 1
url: /cs/system.collections.specialized/bitvector32/
---
## BitVector32 třída

Poskytuje jednoduchý lehký bitový vektor s snadným celočíselným nebo [Boolean](../../system/boolean/) přístupem k 32bitovému úložišti.

```cpp
class BitVector32
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [BitVector32](./bitvector32/)() | Inicializuje novou prázdnou instanci [BitVector32](./). |
|  [BitVector32](./bitvector32/)(**int32_t**) | Inicializuje novou instanci struktury [BitVector32](./) s danými vnitřními daty. |
|  [BitVector32](./bitvector32/)(const [BitVector32](./)\&) | Inicializuje novou instanci struktury [BitVector32](./) s informacemi v zadané hodnotě. |
| static **int32_t** [CreateMask](./createmask/)() | Vytvoří první masku v sérii. |
| static **int32_t** [CreateMask](./createmask/)(**int32_t**) | Vytvoří následující masku v sérii. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**) | Vytvoří první sekci v sérii s určenou maximální hodnotou. |
| static **BitVector32::Section** [CreateSection](./createsection/)(**int16_t**, **BitVector32::Section**) | Vytvoří další sekci v sérii s určenou maximální hodnotou. |
| **bool** [Equals](./equals/)(const [BitVector32](./)\&) | Určuje, zda je zadaný objekt stejný jako aktuální. |
| **int32_t** [get_Data](./get_data/)() | vrací surová data uložená v tomto bitovém vektoru... |
| **int32_t** [GetHashCode](./gethashcode/)() const | Vrací hash kód pro aktuální objekt. |
| **bool** [idx_get](./idx_get/)(**int32_t**) | Získá hodnotu, která určuje, zda jsou všechna specifikovaná bity nastavená. |
| **int32_t** [idx_get](./idx_get/)(**BitVector32::Section**) | Získá hodnotu pro specifikovanou sekci. |
| void [idx_set](./idx_set/)(**int32_t**, **bool**) | Nastaví hodnotu, která určuje, zda jsou všechna specifikovaná bity nastavená. |
| void [idx_set](./idx_set/)(**BitVector32::Section**, **int32_t**) | Nastaví hodnotu pro specifikovanou sekci. |
| static [String](../../system/string/) [ToString](./tostring/)(const [BitVector32](./)\&) | Převede hodnotu reprezentovanou parametrem value na řetězec. |
| [String](../../system/string/) [ToString](./tostring/)() const | Převede hodnotu reprezentovanou aktuálním objektem na řetězec. |

## Viz také

* jmenný prostor [System::Collections::Specialized](../)
* Knihovna [Aspose.Slides](../../)