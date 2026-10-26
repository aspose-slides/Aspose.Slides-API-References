---
title: EnumValues
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje meta informace o konstantách výčtu typu E.
type: docs
weight: 794
url: /cs/system/enumvalues/
---
## EnumValues třída

Poskytuje metainformace o konstantách výčtu typu **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| E | Typ výčtu |
## Metody

| Metoda | Popis |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Vytvoří instanci. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Vrací pole obsahující všechna jména výčtu **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Načte pole jmen konstant ve specifikovaném výčtu. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Vrací podkladový typ specifikovaného výčtu. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Vrací podkladový typ specifikovaného výčtu. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Vrací zabalenou hodnotu konstanty výčtu se zadaným jménem. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Vrací zabalenou hodnotu konstanty výčtu se zadanou hodnotou. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Vrací pole obsahující všechny hodnoty výčtu **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Vrací pole obsahující všechny hodnoty specifikovaného typu výčtu. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Vrací objekt představující hodnotu konstanty výčtu specifikovaného typu s daným jménem. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Převádí zadanou 64bitovou neznačkovou celočíselnou hodnotu na člena výčtu. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Převádí zadaný objekt s celočíselnou hodnotou na člena výčtu. |
| virtual  [~EnumValues](./~enumvalues/)() | Destruktor. |

## Viz také

* třída [EnumValuesBase](../enumvaluesbase/)
* jmenný prostor [System](../)
* knihovna [Aspose.Slides](../../)