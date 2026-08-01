---
title: EnumValues
second_title: Aspose.Slides voor C++ API Referentie
description: Biedt meta-informatie over enumeratieconstanten van enumtype E.
type: docs
weight: 794
url: /nl/system/enumvalues/
---
## EnumValues klasse

Biedt meta-informatie over enumeratieconstanten van enumtype **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| E | Het type van enumeratie |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Construeert een instantie. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Retourneert een array met alle namen van de enumeratie **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Haalt een array op van de namen van de constanten in een opgegeven enumeratie. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Retourneert het onderliggende type van de opgegeven enumeratie. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Retourneert het onderliggende type van de opgegeven enumeratie. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Retourneert de verpakte waarde van de enum-constante met de opgegeven naam. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Retourneert de verpakte waarde van de enum-constante met de opgegeven waarde. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Retourneert een array met alle waarden van de enumeratie **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Retourneert een array met alle waarden van het opgegeven enumeratietype. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Retourneert een object dat een waarde van een enumeratieconstante van het opgegeven enumeratietype met de opgegeven naam vertegenwoordigt. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Converteert de opgegeven 64-bit unsigned integer-waarde naar een enumeratielid. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Converteert het opgegeven object met een gehele getalwaarde naar een enumeratielid. |
| virtual  [~EnumValues](./~enumvalues/)() | Destructor. |

## Zie ook

* Klasse [EnumValuesBase](../enumvaluesbase/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)