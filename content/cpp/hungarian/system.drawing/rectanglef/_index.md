---
title: RectangleF
second_title: Aspose.Slides C++ API Referenciája
description: "Ábrázolja egy kép téglalap alakú területét, amely a bal felső sarok X és Y egyszeres pontosságú lebegőpontos koordinátáival, valamint a szélességével és magasságával van definiálva. Ez a típus a stack-en kell, hogy legyen lefoglalva, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 248
url: /hu/system.drawing/rectanglef/
---
## RectangleF osztály


Ábrázolja egy képen a bal felső sarok X és Y egypontozott, egyszeres pontosságú lebegőpontos koordinátáival, valamint szélességét és magasságát meghatározó téglalapnyi területet. Ez a típus a stack-en kell, hogy legyen lefoglalva, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a(z) [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class RectangleF
```

## Metódusok

| Method | Description |
| --- | --- |
| **bool** [Contains](./contains/)(**float**, **float**) | Megállapítja, hogy a megadott pont a jelen objektum által képviselt téglalapon belül helyezkedik-e. |
| **bool** [Contains](./contains/)(const [PointF](../pointf/)\&) | Megállapítja, hogy a megadott pont a jelen objektum által képviselt téglalapon belül helyezkedik-e. |
| **bool** [Contains](./contains/)(const [RectangleF](./)\&) | Megállapítja, hogy a megadott téglalap a jelen objektum által képviselt téglalapon belül helyezkedik-e. |
| **bool** [Equals](./equals/)(const [RectangleF](./)\&) const | Megállapítja, hogy a jelen és a megadott objektumok által képviselt téglalapok azonosak-e. |
| static [RectangleF](./) [FromLTRB](./fromltrb/)(**float**, **float**, **float**, **float**) | Létrehoz egy új [RectangleF](./) objektumot, amely a megadott élhelyzetekkel rendelkező téglalapot képviseli. |
| **float** [get_Bottom](./get_bottom/)() const | Visszaadja a jelen objektum által képviselt téglalap alsó élének y koordinátáját. |
| **float** [get_Height](./get_height/)() const | Visszaadja a jelen objektum által képviselt téglalap magasságát. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Megállapítja, hogy a jelen objektum által képviselt téglalap bal felső sarkának X és Y koordinátái, valamint szélessége és magassága 0 értéket tartalmaznak-e. |
| **float** [get_Left](./get_left/)() const | Visszaadja a jelen objektum által képviselt téglalap bal élének X koordinátáját. |
| [PointF](../pointf/) [get_Location](./get_location/)() const | Visszaad egy példányt a [PointF](../pointf/) osztályból, amely a jelen objektum által képviselt téglalap bal felső sarkának helyzetét adja meg. |
| **float** [get_Right](./get_right/)() const | Visszaadja a jelen objektum által képviselt téglalap jobb élének X koordinátáját. |
| [SizeF](../sizef/) [get_Size](./get_size/)() const | Visszaad egy példányt a [SizeF](../sizef/) osztályból, amely a jelen objektum által képviselt téglalap szélességét és magasságát adja meg. |
| **float** [get_Top](./get_top/)() const | Visszaadja a jelen objektum által képviselt téglalap felső élének Y koordinátáját. |
| **float** [get_Width](./get_width/)() const | Visszaadja a jelen objektum által képviselt téglalap szélességét. |
| **float** [get_X](./get_x/)() const | Visszaadja a jelen objektum által képviselt téglalap bal felső sarkának X koordinátáját. |
| **float** [get_Y](./get_y/)() const | Visszaadja a jelen objektum által képviselt téglalap bal felső sarkának Y koordinátáját. |
| int [GetHashCode](./gethashcode/)() const | Visszaadja a jelen objektum hash kódját. |
| void [Inflate](./inflate/)(**float**, **float**) | Növeli a jelen objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a téglalap geometriai középpontjának helyzetét. A szélesség és magasság mindkét irányban a megadott értékekkel növekszik. |
| void [Inflate](./inflate/)(const [SizeF](../sizef/)\&) | Növeli a jelen objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a geometriai középpont helyzetét. A szélesség és magasság mindkét irányban a megadott méretobjektum szélesség- és magasságértékei szerint növekszik. |
| static [RectangleF](./) [Inflate](./inflate/)(const [RectangleF](./)\&, **float**, **float**) | Növeli a megadott objektum által képviselt téglalap szélességét és magasságát, miközben megőrzi a geometriai középpont helyzetét. A szélesség és magasság mindkét irányban a megadott értékekkel növekszik. |
| void [Intersect](./intersect/)(const [RectangleF](./)\&) | A jelen objektum által képviselt téglalapot a megadott objektummal való metszet eredményeként kapott téglalappal helyettesíti. |
| static [RectangleF](./) [Intersect](./intersect/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Visszaad egy téglalapot, amely a megadott téglalapok metszete. |
| **bool** [IntersectsWith](./intersectswith/)(const [RectangleF](./)\&) | Megállapítja, hogy a jelen és a megadott objektumok által képviselt téglalapok metszenek-e. |
| void [Offset](./offset/)(const [PointF](../pointf/)\&) | Eltolja a jelen objektum által képviselt téglalap pozícióját a megadott értékekkel. |
| void [Offset](./offset/)(**float**, **float**) | Eltolja a jelen objektum által képviselt téglalap pozícióját a megadott értékekkel. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Mindig true értéket ad. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Mindig false értéket ad. |
|  [RectangleF](./rectanglef/)() | Létrehoz egy új [RectangleF](./) objektumpéldányt, amely 0 értékű X és Y koordinátákkal, valamint szélesség- és magasságértékekkel rendelkező téglalapot képvisel. |
|  [RectangleF](./rectanglef/)(**float**, **float**, **float**, **float**) | Létrehoz egy új [RectangleF](./) objektumpéldányt, amely a megadott bal felső sarok koordinátáival, valamint szélességgel és magassággal rendelkező téglalapot képvisel. |
|  [RectangleF](./rectanglef/)(const [PointF](../pointf/)\&, const [SizeF](../sizef/)\&) | Létrehoz egy új [RectangleF](./) objektumpéldányt, amely a bal felső sarok koordinátáit a [PointF](../pointf/) osztály példányaként, szélességét és magasságát pedig a [SizeF](../sizef/) osztály példányaként adja meg. |
| explicit  [RectangleF](./rectanglef/)(const [Rectangle](../rectangle/)\&) | Létrehoz egy új [RectangleF](./) objektumpéldányt, amely a megadott téglalappal egyenértékű téglalapot képvisel. |
| void [set_Height](./set_height/)(**float**) | Beállítja a jelen objektum által képviselt téglalap magasságát. |
| void [set_Location](./set_location/)([PointF](../pointf/)) | Beállítja a jelen objektum által képviselt téglalap bal felső sarkának helyzetét. |
| void [set_Size](./set_size/)([SizeF](../sizef/)) | Beállítja a jelen objektum által képviselt téglalap szélességét és magasságát. |
| void [set_Width](./set_width/)(**float**) | Beállítja a jelen objektum által képviselt téglalap szélességét. |
| void [set_X](./set_x/)(**float**) | Beállítja a jelen objektum által képviselt téglalap bal felső sarkának X koordinátáját. |
| void [set_Y](./set_y/)(**float**) | Beállítja a jelen objektum által képviselt téglalap bal felső sarkának Y koordinátáját. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Visszaadja a jelen objektum szöveges reprezentációját. |
| static [RectangleF](./) [Union](./union/)(const [RectangleF](./)\&, const [RectangleF](./)\&) | Visszaad egy téglalapot, amely a megadott téglalapok uniójának eredménye. |

## Mezők

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Egy üres téglalap, vagyis egy téglalap, melynek hely- és méretértékei nulla. |

## Lásd még

* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)