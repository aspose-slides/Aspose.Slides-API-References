---
title: TryParse()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den angivna strängen som innehåller en nummerrepresentation till motsvarande Decimal-värde.
type: docs
weight: 482
url: /sv/system/decimal/tryparse/
---
## Decimal::TryParse(const String\&, Decimal\&) metod


Konverterar den angivna strängen som innehåller nummerrepresentationen till motsvarande [Decimal](../) värde.

```cpp
static bool System::Decimal::TryParse(const String &value, Decimal &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som skall konverteras |
| result | [Decimal](../)\& | Referensen till en [Decimal](../)-variabel där resultatet av konverteringen placeras |

### Returvärde

Sant om konverteringen lyckades, annars - falskt

## Decimal::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, Decimal\&) metod


Konverterar den angivna strängen som innehåller nummerrepresentationen till motsvarande [Decimal](../) värde med den angivna formateringsinformationen och nummerstilen.

```cpp
static bool System::Decimal::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, Decimal &result)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | Strängen som skall konverteras |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | En bitvis kombination av värden i NumberStyles-enumerationen som anger den tillåtna stilen för nummerrepresentationen |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | En pekare till ett objekt som innehåller information om strängformatet |
| result | [Decimal](../)\& | Ett utskriftsargument; innehåller resultatet av konverteringen |

### Returvärde

Sant om konverteringen lyckades, annars - falskt

## Se även

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Decimal](../)
* Class [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)