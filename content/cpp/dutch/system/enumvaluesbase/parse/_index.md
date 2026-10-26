---
title: Parse()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een object dat een waarde van een enumeratie-constante van het opgegeven enumeratietype met de opgegeven naam vertegenwoordigt.
type: docs
weight: 27
url: /nl/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) methode


Retourneert een object dat een waarde van een enumeratie-constante van het opgegeven enumeratietype met de opgegeven naam vertegenwoordigt.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Het [TypeInfo](../../typeinfo/) object dat het type van de enumeratiewaarde die moet worden geretourneerd weergeeft |
| str | const [String](../../string/)\& | De naam van de enum-constante |
| ignoreCase | **bool** | Specificeert of de hoofdlettergevoeligheid genegeerd moet worden bij het interpreteren van de naam van de enum-constante |

### Retourwaarde

Een object dat de waarde van de enum-constante vertegenwoordigt waarvan de naam is opgegeven in **str**.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Object](../../object/)
* Klasse [TypeInfo](../../typeinfo/)
* Klasse [String](../../string/)
* Klasse [EnumValuesBase](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)