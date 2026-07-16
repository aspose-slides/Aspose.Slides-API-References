---
title: ToDouble()
second_title: Référence API Aspose.Slides pour C++
description: Convertit la valeur booléenne spécifiée en un nombre à virgule flottante double précision équivalent.
type: docs
weight: 222
url: /fr/system/convert/todouble/
---
## Convert::ToDouble(bool) method

Convertit la valeur booléenne spécifiée en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) method

Convertit l’entier non signé de 8 bits spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) method

Convertit l’entier signé de 8 bits spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) method

Convertit l’entier non signé de 16 bits spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) method

Convertit l’entier signé de 16 bits spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) method

Convertit l’entier non signé de 32 bits spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) method

Convertit l’entier signé de 32 bits spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) method

Convertit l’entier non signé de 64 bits spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) method

Convertit l’entier signé de 64 bits spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) method

Convertit le nombre à précision simple spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) method

Renvoie le nombre double spécifié.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) method

Convertit le nombre décimal spécifié en un nombre à virgule flottante double précision équivalent.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) method

La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) method

La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) method

Convertit la chaîne nulle spécifiée en la valeur équivalente à virgule flottante double précision.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```

### Valeur de retour

Zéro.

## Convert::ToDouble(const char_t *) method

Convertit la chaîne c contenant la représentation sous forme de texte d’un nombre en la valeur à virgule flottante double précision équivalente.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La chaîne c à convertir |

### Valeur de retour

La valeur à virgule flottante double précision égale au nombre représenté par la chaîne c spécifiée

## Convert::ToDouble(const String\&) method

Convertit la chaîne contenant la représentation sous forme de texte d’un nombre en la valeur à virgule flottante double précision équivalente.

```cpp
static double System::Convert::ToDouble(const String &value)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

La valeur à virgule flottante double précision égale au nombre représenté par la chaîne spécifiée

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) method

Convertit la chaîne contenant la représentation sous forme de texte d’un nombre en la valeur à virgule flottante double précision équivalente en utilisant les informations de format fournies.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne |

### Valeur de retour

La valeur à virgule flottante double précision égale au nombre représenté par la chaîne spécifiée

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) method




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

Convertit la chaîne contenant la représentation sous forme de texte d’un nombre en la valeur à virgule flottante double précision équivalente en utilisant les informations de format et le style de nombre fournis.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison bit à bit des valeurs de l’énumération NumberStyles qui indique le style autorisé de la représentation sous forme de texte du nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne |

### Valeur de retour

La valeur à virgule flottante double précision égale au nombre représenté par la chaîne spécifiée

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

Convertit la valeur encapsulée spécifiée en valeur à virgule flottante double précision. Si le type de la valeur encapsulée est [String](../../string/), le format de chaîne fourni est utilisé pendant la conversion.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l’objet encapsulant la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encapsulée est [String](../../string/) |

### Valeur de retour

Une valeur à virgule flottante double précision équivalente à la valeur encapsulée spécifiée

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)