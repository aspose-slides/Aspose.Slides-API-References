---
title: TryParse()
second_title: Aspose.Slides for C++ API Referentie
description: Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige single-precision zwevend-kommagetalwaarde.
type: docs
weight: 14
url: /nl/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige single-precision zwevend-kommagetalwaarde.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |
| result | **float**\& | De referentie naar een single-precision zwevend-kommagetalvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True if the conversion succeeded, otherwise - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) methode


Converteert de opgegeven string die de tekenreeksrepresentatie van een getal bevat naar de overeenkomstige single-precision zwevend-kommagetalwaarde met behulp van de opgegeven opmaak- en getal-stijlinformatie.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De string om te converteren. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitwise-combinatie van waarden van de NumberStyles-enum die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeks-opmaakinformatie bevat. |
| result | **float**\& | De referentie naar een single-precision zwevend-kommagetalvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True if the conversion succeeded, otherwise - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) methode




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) methode




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) methode




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)