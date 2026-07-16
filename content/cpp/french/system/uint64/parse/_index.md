---
title: Parse()
second_title: Référence API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier non signé 64 bits équivalent.
type: docs
weight: 1
url: /fr/system/uint64/parse/
---
## UInt64::Parse(const String\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier non signé 64 bits équivalent.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |

### Valeur de retour

L’entier non signé 64 bits égal au nombre représenté par la chaîne spécifiée.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier non signé 64 bits équivalent en utilisant les informations de formatage fournies.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne. |

### Valeur de retour

L’entier non signé 64 bits égal au nombre représenté par la chaîne spécifiée.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) méthode




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d’un nombre en l’entier non signé 64 bits équivalent en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire de valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation sous forme de chaîne d’un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne. |

### Valeur de retour

L’entier non signé 64 bits égal au nombre représenté par la chaîne spécifiée.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)