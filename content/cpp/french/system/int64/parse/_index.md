---
title: Parse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en entier signé de 64 bits équivalent.
type: docs
weight: 1
url: /fr/system/int64/parse/
---
## Int64::Parse(const String\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en entier signé de 64 bits équivalent.

```cpp
static int64_t System::Int64::Parse(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |

### Valeur de retour

L'entier signé de 64 bits égal au nombre représenté par la chaîne spécifiée.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en entier signé de 64 bits équivalent en utilisant les informations de formatage fournies.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de la chaîne. |

### Valeur de retour

L'entier signé de 64 bits égal au nombre représenté par la chaîne spécifiée.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) méthode




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en entier signé de 64 bits équivalent en utilisant les informations de formatage fournies et le style numérique.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison bit à bit des valeurs de l'enum NumberStyles qui spécifie le style autorisé de la représentation sous forme de chaîne d'un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de la chaîne. |

### Valeur de retour

L'entier signé de 64 bits égal au nombre représenté par la chaîne spécifiée.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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