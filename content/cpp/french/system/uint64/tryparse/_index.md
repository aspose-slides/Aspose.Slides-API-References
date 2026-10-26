---
title: TryParse()
second_title: Référence API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier non signé 64 bits équivalent.
type: docs
weight: 14
url: /fr/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) method

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier non signé 64 bits équivalent.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| result | **uint64_t**\& | La référence à une variable entier non signé 64 bits où le résultat de la conversion est placé. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) method

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier non signé 64 bits équivalent en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs de l'énumération NumberStyles qui spécifie le style autorisé de la représentation sous forme de chaîne d'un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne. |
| result | **uint64_t**\& | La référence à une variable entier non signé 64 bits où le résultat de la conversion est placé. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) method




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Voir aussi

* Énumération [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Structure [UInt64](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)