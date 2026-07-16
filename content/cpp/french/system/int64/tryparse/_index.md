---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier signé 64 bits équivalent.
type: docs
weight: 14
url: /fr/system/int64/tryparse/
---
## Int64::TryParse(const String&, int64_t&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier signé 64 bits équivalent.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)& | La chaîne à convertir. |
| result | **int64_t**& | La référence à une variable d'entier signé 64 bits où le résultat de la conversion est placé. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## Int64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&, int64_t&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en l'entier signé 64 bits équivalent en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs de l'énumération NumberStyles qui spécifie le style autorisé de la représentation sous forme de chaîne d'un nombre. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Un pointeur vers un objet qui contient les informations de format de la chaîne. |
| result | **int64_t**& | La référence à une variable d'entier signé 64 bits où le résultat de la conversion est placé. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## Int64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&, int64_t&) méthode


```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&, int64_t&) méthode


```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, int64_t&) méthode


```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)