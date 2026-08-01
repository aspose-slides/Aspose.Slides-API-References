---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente double-precision floating-pointwaarde.
type: docs
weight: 14
url: /nl/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) method

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente double-precision floating-pointwaarde.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |
| result | **double**\& | De referentie naar een double-precision floating-pointvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie slaagde, anders - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) method

Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de equivalente double-precision floating-pointwaarde met behulp van de opgegeven opmaakinformatie en getalstijl.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaak-informatie bevat. |
| result | **double**\& | De referentie naar een double-precision floating-pointvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True als de conversie slaagde, anders - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)