---
title: EnumValues
second_title: Aspose.Slides C++ API referenciája
description: Meta információkat biztosít az E enum típusú enumerációs állandókról.
type: docs
weight: 794
url: /hu/system/enumvalues/
---
## EnumValues osztály

Metaadatokat biztosít az **E** enum típusú enumerációs konstansokról.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| E | Az enumeráció típusa |

## Módszerek

| Módszer | Leírás |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Példányt hoz létre. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Visszaad egy tömböt, amely az **E** enumeráció összes nevét tartalmazza. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Visszaad egy tömböt, amely a megadott enumeráció állandóinak nevét tartalmazza. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Visszaad a megadott enumeráció alapjául szolgáló típust. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Visszaad a megadott enumeráció alapjául szolgáló típust. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Visszaad egy dobozolt értéket a megadott névvel rendelkező enum állandóhoz. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Visszaad egy dobozolt értéket a megadott értékkel rendelkező enum állandóhoz. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Visszaad egy tömböt, amely az **E** enumeráció összes értékét tartalmazza. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Visszaad egy tömböt, amely a megadott enumerációtípus összes értékét tartalmazza. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Visszaad egy objektumot, amely a megadott névvel rendelkező, a megadott enumerációtípusú enumerációs állandó értékét reprezentálja. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Átalakítja a megadott 64-bitű előjel nélküli egész értéket egy enumerációs elemre. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Átalakítja a megadott egész értékkel rendelkező objektumot egy enumerációs elemre. |
| virtual  [~EnumValues](./~enumvalues/)() | Megsemmisítő. |

## Lásd még

* Osztály [EnumValuesBase](../enumvaluesbase/)
* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)