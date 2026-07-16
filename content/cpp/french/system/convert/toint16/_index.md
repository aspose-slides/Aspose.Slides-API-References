---
title: ToInt16()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la valeur booléenne spécifiée en un entier signé de 16 bits équivalent.
type: docs
weight: 131
url: /fr/system/convert/toint16/
---
## Convert::ToInt16(bool) méthode

Convertit la valeur booléenne spécifiée en un entier signé de 16 bits équivalent.

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```
## Convert::ToInt16(uint8_t) méthode

Convertit l'entier non signé de 8 bits spécifié en un entier signé de 16 bits équivalent.

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```
## Convert::ToInt16(int8_t) méthode

Convertit l'entier signé de 8 bits spécifié en un entier signé de 16 bits équivalent.

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```
## Convert::ToInt16(uint16_t) méthode

Convertit l'entier non signé de 16 bits spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```
## Convert::ToInt16(int16_t) méthode

Retourne l'entier signé de 16 bits spécifié.

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```
## Convert::ToInt16(uint32_t) méthode

Convertit l'entier non signé de 32 bits spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```
## Convert::ToInt16(int32_t) méthode

Convertit l'entier signé de 32 bits spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```
## Convert::ToInt16(uint64_t) méthode

Convertit l'entier non signé de 64 bits spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```
## Convert::ToInt16(int64_t) méthode

Convertit l'entier signé de 64 bits spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```
## Convert::ToInt16(float) méthode

Convertit le nombre flottant spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(float value)
```
## Convert::ToInt16(double) méthode

Convertit le nombre double spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(double value)
```
## Convert::ToInt16(const Decimal\&) méthode

Convertit le nombre décimal spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```
## Convert::ToInt16(char_t) méthode

Convertit le caractère Unicode spécifié en un entier signé de 16 bits équivalent.

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```
## Convert::ToInt16(DateTime) méthode

La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```
## Convert::ToInt16(std::nullptr_t) méthode

Convertit la chaîne nulle spécifiée en la valeur entière de 16 bits équivalente.

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```


### Valeur de retour

Zéro.

## Convert::ToInt16(const char_t *) méthode

Convertit la chaîne C spécifiée contenant la représentation textuelle d’un nombre en la valeur entière de 16 bits équivalente.

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La chaîne C à convertir |

### Valeur de retour

La valeur entière de 16 bits égale au nombre représenté par la chaîne C spécifiée

## Convert::ToInt16(const String\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur entière de 16 bits équivalente.

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

La valeur entière de 16 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToInt16(const String\&, int) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre dans la base indiquée en la valeur entière de 16 bits équivalente.

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| from_base | int | La base du nombre représenté par la chaîne |

### Valeur de retour

La valeur entière de 16 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur entière de 16 bits équivalente en utilisant les informations de formatage fournies.

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne |

### Valeur de retour

La valeur entière de 16 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) méthode




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur entière de 16 bits équivalente en utilisant les informations de formatage fournies et le style de nombre.

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison bit à bit des valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation textuelle d’un nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne |

### Valeur de retour

La valeur entière de 16 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) méthode




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la valeur encadrée spécifiée en une valeur entière de 16 bits équivalente.

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l’objet qui encapsule la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encapsulée est [String](../../string/) |

### Valeur de retour

Une valeur entière de 16 bits équivalente à la valeur encapsulée spécifiée

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)