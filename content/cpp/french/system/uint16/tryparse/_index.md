---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre en l'entier non signé sur 16 bits équivalent.
type: docs
weight: 14
url: /fr/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier non signé sur 16 bits équivalent.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| result | **uint16_t**\& | La référence à une variable d’entier non signé sur 16 bits où le résultat de la conversion est placé. |

### Return Value

Vrai si la conversion a réussi, sinon - faux.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier non signé sur 16 bits équivalent en utilisant les informations de formatage et le style numérique fournis.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation textuelle d’un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne. |
| result | **uint16_t**\& | La référence à une variable d’entier non signé sur 16 bits où le résultat de la conversion est placé. |

### Return Value

Vrai si la conversion a réussi, sinon - faux.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) méthode




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) méthode




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) méthode




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)