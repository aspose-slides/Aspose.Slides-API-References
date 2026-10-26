---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre en l'entier signé 8 bits équivalent.
type: docs
weight: 14
url: /fr/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier signé 8 bits équivalent.

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| result | **int8_t**\& | La référence à une variable d’entier signé 8 bits où le résultat de la conversion est placé. |

### Valeur de retour

true si la conversion a réussi, sinon - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier signé 8 bits équivalent en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation textuelle d’un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne. |
| result | **int8_t**\& | La référence à une variable d’entier signé 8 bits où le résultat de la conversion est placé. |

### Valeur de retour

true si la conversion a réussi, sinon - false.

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) méthode



```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) méthode



```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) méthode



```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Structure [SByte](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)