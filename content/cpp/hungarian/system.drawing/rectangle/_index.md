---
title: Rectangle
second_title: Aspose.Slides C++ API referencia
description: "Representál egy képen lévő téglalap területet, amelyet a bal felső sarok egész X és Y koordinátái, valamint a szélessége és magassága határoz meg. Ez a típus a stack-en kell legyen lefoglalva, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 235
url: /hu/system.drawing/rectangle/
---
## Rectangle osztály


Representál egy képen lévő téglalap területet, amelyet az előülő bal sarok egész X és Y koordinátái, valamint a szélessége és magassága határoz meg. Ez a típus a stack-en kell legyen lefoglalva, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a(z) [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class Rectangle
```

## Metódusok

| Method | Description |
| --- | --- |
| static [Rectangle](./) [Ceiling](./ceiling/)(const [RectangleF](../rectanglef/)\&) | Létrehozza a(z) [Rectangle](./) objektumot a megadott [RectangleF](../rectanglef/) objektumból, a [RectangleF](../rectanglef/) objektum hely- és méretértékeit a következő magasabb egész számra kerekítve. |
| **bool** [Contains](./contains/)(int, int) const | Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt téglalapon belül helyezkedik-e el. |
| **bool** [Contains](./contains/)(const [Point](../point/)\&) const | Megállapítja, hogy a megadott pont a jelenlegi objektum által képviselt téglalapon belül helyezkedik-e el. |
| **bool** [Contains](./contains/)(const [Rectangle](./)\&) const | Megállapítja, hogy a megadott téglalap a jelenlegi objektum által képviselt téglalapon belül helyezkedik-e el. |
| **bool** [Equals](./equals/)(const [Rectangle](./)\&) const | Megállapítja, hogy a jelenlegi és a megadott objektumok által képviselt téglalapok azonosak-e. |
| static [Rectangle](./) [FromLTRB](./fromltrb/)(int, int, int, int) | Létrehozza az új [Rectangle](./) objektumot, amely a megadott élhelyzetekkel rendelkező téglalapot képviseli. |
| int [get_Bottom](./get_bottom/)() const | Visszaadja a téglalap alsó szélének y koordinátáját, amelyet a jelenlegi objektum képvisel. |
| int [get_Height](./get_height/)() const | Visszaadja a téglalap magasságát, amelyet a jelenlegi objektum képvisel. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Megállapítja, hogy a téglalap bal felső sarkának X és Y koordinátái, valamint a szélessége és magassága 0 értékre vannak-e állítva. |
| int [get_Left](./get_left/)() const | Visszaadja a téglalap bal szélének X koordinátáját, amelyet a jelenlegi objektum képvisel. |
| [Point](../point/) [get_Location](./get_location/)() const | Visszaad egy [Point](../point/) osztályú példányt, amely a téglalap bal felső sarkának helyét adja meg. |
| int [get_Right](./get_right/)() const | Visszaadja a téglalap jobb szélének X koordinátáját, amelyet a jelenlegi objektum képvisel. |
| [Size](../size/) [get_Size](./get_size/)() const | Visszaad egy [Size](../size/) osztályú példányt, amely a téglalap szélességét és magasságát adja meg. |
| int [get_Top](./get_top/)() const | Visszaadja a téglalap felső szélének Y koordinátáját, amelyet a jelenlegi objektum képvisel. |
| int [get_Width](./get_width/)() const | Visszaadja a téglalap szélességét, amelyet a jelenlegi objektum képvisel. |
| int [get_X](./get_x/)() const | Visszaadja a téglalap bal felső sarkának X koordinátáját, amelyet a jelenlegi objektum képvisel. |
| int [get_Y](./get_y/)() const | Visszaadja a téglalap bal felső sarkának Y koordinátáját, amelyet a jelenlegi objektum képvisel. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi objektumról. |
| void [Inflate](./inflate/)(int, int) | Megnöveli a téglalap szélességét és magasságát, miközben megtartja a téglalap geometriai középpontjának helyét. A szélesség és magasság a megadott értékekkel mindkét irányban növekszik. |
| void [Inflate](./inflate/)(const [Size](../size/)\&) | Megnöveli a téglalap szélességét és magasságát, miközben megtartja a téglalap geometriai középpontjának helyét. A szélesség és magasság a megadott méretobjektum szélesség- és magasságértékeivel nőnek megfelelően. |
| static [Rectangle](./) [Inflate](./inflate/)(const [Rectangle](./)\&, int, int) | Megnöveli a megadott objektum által képviselt téglalap szélességét és magasságát, miközben megtartja a geometriai középpont helyét. A szélesség és magasság a megadott értékekkel növekszik. |
| void [Intersect](./intersect/)(const [Rectangle](./)\&) | Lecseréli a jelenlegi objektum által képviselt téglalapot arra a téglalapra, amely a megadott objektummal való metszetének eredménye. |
| static [Rectangle](./) [Intersect](./intersect/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Visszaad egy téglalapot, amely a megadott téglalapok metszetének eredménye. |
| **bool** [IntersectsWith](./intersectswith/)(const [Rectangle](./)\&) | Megállapítja, hogy a jelenlegi és a megadott objektumok által képviselt téglalapok átfednek-e. |
| void [Offset](./offset/)(const [Point](../point/)\&) | Eltolja a téglalap pozícióját a megadott értékekkel. |
| void [Offset](./offset/)(int, int) | Eltolja a téglalap pozícióját a megadott értékekkel. |
|  [operator RectangleF](./operator_rectanglef/)() const | Visszaad egy [RectangleF](../rectanglef/) objektumot, amely egy a jelenlegi objektum által képviselt téglalappal egyenértékű téglalapot képvisel. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Mindig igazat ad vissza. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Mindig hamisat ad vissza. |
|  [Rectangle](./rectangle/)() | Visszaad egy új [Rectangle](./) objektumot, amely egy X és Y koordinátákkal, valamint szélességgel és magassággal 0 értékű téglalapot képvisel. |
|  [Rectangle](./rectangle/)(int, int, int, int) | Létrehozza az új [Rectangle](./) objektumot, amely a bal felső sarok megadott koordinátáival, valamint a szélesség és magasság értékeivel rendelkező téglalapot képviseli. |
|  [Rectangle](./rectangle/)(const [Point](../point/)\&, const [Size](../size/)\&) | Létrehozza az új [Rectangle](./) objektumot, amely a bal felső sarok koordinátáit [Point](../point/) osztályú példányként, a szélességet és magasságot pedig [Size](../size/) osztályú példányként adja meg. |
|  [Rectangle](./rectangle/)(const **System::Windows::Forms::Screen::Rectangle_**\&) | Létrehozza az új [Rectangle](./) objektumot, amely a megadott téglalappal egyenértékű téglalapot képvisel. |
| static [Rectangle](./) [Round](./round/)(const [RectangleF](../rectanglef/)\&) | Létrehozza egy [Rectangle](./) objektumot a megadott [RectangleF](../rectanglef/) objektumból, a [RectangleF](../rectanglef/) objektum hely- és méretértékeit a legközelebbi egész számra kerekítve. |
| void [set_Height](./set_height/)(int) | Beállítja a jelenlegi objektum által képviselt téglalap magasságát. |
| void [set_Location](./set_location/)([Point](../point/)) | Beállítja a jelenlegi objektum által képviselt téglalap bal felső sarkának helyét. |
| void [set_Size](./set_size/)([Size](../size/)) | Beállítja a jelenlegi objektum által képviselt téglalap szélességét és magasságát. |
| void [set_Width](./set_width/)(int) | Beállítja a jelenlegi objektum által képviselt téglalap szélességét. |
| void [set_X](./set_x/)(int) | Beállítja a jelenlegi objektum által képviselt téglalap bal felső sarkának X koordinátáját. |
| void [set_Y](./set_y/)(int) | Beállítja a jelenlegi objektum által képviselt téglalap bal felső sarkának Y koordinátáját. |
| [String](../../system/string/) [ToString](./tostring/)() const | Visszaadja a jelenlegi objektum karakterlánc ábrázolását. |
| static [Rectangle](./) [Truncate](./truncate/)(const [RectangleF](../rectanglef/)\&) | Létrehozza egy [Rectangle](./) objektumot a megadott [RectangleF](../rectanglef/) objektumból, a [RectangleF](../rectanglef/) objektum hely- és méretértékeit a következő alacsonyabb egész számra csonkolva. |
| static [Rectangle](./) [Union](./union/)(const [Rectangle](./)\&, const [Rectangle](./)\&) | Visszaad egy téglalapot, amely a megadott téglalapok uniójának eredménye. |

## Mezők

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Egy üres téglalap, azaz egy olyan téglalap, amelynek hely- és méretértékei nulla. |

## Lásd még

* Névtere [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)