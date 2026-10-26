---
title: EnumValuesBase
second_title: Aspose.Slides pro C++ API Reference
description: Základní třída pro třídu, která představuje meta informace typu výčtu.
type: docs
weight: 807
url: /cs/system/enumvaluesbase/
---
## EnumValuesBase třída


Základní třída pro třídu, která představuje meta informace typu výčtu.

```cpp
class EnumValuesBase
```

## Metody

| Metoda | Popis |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Načte pole názvů konstant v určeném výčtu. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Vrací základní typ určeného výčtu. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Vrací pole obsahující všechny hodnoty určeného typu výčtu. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Vrací objekt, který představuje hodnotu konstanty výčtu daného typu výčtu se zadaným názvem. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Převede zadanou 64-bitovou neznačenou celočíselnou hodnotu na člena výčtu. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Převede zadaný objekt s celočíselnou hodnotou na člena výčtu. |
## Viz také

* jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)