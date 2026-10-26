---
title: EnumValuesBase
second_title: Aspose.Slides for C++ API Referencia
description: Alap osztály egy olyan osztály számára, amely a felsoroló típus metaadatait reprezentálja.
type: docs
weight: 807
url: /hu/system/enumvaluesbase/
---
## EnumValuesBase osztály


Alap osztály egy olyan osztály számára, amely a felsoroló típus metaadatait reprezentálja.

```cpp
class EnumValuesBase
```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Visszaad egy tömböt a megadott felsorolás állandóinak neveivel. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Visszaadja a megadott felsorolás alaptípusát. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Visszaad egy tömböt, amely a megadott felsorolás típus összes értékét tartalmazza. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Visszaad egy objektumot, amely a megadott névvel és megadott felsorolás típussal rendelkező felsorolásállandó értékét képviseli. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Átalakítja a megadott 64 bites előjel nélküli egész értéket egy felsorolás elemévé. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Átalakítja a megadott egész értékkel rendelkező objektumot egy felsorolás elemévé. |
## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)