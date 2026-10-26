---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente Decimal waarde.
type: docs
weight: 482
url: /nl/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente [Decimal](../) waarde.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string |
| result | [Decimal](../)\& | De referentie naar een [Decimal](../) variabele waarin het resultaat van de conversie wordt geplaatst |

### Retourwaarde

True if the conversion succeeded, otherwise - false

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente [Decimal](../) waarde met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren string |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise combinatie van waarden van de enum NumberStyles die de toegestane stijl van de stringrepresentatie van een getal specificeert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de stringopmaakinformatie bevat |
| result | [Decimal](../)\& | Een uitvoerargument; bevat het resultaat van de conversie |

### Retourwaarde

True if the conversion succeeded, otherwise - false

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [Decimal](../)
* Klasse [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)