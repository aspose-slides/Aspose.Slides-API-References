---
title: EnumValuesBase
second_title: Aspose.Slides voor C++ API-referentie
description: Een basisklasse voor een klasse die meta-informatie van een enumeratietype weergeeft.
type: docs
weight: 807
url: /nl/system/enumvaluesbase/
---
## EnumValuesBase klasse

Een basisklasse voor een klasse die meta-informatie van een enumeratietype weergeeft.

```cpp
class EnumValuesBase
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Haalt een array op van de namen van de constanten in een opgegeven enumeratie. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Retourneert het onderliggende type van de opgegeven enumeratie. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Retourneert een array met alle waarden van het opgegeven enumeratietype. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Retourneert een object dat een waarde van een enumeratie-constante van het opgegeven enumeratietype vertegenwoordigt met de opgegeven naam. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Converteert de opgegeven 64-bit unsigned integer-waarde naar een enumeratielid. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Converteert het opgegeven object met een gehele-waarde naar een enumeratielid. |

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)