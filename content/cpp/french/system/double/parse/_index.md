---
title: Parse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation texte d'un nombre en la valeur à virgule flottante double précision équivalente.
type: docs
weight: 1
url: /fr/system/double/parse/
---
## Double::Parse(const String\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur à virgule flottante double précision équivalente.

```cpp
static double System::Double::Parse(const String &value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |

### Return Value

La valeur à virgule flottante double précision égale au nombre représenté par la chaîne spécifiée.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur à virgule flottante double précision équivalente en utilisant les informations de formatage fournies.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne. |

### Return Value

La valeur à virgule flottante double précision égale au nombre représenté par la chaîne spécifiée.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) méthode




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode


Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur à virgule flottante double précision équivalente en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison bit à bit des valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation de chaîne d’un nombre. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne. |

### Return Value

La valeur à virgule flottante double précision égale au nombre représenté par la chaîne spécifiée.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)