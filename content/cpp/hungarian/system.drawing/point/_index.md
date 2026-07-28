---
title: Point
second_title: Aspose.Slides C++ API referencia
description: "Egy 2-dimenziós síkon egy pont egész X és Y koordinátáit tartalmazó párt reprezentál. Ezt a típust a stack-en kell lefoglalni, és értékként vagy referenciaként kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 209
url: /hu/system.drawing/point/
---
## Pont osztály


Egy 2-dimenziós síkon lévő pont egész X és Y koordinátáit tartalmazó párt reprezentál. Ezt a típust a stack-en kell lefoglalni, és értékként vagy referenciaként kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class Point
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [Point](./) [Add](./add/)(const [Point](./)\&, const [Size](../size/)\&) | A megadott [Size](../size/) objektum szélesség- és magasságértékeit a megadott [Point](./) objektum X és Y koordinátaértékeihez adja hozzá megfelelően. |
| static [Point](./) [Ceiling](./ceiling/)(const [PointF](../pointf/)\&) | Létrehoz egy [Point](./) objektumot a megadott [PointF](../pointf/) objektumból úgy, hogy a [PointF](../pointf/) objektum X és Y koordinátaértékeit a következő magasabb egész számra kerekíti. |
| **bool** [Equals](./equals/)(const [Point](./)\&) const | Megállapítja, hogy a jelenlegi objektum és a megadott objektum egyenlő-e, vagyis ugyanazt az X és Y koordinátapárt reprezentálja. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Megállapítja, hogy mind az X, mind az Y koordinátaérték 0-e. |
| int [get_X](./get_x/)() const | Visszaadja a jelenlegi objektum által reprezentált X koordináta értékét. |
| int [get_Y](./get_y/)() const | Visszaadja a jelenlegi objektum által reprezentált Y koordináta értékét. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumhoz. |
| size_t [getStdHash](./getstdhash/)() const | Visszaad egy hash értéket a jelenlegi objektumhoz. |
| **bool** [IsNull](./isnull/)() const | Mindig hamis értéket ad vissza. |
| void [Offset](./offset/)(int, int) | Az aktuális objektum által reprezentált X és Y koordinátaértéket eltolja a megadott értékekkel. |
| void [Offset](./offset/)([Point](./)) | Az aktuális objektum X és Y koordinátáit eltolja a megadott [Point](./) objektum X és Y koordinátaértékeivel megfelelően. |
|  [operator PointF](./operator_pointf/)() const | Létrehoz egy [PointF](../pointf/) objektum példányt, és inicializálja azt a jelenlegi [Point](./) objektum X és Y koordinátaértékeivel. |
|  [operator Size](./operator_size/)() const | Létrehoz egy [Size](../size/) objektum példányt, és annak szélesség- és magasságértékeit a jelenlegi objektum X és Y koordinátaértékeivel állítja be megfelelően. |
|  [Point](./point/)() | Létrehoz egy új [Point](./) objektumot, és X és Y koordinátaértékeit 0-ra inicializálja. |
|  [Point](./point/)(int, int) | Létrehoz egy új [Point](./) objektumot, és a megadott értékekkel inicializálja. |
|  [Point](./point/)(const [Size](../size/)\&) | Létrehoz egy új [Point](./) objektumot, és annak X és Y koordinátaértékeit a megadott [SizeF](../sizef/) objektum szélesség- és magasságértékeivel állítja be megfelelően. |
|  [Point](./point/)(int) | Létrehoz egy új [Point](./) objektumot, és annak X koordinátaértékét a megadott 32 bit egész szám felső 16 bitjéből, Y koordinátaértékét pedig az alsó 16 bitjéből állítja elő. |
| static [Point](./) [Round](./round/)(const [PointF](../pointf/)\&) | Létrehoz egy [Point](./) objektumot a megadott [PointF](../pointf/) objektumból úgy, hogy a [PointF](../pointf/) objektum X és Y koordinátaértékeit a legközelebbi egész számra kerekíti. |
| void [set_X](./set_x/)(int) | Beállítja a jelenlegi objektum által reprezentált X koordináta értékét. |
| void [set_Y](./set_y/)(int) | Beállítja a jelenlegi objektum által reprezentált Y koordináta értékét. |
| static [Point](./) [Subtract](./subtract/)(const [Point](./)\&, const [Size](../size/)\&) | A megadott [Size](../size/) objektum szélesség- és magasságértékeit levonja a megadott [Point](./) objektum X és Y koordinátaértékeiből megfelelően. |
| [String](../../system/string/) [ToString](./tostring/)() const | Visszaadja a jelenlegi objektum által reprezentált X és Y koordinátapár karakterláncábrázolását. |
| static [Point](./) [Truncate](./truncate/)(const [PointF](../pointf/)\&) | Létrehoz egy [Point](./) objektumot a megadott [PointF](../pointf/) objektumból úgy, hogy a [PointF](../pointf/) objektum X és Y koordinátaértékeit a következő alacsonyabb egész számra csonkolja. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Empty](./empty/) | Egy üres [Point](./) osztálypéldány, amelynek X és Y koordinátaértékei 0. |

## Lásd még

* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)