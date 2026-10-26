---
title: Index
second_title: Aspose.Slides C++ API hivatkozás
description: "Egy gyűjteményben lévő indexet képviseli. Az index lehet az elejétől vagy a végétől számítva. Ezt a típust a veremben kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ennek a típusnak az objektumainak kezelésére."
type: docs
weight: 1015
url: /hu/system/index/
---
## Index osztály

Egy gyűjteményben lévő indexet képviseli. Az index lehet az elejétől vagy a végétől számítva. Ezt a típust a veremben kell lefoglalni, és értékkel vagy referenciával átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../smartptr/) osztályt ennek a típusnak az objektumainak kezelésére.

```cpp
class Index : public System::Details::BoxableObjectBase
```

## Módszerek

| Metódus | Leírás |
| --- | --- |
| **bool** [Equals](./equals/)(const [Index](./)\&) const | Megállapítja, hogy a jelenlegi példány és a megadott [Index](./) ugyanazt a pozíciót képviseli-e. |
| static constexpr [Index](./) [FromEnd](./fromend/)(**int32_t**) | Létrehoz egy [Index](./) objektumot, amely a gyűjtemény végéhez relatív. |
| static constexpr [Index](./) [get_End](./get_end/)() | Lekéri egy [Index](./) objektumot, amely a gyűjtemény végét képviseli. |
| constexpr **bool** [get_IsFromEnd](./get_isfromend/)() const | Lekér egy értéket, amely jelzi, hogy az index a végéről származik-e. |
| static constexpr [Index](./) [get_Start](./get_start/)() | Lekér egy [Index](./) objektumot, amely a gyűjtemény elejét képviseli. |
| constexpr **int32_t** [get_Value](./get_value/)() const | Lekéri az index értékét. |
| **int32_t** [GetHashCode](./gethashcode/)() const | Visszaad egy hash kódot a jelenlegi indexhez. |
| **int32_t** [GetOffset](./getoffset/)(**int32_t**) const | Átalakítja a jelenlegi [Index](./)-t egy eltolással a megadott hosszúságú gyűjtemény elejétől számítva. |
| constexpr [Index](./index/)() | Létrehoz egy példányt, amely a gyűjtemény elejét képviseli. |
| constexpr [Index](./index/)(**int32_t**) | Létrehoz egy példányt, amely a gyűjtemény elejétől számított megadott pozíciót képviseli. |
| constexpr [Index](./index/)(**int32_t**, **bool**) | Létrehoz egy példányt, amely a megadott indexet képviseli. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)