---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier non signé 32 bits équivalent.
type: docs
weight: 14
url: /fr/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier non signé 32 bits équivalent.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| result | **uint32_t**\& | La référence à une variable entier non signé 32 bits où le résultat de la conversion est placé. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en l’entier non signé 32 bits équivalent en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation textuelle d’un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de la chaîne. |
| result | **uint32_t**\& | La référence à une variable entier non signé 32 bits où le résultat de la conversion est placé. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) méthode




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) méthode




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) méthode




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Structure [UInt32](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)