---
title: ToBoolean()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie la valeur booléenne spécifiée.
type: docs
weight: 79
url: /fr/system/convert/toboolean/
---
## Convert::ToBoolean(bool) méthode


Renvoie la valeur booléenne spécifiée.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) méthode


Convertit l’entier non signé de 8 bits spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) méthode


Convertit l’entier signé de 8 bits spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) méthode


Convertit l’entier non signé de 16 bits spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) méthode


Convertit l’entier signé de 16 bits spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) méthode


Convertit l’entier non signé de 32 bits spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) méthode


Convertit l’entier signé de 32 bits spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) méthode


Convertit l’entier non signé de 64 bits spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) méthode


Convertit l’entier signé de 64 bits spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) méthode


Convertit le nombre flottant spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) méthode


Convertit le nombre double spécifié en une valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) méthode


Convertit le nombre décimal spécifié en une valeur booléenne équivalente.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) méthode


La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) méthode


La conversion n’est pas prise en charge. Lève toujours InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) méthode


Convertit la chaîne nulle spécifiée en la valeur booléenne équivalente.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Valeur de retour

False.

## Convert::ToBoolean(const char_t *) méthode


Convertit la chaîne c spécifiée en une valeur de type bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const char_t * | La chaîne c à convertir |

### Valeur de retour

True si la chaîne c spécifiée est égale à "True" et false si la chaîne c spécifiée est égale à "False".

## Convert::ToBoolean(const String\&) méthode


Convertit la chaîne spécifiée en une valeur de type bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

True si la chaîne spécifiée est égale à "True" et false si la chaîne spécifiée est égale à "False".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode


Convertit la chaîne spécifiée en une valeur de type bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | La chaîne à convertir |

### Valeur de retour

True si la chaîne spécifiée est égale à "True" et false si la chaîne spécifiée est égale à "False".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) méthode


Convertit la valeur encadrée spécifiée en une valeur booléenne équivalente.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Le pointeur partagé vers l'objet encapsulant la valeur à convertir |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Le format de chaîne à utiliser si le type de la valeur encadrée est [String](../../string/) |

### Valeur de retour

Une valeur booléenne équivalente à la valeur encadrée spécifiée

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)