---
title: EnumValuesBase
second_title: Aspose.Slides för C++ API-referens
description: En basklass för en klass som representerar metainformation för en uppräkningstyp.
type: docs
weight: 807
url: /sv/system/enumvaluesbase/
---
## EnumValuesBase klass

En basklass för en klass som representerar metainformation för en uppräkningstyp.

```cpp
class EnumValuesBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Hämtar en array med namnen på konstanterna i en specificerad uppräkning. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Returnerar den underliggande typen för den specificerade uppräkningen. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Returnerar en array som innehåller alla värden för den specificerade uppräkningstypen. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Returnerar ett objekt som representerar ett värde av uppräkningens konstant för den specificerade uppräkningstypen med det angivna namnet. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Konverterar det specificerade 64-bitars osignerade heltalsvärdet till en uppräkningens medlem. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Konverterar det specificerade objektet med ett heltalsvärde till en uppräkningens medlem. |
## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)