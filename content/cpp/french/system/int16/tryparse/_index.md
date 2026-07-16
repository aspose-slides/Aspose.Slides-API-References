---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre en l'entier signé sur 16 bits équivalent.
type: docs
weight: 14
url: /fr/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier signé sur 16 bits équivalent.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| result | **int16_t**\& | La référence vers une variable d’entier signé sur 16 bits où le résultat de la conversion est placé. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier signé sur 16 bits équivalent en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation textuelle d’un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne. |
| result | **int16_t**\& | La référence vers une variable d’entier signé sur 16 bits où le résultat de la conversion est placé. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) méthode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) méthode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) méthode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)