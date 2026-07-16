---
title: Parse()
second_title: Référence API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre en l'entier non signé 32 bits équivalent.
type: docs
weight: 1
url: /fr/system/uint32/parse/
---
## UInt32::Parse(const String\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier non signé 32 bits équivalent.

```cpp
static uint32_t System::UInt32::Parse(const String &value)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |

### Valeur de retour

L’entier non signé 32 bits égal au nombre représenté par la chaîne spécifiée.

## UInt32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier non signé 32 bits équivalent en utilisant les informations de format fournies.

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de la chaîne. |

### Valeur de retour

L’entier non signé 32 bits égal au nombre représenté par la chaîne spécifiée.

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode

```cpp
static uint32_t System::UInt32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, std::nullptr_t) méthode

```cpp
static uint32_t System::UInt32::Parse(const String &value, std::nullptr_t)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier non signé 32 bits équivalent en utilisant les informations de format et le style numérique fournis.

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire des valeurs de l’énumération NumberStyles qui indique le style autorisé de la représentation sous forme de chaîne d’un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de la chaîne. |

### Valeur de retour

L’entier non signé 32 bits égal au nombre représenté par la chaîne spécifiée.

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode

```cpp
static uint32_t System::UInt32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)