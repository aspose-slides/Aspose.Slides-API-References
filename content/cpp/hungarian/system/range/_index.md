---
title: Range
second_title: Aspose.Slides C++ API referenciája
description: "Egy tartományt reprezentál, amelynek van kezdő és befejező indexe. Ezt a típust a stacken kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak a példányainak kezelésére."
type: docs
weight: 1197
url: /hu/system/range/
---
## Range osztály

Reprezentál egy tartományt, amelynek van kezdő és vég indexe. Ezt a típust a stacken kell lefoglalni, és értékkel vagy referenciával átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak a példányainak kezelésére.

```cpp
class Range : public System::Details::BoxableObjectBase
```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| static constexpr [Range](./) [EndAt](./endat/)(const [Index](../index/)\&) | Létrehoz egy tartományt, amely a gyűjtemény elején kezdődik és a megadott befejező indexnél ér véget. |
| **bool** [Equals](./equals/)(const [Range](./)\&) const | Megállapítja, hogy a jelenlegi tartomány egyenlő-e a megadott tartománnyal. |
| static constexpr [Range](./) [get_All](./get_all/)() | Visszaad egy [Range](./) objektumot, amely a teljes gyűjteményt képviseli. |
| const [Index](../index/)\& [get_End](./get_end/)() const | Lekéri a vég indexet. |
| const [Index](../index/)\& [get_Start](./get_start/)() const | Lekéri a kezdő indexet. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi tartományhoz. |
| [System::ValueTuple](../valuetuple/)\<**int32_t**, **int32_t**\> [GetOffsetAndLength](./getoffsetandlength/)(**int32_t**) const | Kiszámítja a nulláktól kezdődő kezdőeltolást és a hosszt a megadott gyűjtemény hosszához. |
| constexpr [Range](./range/)() | Létrehoz egy üres tartományt. |
| constexpr [Range](./range/)(const [Index](../index/)\&, const [Index](../index/)\&) | Létrehoz egy [Range](./) objektumot a megadott kezdő és befejező indexekből. |
| static constexpr [Range](./) [StartAt](./startat/)(const [Index](../index/)\&) | Létrehoz egy tartományt, amely a megadott kezdő indexnél kezdődik és a gyűjtemény végéig tart. |
## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)