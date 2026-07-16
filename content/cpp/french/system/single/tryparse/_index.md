---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne spécifiée contenant la représentation sous forme de chaîne d'un nombre en la valeur à virgule flottante simple précision équivalente.
type: docs
weight: 14
url: /fr/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) méthode

Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| result | **float**\& | The reference to a single-precision floating-point variable where the result of the conversion is put. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) méthode

Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information and number style.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information. |
| result | **float**\& | The reference to a single-precision floating-point variable where the result of the conversion is put. |

### Valeur de retour

True si la conversion a réussi, sinon - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) méthode

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) méthode

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) méthode

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Voir aussi

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)