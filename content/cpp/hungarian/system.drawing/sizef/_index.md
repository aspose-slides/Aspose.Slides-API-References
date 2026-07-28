---
title: SizeF
second_title: Aspose.Slides C++ API referencia
description: "Egyszeres pontosságú lebegőpontos értékek párosát képviseli, amelyek egy kép szélességét és magasságát határozzák meg. Ezt a típust a veremben kell példányosítani, és érték szerint vagy referenciaként átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 287
url: /hu/system.drawing/sizef/
---
## SizeF osztály


Represents a pair of single-precision floating point values that represent width and height of an image. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../../system/smartptr/) osztály to manage objects of this type.

```cpp
class SizeF
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [SizeF](./) [Add](./add/)(const [SizeF](./)\&, const [SizeF](./)\&) | Visszaad egy új [SizeF](./) objektumot, amely a megadott [SizeF](./) objektumok összege, azaz szélességértéke megegyezik a megadott objektumok szélességértékeinek összegével, és magasságértéke a megadott objektumok magasságértékeinek összegével. |
| **bool** [Equals](./equals/)(const [SizeF](./)\&) const | Megállapítja, hogy a jelenlegi objektum és a megadott objektum egyenlő-e, azaz ugyanazt a szélesség- és magasság-érték párost képviseli. |
| **float** [get_Height](./get_height/)() const | Visszaadja a jelenlegi objektum által képviselt magasság értékét. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Megállapítja, hogy a szélesség és magasság értékei egyaránt 0-e. |
| **float** [get_Width](./get_width/)() const | Visszaadja a jelenlegi objektum által képviselt szélesség értékét. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumhoz. |
| [operator PointF](./operator_pointf/)() const | Átalakítja a jelenlegi objektumot egy [Point](../point/) objektumpéldánnyá, az X és Y koordinátákat a jelenlegi objektum szélesség- és magasság-értékeivel kezdeti értékként beállítva. |
| [SizeF](./)\& [operator+=](./operator_plus_equal/)(const [SizeF](./)\&) | Hozzáadja a megadott [SizeF](./) objektum szélesség- és magasság-értékeit a jelenlegi [SizeF](./) objektum szélesség- és magasság-értékeihez ennek megfelelően. |
| void [set_Height](./set_height/)(**float**) | Beállítja a jelenlegi objektum által képviselt magasság értékét. |
| void [set_Width](./set_width/)(**float**) | Beállítja a jelenlegi objektum által képviselt szélesség értékét. |
| [SizeF](./sizef/)() | Létrehoz egy új [SizeF](./) objektumot, és a szélesség- és magasság-értékeket 0-ra állítja. |
| [SizeF](./sizef/)(const [PointF](../pointf/)\&) | Létrehoz egy új [SizeF](./) objektumot, és a szélesség- és magasság-értékeket a megadott pont X és Y koordinátáival inicializálja. |
| [SizeF](./sizef/)(**float**, **float**) | Létrehoz egy új [SizeF](./) objektumot, és a megadott értékekkel inicializálja. |
| static [SizeF](./) [Subtract](./subtract/)(const [SizeF](./)\&, const [SizeF](./)\&) | Visszaad egy új [SizeF](./) objektumot, amely a **size1** és **size2** kivonásának eredménye, azaz szélességértéke **size1** szélességéből **size2** szélességének kivonásával, és magasságértéke **size1** magasságából **size2** magasságának kivonásával keletkezik. |
| [PointF](../pointf/) [ToPointF](./topointf/)() const | Átalakítja a jelenlegi objektumot egy [Point](../point/) objektumpéldánnyá, az X és Y koordinátákat a jelenlegi objektum szélesség- és magasság-értékeivel beállítva. |
| [Size](../size/) [ToSize](./tosize/)() const | Létrehoz egy [Size](../size/) objektumot a jelenlegi [SizeF](./) objektumból, a [SizeF](./) objektum szélesség- és magasság-értékeit lefelé kerekítve a legközelebbi egész értékekre. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Visszaadja a jelenlegi objektum által képviselt szélesség- és magasság-érték páros sztring reprezentációját. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Empty](./empty/) | Egy üres [SizeF](./) osztálypéldány, amelynek szélesség- és magasság-értékei 0. |

## Lásd még

* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)