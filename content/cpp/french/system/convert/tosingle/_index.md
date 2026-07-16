---
title: ToSingle()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la valeur booléenne spécifiée en un nombre à virgule flottante à simple précision équivalent.
type: docs
weight: 209
url: /fr/system/convert/tosingle/
---
## Convert::ToSingle(bool) méthode

Convertit la valeur booléenne spécifiée en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) méthode

Convertit l’entier non signé de 8 bits spécifié en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) méthode

Convertit l’entier signé de 8 bits spécifié en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) méthode

Convertit l’entier non signé de 16 bits spécifié en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) méthode

Convertit l’entier signé de 16 bits spécifié en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) méthode

Convertit l’entier non signé de 32 bits spécifié en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) méthode

Convertit l’entier signé de 32 bits spécifié en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) méthode

Convertit l’entier non signé de 64 bits spécifié en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) méthode

Convertit l’entier signé de 64 bits spécifié en un nombre à virgule flottante à simple précision équivalent.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) méthode

Renvoie le nombre float spécifié.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) méthode

Convertit le nombre à double précision spécifié en une valeur à virgule flottante à simple précision équivalente.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) méthode

Convertit le nombre décimal spécifié en une valeur à virgule flottante à simple précision équivalente.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) méthode

La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) méthode

La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) méthode

Convertit la chaîne nulle spécifiée en la valeur à virgule flottante à simple précision équivalente.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### Valeur de retour

Zéro.

## Convert::ToSingle(const char_t *) méthode

Convertit la c-string spécifiée contenant la représentation textuelle d’un nombre en la valeur à virgule flottante à simple précision équivalente.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La c-string à convertir |

### Valeur de retour

La valeur à virgule flottante à simple précision égale au nombre représenté par la c-string spécifiée

## Convert::ToSingle(const String\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur à virgule flottante à simple précision équivalente.

```cpp
static float System::Convert::ToSingle(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

La valeur à virgule flottante à simple précision égale au nombre représenté par la chaîne spécifiée

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur à virgule flottante à simple précision équivalente en utilisant les informations de formatage fournies.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne |

### Valeur de retour

La valeur à virgule flottante à simple précision égale au nombre représenté par la chaîne spécifiée

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) méthode




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur à virgule flottante à simple précision équivalente en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison bit à bit des valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation textuelle d’un nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne |

### Valeur de retour

La valeur à virgule flottante à simple précision égale au nombre représenté par la chaîne spécifiée

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la valeur empaquetée spécifiée en une valeur à virgule flottante à simple précision.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l’objet empaquetant la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur empaquetée est [String](../../string/) |

### Valeur de retour

Une valeur à virgule flottante à simple précision équivalente à la valeur empaquetée spécifiée

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