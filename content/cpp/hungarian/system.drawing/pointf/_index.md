---
title: PointF
second_title: Aspose.Slides C++ API hivatkozás
description: "Representál egy párost egypontos lebegőpontos X és Y koordinátákat egy 2-dimenziós síkon lévő pont esetén. Ezt a típust a veremben kell lefoglalni, és értékként vagy referenciaként átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 222
url: /hu/system.drawing/pointf/
---
## PointF osztály

Egy egypontos, lebegőpontos X és Y koordinátapárt képvisel egy kétdimenziós síkon lévő pont esetén. Ezt a típust a veremben kell lefoglalni, és értékként vagy referenciaként átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class PointF
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Hozzáadja a megadott [SizeF](../sizef/) objektum szélesség- és magasságértékeit a megadott [PointF](./) objektum X és Y koordinátához megfelelően. |
| static [PointF](./) [Add](./add/)(const [PointF](./)\&, const [Size](../size/)\&) | Hozzáadja a megadott [Size](../size/) objektum szélesség- és magasságértékeit a megadott [PointF](./) objektum X és Y koordinátához megfelelően. |
| **bool** [Equals](./equals/)(const [PointF](./)\&) const | Meghatározza, hogy a jelenlegi objektum és a megadott objektum egyenlő-e, azaz ugyanazt az X és Y koordinátapárt képviseli-e. |
| **bool** [get_IsEmpty](./get_isempty/)() const | Meghatározza, hogy mind az X, mind a Y koordináta értéke 0-e. |
| **float** [get_X](./get_x/)() const | Visszaadja a jelenlegi objektum által képviselt X koordináta értékét. |
| **float** [get_Y](./get_y/)() const | Visszaadja a jelenlegi objektum által képviselt Y koordináta értékét. |
| int [GetHashCode](./gethashcode/)() const | Visszaad egy hash-kódot a jelenlegi objektumhoz. |
| **bool** [IsNull](./isnull/)() const | Mindig hamis értéket ad vissza. |
| explicit  [operator bool](./operator_bool/)() | Mindig igaz értéket ad vissza. |
|  [PointF](./pointf/)() | Létrehoz egy új [PointF](./) objektumot, és a X és Y koordinátáit 0-ra inicializálja. |
|  [PointF](./pointf/)(**float**, **float**) | Létrehoz egy új [PointF](./) objektumot, és a megadott értékekkel inicializálja. |
|  [PointF](./pointf/)(const [SizeF](../sizef/)\&) | Létrehoz egy új [PointF](./) objektumot, és a X és Y koordinátáit a megadott [SizeF](../sizef/) objektum szélesség- és magasságértékeivel inicializálja. |
| void [set_X](./set_x/)(**float**) | Beállítja a jelenlegi objektum által képviselt X koordináta értékét. |
| void [set_Y](./set_y/)(**float**) | Beállítja a jelenlegi objektum által képviselt Y koordináta értékét. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [SizeF](../sizef/)\&) | Levonja a megadott [SizeF](../sizef/) objektum szélesség- és magasságértékeit a megadott [PointF](./) objektum X és Y koordinátáiból megfelelően. |
| static [PointF](./) [Subtract](./subtract/)(const [PointF](./)\&, const [Size](../size/)\&) | Levonja a megadott [Size](../size/) objektum szélesség- és magasságértékeit a megadott [PointF](./) objektum X és Y koordinátáiból megfelelően. |
| [System::String](../../system/string/) [ToString](./tostring/)() const | Visszaadja a jelenlegi objektum által képviselt X és Y koordinátapár karakterlánc-ábrázolását. |

## Mezők

| Mező | Leírás |
| --- | --- |
| static [Empty](./empty/) | Üres példány a(z) [PointF](./) osztályból, amelynek X és Y koordinátái 0. |

## Lásd még

* Névtér [System::Drawing](../)
* Könyvtár [Aspose.Slides](../../)