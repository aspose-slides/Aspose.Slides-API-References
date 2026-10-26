---
title: Size
second_title: Aspose.Slides C++ API Referenciája
description: "Egy egész számot tartalmazó párt képvisel, amely egy kép szélességét és magasságát adja meg. Ezt a típust a veremben kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 274
url: /hu/system.drawing/size/
---
## Méret osztály

Egy egész számotípusú párost képvisel, amely a kép szélességét és magasságát tartalmazza. Ezt a típust a stack-en kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class Size
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [Size](./) [Add](./add/)(const [Size](./)\&, const [Size](./)\&) | Visszaad egy új [Size](./) objektumot, amely a megadott [Size](./) objektum összege, azaz a szélesség értéke megegyezik a megadott objektumok szélességértékeinek összegével, a magasság értéke pedig a megadott objektumok magasságértékeinek összegével. |
| static [Size](./) [Ceiling](./ceiling/)(const [SizeF](../sizef/)\&) | Létrehoz egy [Size](./) objektumot a megadott [SizeF](../sizef/) objektumból úgy, hogy a [SizeF](../sizef/) objektum szélesség- és magasságértékeit a következő nagyobb egész számra kerekíti. |
| **bool** [Equals](./equals/)(const [Size](./)\&) const | Megállapítja, hogy a jelenlegi objektum és a megadott objektum egyenlőek-e, azaz ugyanazt a szélesség- és magasságérték-párt képviselik. |
| int [get_Height](./get_height/)() const | Visszaadja a jelenlegi objektum által képviselt magasság értékét. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Megállapítja, hogy a szélesség és magasság értékei egyaránt 0-k-e. |
| int [get_Width](./get_width/)() const | Visszaadja a jelenlegi objektum által képviselt szélesség értékét. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumhoz. |
| [operator Point](./operator_point/)() const | Létrehoz egy [Point](../point/) objektum példányt, és annak X és Y koordinátáit a jelenlegi objektum szélesség- és magasságértékeivel inicializálja megfelelően. |
| [operator SizeF](./operator_sizef/)() const | Létrehoz egy [SizeF](../sizef/) objektum példányt, és azt a jelenlegi [Size](./) objektum szélesség- és magasságértékeivel inicializálja. |
| static [Size](./) [Round](./round/)(const [SizeF](../sizef/)\&) | Létrehoz egy [Size](./) objektumot a megadott [SizeF](../sizef/) objektumból úgy, hogy a [SizeF](../sizef/) objektum szélesség- és magasságértékeit a legközelebbi egész számra kerekíti. |
| void [set_Height](./set_height/)(int) | Beállítja a jelenlegi objektum által képviselt magasság értékét. |
| void [set_Width](./set_width/)(int) | Beállítja a jelenlegi objektum által képviselt szélesség értékét. |
| [Size](./size/)() | Létrehoz egy új [Size](./) objektumot, és annak szélesség- és magasságértékeit 0-ra inicializálja. |
| [Size](./size/)(const [Point](../point/)\&) | Létrehoz egy új [Size](./) objektumot, és annak szélesség- és magasságértékeit a megadott pont X és Y koordinátáival inicializálja megfelelően. |
| [Size](./size/)(int, int) | Létrehoz egy új [Size](./) objektumot, és azt a megadott értékkel inicializálja. |
| static [Size](./) [Subtract](./subtract/)(const [Size](./)\&, const [Size](./)\&) | Visszaad egy új [Size](./) objektumot, amely a **size1** és **size2** kivonásának eredménye, azaz a szélesség értéke **size1** szélességéből mínusz **size2** szélessége, a magasság értéke pedig **size1** magasságából mínusz **size2** magassága. |
| [String](../../system/string/) [ToString](./tostring/)() const | Visszaadja a jelenlegi objektum által képviselt szélesség- és magasságérték-pár karakterlánc ábrázolását. |
| static [Size](./) [Truncate](./truncate/)(const [SizeF](../sizef/)\&) | Létrehoz egy [Size](./) objektumot a megadott [SizeF](../sizef/) objektumból úgy, hogy a [SizeF](../sizef/) objektum szélesség- és magasságértékeit a következő alacsonyabb egész számra csonkolja. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Empty](./empty/) | Egy üres példány a [Size](./) osztályból, amelynek szélesség- és magasságértékei 0. |

## Lásd még

* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)