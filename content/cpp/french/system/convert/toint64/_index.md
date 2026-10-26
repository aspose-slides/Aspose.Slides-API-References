---
title: ToInt64()
second_title: Référence API Aspose.Slides pour C++
description: Convertit la valeur booléenne spécifiée en un entier signé de 64 bits équivalent.
type: docs
weight: 183
url: /fr/system/convert/toint64/
---
## Convert::ToInt64(bool) méthode

Convertit la valeur booléenne spécifiée en un entier signé de 64 bits équivalent.

```cpp
static constexpr int64_t System::Convert::ToInt64(bool value)
```

## Convert::ToInt64(uint8_t) méthode

Convertit l'entier non signé de 8 bits spécifié en un entier signé de 64 bits équivalent.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint8_t value)
```

## Convert::ToInt64(int8_t) méthode

Convertit l'entier signé de 8 bits spécifié en un entier signé de 64 bits équivalent.

```cpp
static constexpr int64_t System::Convert::ToInt64(int8_t value)
```

## Convert::ToInt64(uint16_t) méthode

Convertit l'entier non signé de 16 bits spécifié en un entier signé de 64 bits équivalent.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint16_t value)
```

## Convert::ToInt64(int16_t) méthode

Convertit l'entier signé de 16 bits spécifié en un entier signé de 64 bits équivalent.

```cpp
static constexpr int64_t System::Convert::ToInt64(int16_t value)
```

## Convert::ToInt64(uint32_t) méthode

Convertit l'entier non signé de 32 bits spécifié en un entier signé de 64 bits équivalent.

```cpp
static constexpr int64_t System::Convert::ToInt64(uint32_t value)
```

## Convert::ToInt64(int32_t) méthode

Convertit l'entier signé de 32 bits spécifié en un entier signé de 64 bits équivalent.

```cpp
static constexpr int64_t System::Convert::ToInt64(int32_t value)
```

## Convert::ToInt64(uint64_t) méthode

Convertit l'entier non signé de 64 bits spécifié en un entier signé de 64 bits équivalent.

```cpp
static int64_t System::Convert::ToInt64(uint64_t value)
```

## Convert::ToInt64(int64_t) méthode

Renvoie l'entier signé de 64 bits spécifié.

```cpp
static constexpr int64_t System::Convert::ToInt64(int64_t value)
```

## Convert::ToInt64(float) méthode

Convertit le nombre à virgule flottante spécifié en un entier signé de 64 bits équivalent.

```cpp
static int64_t System::Convert::ToInt64(float value)
```

## Convert::ToInt64(double) méthode

Convertit le nombre double spécifié en un entier signé de 64 bits équivalent.

```cpp
static int64_t System::Convert::ToInt64(double value)
```

## Convert::ToInt64(const Decimal&) méthode

Convertit le nombre décimal spécifié en un entier signé de 64 bits équivalent.

```cpp
static int64_t System::Convert::ToInt64(const Decimal &value)
```

## Convert::ToInt64(char_t) méthode

Convertit le caractère unicode spécifié en un entier signé de 64 bits équivalent.

```cpp
static constexpr int64_t System::Convert::ToInt64(char_t value)
```

## Convert::ToInt64(DateTime) méthode

La conversion n'est pas prise en charge. Lance toujours InvalidCastException.

```cpp
static int64_t System::Convert::ToInt64(DateTime value)
```

## Convert::ToInt64(std::nullptr_t) méthode

Convertit la chaîne nulle spécifiée en la valeur entière 64 bits équivalente.

```cpp
static constexpr int64_t System::Convert::ToInt64(std::nullptr_t)
```

### Valeur de retour

Zéro.

## Convert::ToInt64(const char_t *) méthode

Convertit la c-string spécifiée contenant la représentation littérale d'un nombre en la valeur entière de 64 bits équivalente.

```cpp
static int64_t System::Convert::ToInt64(const char_t *value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La c-string à convertir |

### Valeur de retour

La valeur entière de 64 bits égale au nombre représenté par la c-string spécifiée

## Convert::ToInt64(const String&) méthode

Convertit la chaîne spécifiée contenant la représentation littérale d'un nombre en la valeur entière de 64 bits équivalente.

```cpp
static int64_t System::Convert::ToInt64(const String &value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

La valeur entière de 64 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToInt64(const String&, int) méthode

Convertit la chaîne spécifiée contenant la représentation littérale d'un nombre dans la base indiquée en la valeur entière de 64 bits équivalente.

```cpp
static int64_t System::Convert::ToInt64(const String &value, int from_base)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| from_base | int | La base du nombre représenté par la chaîne |

### Valeur de retour

La valeur entière de 64 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToInt64(const String&, const SharedPtr<IFormatProvider>&) méthode

Convertit la chaîne spécifiée contenant la représentation littérale d'un nombre en la valeur entière de 64 bits équivalente en utilisant les informations de format fournies.

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne |

### Valeur de retour

La valeur entière de 64 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToInt64(const String&, const SharedPtr<Globalization::CultureInfo>&) méthode

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String&, const SharedPtr<Globalization::NumberFormatInfo>&) méthode

```cpp
static int64_t System::Convert::ToInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String&, std::nullptr_t) méthode

```cpp
static int64_t System::Convert::ToInt64(const String &value, std::nullptr_t)
```

## Convert::ToInt64(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&) méthode

Convertit la chaîne spécifiée contenant la représentation littérale d'un nombre en la valeur entière de 64 bits équivalente en utilisant les informations de format fournies et le style de nombre.

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Une combinaison binaire de valeurs de l'énumération NumberStyles qui spécifie le style autorisé de la représentation littérale d'un nombre |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un pointeur vers un objet qui contient les informations de format de chaîne |

### Valeur de retour

La valeur entière de 64 bits égale au nombre représenté par la chaîne spécifiée

## Convert::ToInt64(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&) méthode

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt64(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&) méthode

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt64(const String&, Globalization::NumberStyles, std::nullptr_t) méthode

```cpp
static int64_t System::Convert::ToInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt64(Enum) méthode

```cpp
template<typename Enum,typename> static int64_t System::Convert::ToInt64(Enum value)
```

## Convert::ToInt64(const SharedPtr<Object>&, const SharedPtr<IFormatProvider>&) méthode

Convertit la valeur encapsulée spécifiée en une valeur entière de 64 bits équivalente.

```cpp
static int64_t System::Convert::ToInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l'objet qui encapsule la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encapsulée est [String](../../string/) |

### Valeur de retour

Une valeur entière de 64 bits équivalente à la valeur encapsulée spécifiée

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