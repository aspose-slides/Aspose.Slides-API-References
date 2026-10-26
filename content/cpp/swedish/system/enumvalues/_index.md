---
title: EnumValues
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller meta-information om uppräkningens konstanter av enum-typen E.
type: docs
weight: 794
url: /sv/system/enumvalues/
---
## EnumValues klass

Tillhandahåller meta-information om uppräkningens konstanter av enum-typ **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| E | The type of enumeration |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Skapar en instans. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Returnerar en array som innehåller alla namn i uppräkningen **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Hämtar en array med namn på konstanterna i en specificerad uppräkning. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Returnerar den underliggande typen för den specificerade uppräkningen. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Returnerar den underliggande typen för den specificerade uppräkningen. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Returnerar ett inneslutet (boxat) värde för enum-konstanten med det specificerade namnet. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Returnerar ett inneslutet (boxat) värde för enum-konstanten med det specificerade värdet. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Returnerar en array som innehåller alla värden i uppräkningen **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Returnerar en array som innehåller alla värden för den specificerade uppräkningstypen. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Returnerar ett objekt som representerar ett värde av enum-konstanten för den specificerade uppräkningstypen med det specificerade namnet. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Konverterar det specificerade 64-bits osignerade heltalsvärdet till en uppräkningens medlem. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Konverterar det specificerade objektet med ett heltalsvärde till en uppräkningens medlem. |
| virtual  [~EnumValues](./~enumvalues/)() | Destruktor. |

## Se även

* Klass [EnumValuesBase](../enumvaluesbase/)
* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)