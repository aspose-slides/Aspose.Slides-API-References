---
title: Format()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een tekenreeksrepresentatie van een waarde die wordt weergegeven door het huidige object met behulp van het opgegeven formaat.
type: docs
weight: 1
url: /nl/system/icustomformatter/format/
---
## ICustomFormatter::Format(System::String, System::SharedPtr\<System::Object\>, System::SharedPtr\<System::IFormatProvider\>) method

Retourneert een tekenreeksrepresentatie van een waarde die wordt weergegeven door het huidige object met behulp van het opgegeven formaat.

```cpp
virtual System::String System::ICustomFormatter::Format(System::String format, System::SharedPtr<System::Object> arg, System::SharedPtr<System::IFormatProvider> formatProvider)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | [System::String](../../string/) | Het tekenreeksformaat |
| arg | [System::SharedPtr](../../sharedptr/)\<[System::Object](../../object/)\> | Het te formatteren object |
| formatProvider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Het object dat de formatteringsinformatie levert |

### Retourwaarde

De tekenreeksrepresentatie van **arg** geformatteerd volgens het formaat gespecificeerd door **format** en **formatProvider**

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Object](../../object/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [ICustomFormatter](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)