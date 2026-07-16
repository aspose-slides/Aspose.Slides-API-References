---
title: ToDecimal()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la valeur booléenne spécifiée en un nombre décimal équivalent.
type: docs
weight: 235
url: /fr/system/convert/todecimal/
---
## Convert::ToDecimal(bool) méthode

Convertit la valeur booléenne spécifiée en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) méthode

Convertit l’entier non signé de 8 bits spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) méthode

Convertit l’entier signé de 8 bits spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) méthode

Convertit l’entier non signé de 16 bits spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) méthode

Convertit l’entier signé de 16 bits spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) méthode

Convertit l’entier non signé de 32 bits spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) méthode

Convertit l’entier signé de 32 bits spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) méthode

Convertit l’entier non signé de 64 bits spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) méthode

Convertit l’entier signé de 64 bits spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) méthode

Convertit le nombre à virgule flottante spécifié en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) méthode

Convertit le nombre double précisé en un nombre décimal équivalent.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) méthode

Renvoie le nombre décimal spécifié.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) méthode

La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) méthode

La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) méthode

Convertit la chaîne nulle spécifiée en la valeur [Decimal](../../decimal/) équivalente.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### Valeur de retour

Zéro.

## Convert::ToDecimal(const char_t *) méthode

Convertit la chaîne C contenant la représentation sous forme de chaîne d’un nombre en la valeur [Decimal](../../decimal/) équivalente.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La chaîne C à convertir |

### Valeur de retour

La valeur [Decimal](../../decimal/) égale au nombre représenté par la chaîne C spécifiée

## Convert::ToDecimal(const String\&) méthode

Convertit la chaîne contenant la représentation sous forme de chaîne d’un nombre en la valeur [Decimal](../../decimal/) équivalente.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

La valeur [Decimal](../../decimal/) égale au nombre représenté par la chaîne spécifiée

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne contenant la représentation sous forme de chaîne d’un nombre en la valeur [Decimal](../../decimal/) équivalente en utilisant les informations de formatage fournies.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne |

### Valeur de retour

La valeur [Decimal](../../decimal/) égale au nombre représenté par la chaîne spécifiée

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne contenant la représentation sous forme de chaîne d’un nombre en la valeur [Decimal](../../decimal/) équivalente en utilisant les styles numériques et les informations de formatage spécifiés.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire de valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation sous forme de chaîne d’un nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne |

### Valeur de retour

La valeur [Decimal](../../decimal/) égale au nombre représenté par la chaîne spécifiée

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la valeur encadrée spécifiée en une valeur [Decimal](../../decimal/) équivalente.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l’objet contenant la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encadrée est [String](../../string/) |

### Valeur de retour

Une valeur [Decimal](../../decimal/) équivalente à la valeur encadrée spécifiée

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)