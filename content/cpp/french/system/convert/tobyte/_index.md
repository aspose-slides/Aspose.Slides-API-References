---
title: ToByte()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la valeur booléenne spécifiée en un entier non signé de 8 bits équivalent.
type: docs
weight: 92
url: /fr/system/convert/tobyte/
---
## Convert::ToByte(bool) méthode

Convertit la valeur booléenne spécifiée en un entier non signé de 8 bits équivalent.

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) méthode

Renvoie l’entier non signé de 8 bits spécifié.

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) méthode

Convertit l’entier signé de 8 bits spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) méthode

Convertit l’entier non signé de 16 bits spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) méthode

Convertit l’entier signé de 16 bits spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) méthode

Convertit l’entier non signé de 32 bits spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) méthode

Convertit l’entier signé de 32 bits spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) méthode

Convertit l’entier non signé de 64 bits spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) méthode

Convertit l’entier signé de 64 bits spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) méthode

Convertit le nombre flottant spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) méthode

Convertit le nombre double spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) méthode

Convertit le nombre décimal spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) méthode

Convertit le caractère Unicode spécifié en un entier non signé de 8 bits équivalent.

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) méthode

La conversion n’est pas prise en charge. Lance toujours InvalidCastException.

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) méthode

Convertit la chaîne nulle spécifiée en la valeur entier non signé de 8 bits équivalente.

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### Valeur de retour

Zéro.

## Convert::ToByte(const char_t *) méthode

Convertit la chaîne C contenant la représentation textuelle d’un nombre en la valeur entier non signé de 8 bits équivalente.

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La chaîne C à convertir |

### Valeur de retour

La valeur entier non signé de 8 bits égale au nombre représenté par la chaîne C spécifiée

## Convert::ToByte(const String\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur entier non signé de 8 bits équivalente.

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

La valeur entier non signé de 8 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToByte(const String\&, int) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre dans la base indiquée en la valeur entier non signé de 8 bits équivalente.

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| from_base | int | La base du nombre représenté par la chaîne |

### Valeur de retour

La valeur entier non signé de 8 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur entier non signé de 8 bits équivalente en utilisant les informations de format fournies.

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne |

### Valeur de retour

La valeur entier non signé de 8 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) méthode




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d’un nombre en la valeur entier non signé de 8 bits équivalente en utilisant les informations de format et le style de nombre fournis.

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire de valeurs de l’énumération NumberStyles qui spécifie le style autorisé de la représentation chaîne d’un nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de chaîne |

### Valeur de retour

La valeur entier non signé de 8 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) méthode




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la valeur encapsulée spécifiée en une valeur entier non signé de 8 bits équivalente.

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l’objet encapsulant la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encapsulée est [String](../../string/) |

### Valeur de retour

Une valeur entier non signé de 8 bits équivalente à la valeur encapsulée spécifiée

## Voir aussi

* Énumération [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [Decimal](../../decimal/)
* Classe [DateTime](../../datetime/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Classe [Object](../../object/)
* Structure [Convert](../)
* Structure [Enum](../../enum/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)