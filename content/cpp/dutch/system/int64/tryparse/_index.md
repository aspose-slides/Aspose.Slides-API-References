---
title: TryParse()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 64-bits ondertekende gehele getal.
type: docs
weight: 14
url: /nl/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) method


Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 64-bits ondertekende gehele getal.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |
| result | **int64_t**\& | De referentie naar een 64-bits ondertekende geheel-getalvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True if the conversion succeeded, otherwise - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) method


Converteert de opgegeven tekenreeks die de tekenreeksrepresentatie van een getal bevat naar het overeenkomstige 64-bits ondertekende gehele getal met behulp van de meegeleverde opmaakinformatie en getalstijl.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../string/)\& | De te converteren tekenreeks. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Een bitgewijze combinatie van waarden van de enum NumberStyles die de toegestane stijl van de tekenreeksrepresentatie van een getal specificeert. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Een pointer naar een object dat de tekenreeksopmaakinformatie bevat. |
| result | **int64_t**\& | De referentie naar een 64-bits ondertekende geheel-getalvariabele waarin het resultaat van de conversie wordt geplaatst. |

### Retourwaarde

True if the conversion succeeded, otherwise - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) method




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Zie ook

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)