---
title: ToSByte()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la valeur booléenne spécifiée en un entier signé de 8 bits équivalent.
type: docs
weight: 105
url: /fr/system/convert/tosbyte/
---
## Convert::ToSByte(bool) méthode

Convertit la valeur booléenne spécifiée en un entier signé de 8 bits équivalent.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) méthode

Convertit l'entier non signé de 8 bits spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) méthode

Renvoie l'entier signé de 8 bits spécifié.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) méthode

Convertit l'entier non signé de 16 bits spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) méthode

Convertit l'entier signé de 16 bits spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) méthode

Convertit l'entier non signé de 32 bits spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) méthode

Convertit l'entier signé de 32 bits spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) méthode

Convertit l'entier non signé de 64 bits spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) méthode

Convertit l'entier signé de 64 bits spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) méthode

Convertit le nombre à virgule flottante spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) méthode

Convertit le nombre double spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) méthode

Convertit le nombre décimal spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) méthode

Convertit le caractère Unicode spécifié en un entier signé de 8 bits équivalent.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) méthode

La conversion n'est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) méthode

Convertit la chaîne null spécifiée en la valeur entière de 8 bits équivalente.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### Valeur de retour

Zéro.

## Convert::ToSByte(const char_t *) méthode

Convertit la c-string spécifiée contenant la représentation textuelle d'un nombre en la valeur entière de 8 bits équivalente.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La c-string à convertir |

### Valeur de retour

La valeur entière de 8 bits égale au nombre représenté par la c-string spécifiée

## Convert::ToSByte(const String\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre en la valeur entière de 8 bits équivalente.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

La valeur entière de 8 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToSByte(const String\&, int) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre dans la base spécifiée en la valeur entière de 8 bits équivalente.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| from_base | int | La base du nombre représenté par la chaîne |

### Valeur de retour

La valeur entière de 8 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre en la valeur entière non signée de 8 bits équivalente en utilisant les informations de formatage fournies.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de la chaîne |

### Valeur de retour

La valeur entière de 8 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) méthode

```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne spécifiée contenant la représentation textuelle d'un nombre en la valeur entière de 8 bits en utilisant les informations de formatage et le style de nombre fournis.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison bit à bit des valeurs de l'énumération NumberStyles qui spécifie le style autorisé de la représentation textuelle d'un nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet contenant les informations de format de la chaîne |

### Valeur de retour

La valeur entière non signée de 8 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) méthode

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) méthode

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) méthode

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) méthode

```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la valeur encapsulée spécifiée en une valeur entière de 8 bits équivalente.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l'objet encapsulant la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encapsulée est [String](../../string/) |

### Valeur de retour

Une valeur entière de 8 bits équivalente à la valeur encapsulée spécifiée

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
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