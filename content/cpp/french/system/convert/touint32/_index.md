---
title: ToUInt32()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la valeur booléenne spécifiée en un entier non signé de 32 bits équivalent.
type: docs
weight: 170
url: /fr/system/convert/touint32/
---
## Convert::ToUInt32(bool) méthode


Convertit la valeur booléenne spécifiée en un entier non signé de 32 bits équivalent.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(bool value)
```

## Convert::ToUInt32(uint8_t) méthode


Convertit l'entier non signé de 8 bits spécifié en un entier non signé de 32 bits équivalent.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint8_t value)
```

## Convert::ToUInt32(int8_t) méthode


Convertit l'entier signé de 8 bits spécifié en un entier non signé de 32 bits équivalent.

```cpp
static uint32_t System::Convert::ToUInt32(int8_t value)
```

## Convert::ToUInt32(uint16_t) méthode


Convertit l'entier non signé de 16 bits spécifié en un entier non signé de 32 bits équivalent.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint16_t value)
```

## Convert::ToUInt32(int16_t) méthode


Convertit l'entier signé de 16 bits spécifié en un entier non signé de 32 bits équivalent.

```cpp
static uint32_t System::Convert::ToUInt32(int16_t value)
```

## Convert::ToUInt32(uint32_t) méthode


Renvoie l'entier non signé de 32 bits spécifié.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(uint32_t value)
```

## Convert::ToUInt32(int32_t) méthode


Convertit l'entier signé de 32 bits spécifié en un entier non signé de 32 bits équivalent.

```cpp
static uint32_t System::Convert::ToUInt32(int32_t value)
```

## Convert::ToUInt32(uint64_t) méthode


Convertit l'entier non signé de 64 bits spécifié en un entier non signé de 32 bits équivalent.

```cpp
static uint32_t System::Convert::ToUInt32(uint64_t value)
```

## Convert::ToUInt32(int64_t) méthode


Convertit l'entier signé de 64 bits spécifié en un entier non signé de 32 bits équivalent.

```cpp
static uint32_t System::Convert::ToUInt32(int64_t value)
```

## Convert::ToUInt32(float) méthode


Convertit le nombre à virgule flottante spécifié en un entier non signé de 32 bits équivalent.

```cpp
static uint32_t System::Convert::ToUInt32(float value)
```

## Convert::ToUInt32(double) méthode


Convertit le nombre double spécifié en un entier non signé de 32 bits équivalent.

```cpp
static uint32_t System::Convert::ToUInt32(double value)
```

## Convert::ToUInt32(const Decimal\&) méthode


Convertit le nombre décimal spécifié en un entier non signé de 32 bits équivalent.

```cpp
static uint32_t System::Convert::ToUInt32(const Decimal &value)
```

## Convert::ToUInt32(char_t) méthode


Convertit le caractère Unicode spécifié en un entier non signé de 32 bits équivalent.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(char_t value)
```

## Convert::ToUInt32(DateTime) méthode


La conversion n'est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static uint32_t System::Convert::ToUInt32(DateTime value)
```

## Convert::ToUInt32(std::nullptr_t) méthode


Convertit la chaîne nulle spécifiée en la valeur équivalente d'entier non signé de 32 bits.

```cpp
static constexpr uint32_t System::Convert::ToUInt32(std::nullptr_t)
```


### Valeur de retour

Zéro.

## Convert::ToUInt32(const char_t *) méthode


Convertit la chaîne C contenant la représentation littérale d'un nombre en la valeur équivalente d'entier non signé de 32 bits.

```cpp
static uint32_t System::Convert::ToUInt32(const char_t *value)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La chaîne C à convertir |

### Valeur de retour

La valeur d'entier non signé de 32 bits égale au nombre représenté par la chaîne C spécifiée

## Convert::ToUInt32(const String\&) méthode


Convertit la chaîne contenant la représentation littérale d'un nombre en la valeur équivalente d'entier non signé de 32 bits.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

La valeur d'entier non signé de 32 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToUInt32(const String\&, int) méthode


Convertit la chaîne contenant la représentation littérale d'un nombre dans la base spécifiée en la valeur équivalente d'entier non signé de 32 bits.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, int from_base)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| from_base | int | La base du nombre représenté par la chaîne |

### Valeur de retour

La valeur d'entier non signé de 32 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToUInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode


Convertit la chaîne contenant la représentation littérale d'un nombre en la valeur équivalente d'entier non signé de 32 bits en utilisant les informations de format fournies.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne |

### Valeur de retour

La valeur d'entier non signé de 32 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, std::nullptr_t) méthode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, std::nullptr_t)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode


Convertit la chaîne contenant la représentation littérale d'un nombre en la valeur équivalente d'entier non signé de 32 bits en utilisant les informations de format et le style de nombre fournis.

```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Combinaison binaire des valeurs de l'énumération NumberStyles qui spécifie le style autorisé de la représentation sous forme de chaîne d'un nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne |

### Valeur de retour

La valeur d'entier non signé de 32 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode




```cpp
static uint32_t System::Convert::ToUInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt32(Enum) méthode




```cpp
template<typename Enum,typename> static uint32_t System::Convert::ToUInt32(Enum value)
```

## Convert::ToUInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) méthode


Convertit la valeur encapsulée spécifiée en une valeur d'entier non signé de 32 bits équivalente.

```cpp
static uint32_t System::Convert::ToUInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l'objet qui encapsule la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encapsulée est [String](../../string/) |

### Valeur de retour

Une valeur d'entier non signé de 32 bits équivalente à la valeur encapsulée spécifiée

## See Also

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)