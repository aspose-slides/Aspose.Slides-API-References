---
title: TryParseExact()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit une chaîne en un objet TimeSpan équivalent en utilisant les formats spécifiés et le fournisseur de format, et renvoie le résultat de la conversion.
type: docs
weight: 573
url: /fr/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) méthode

Convertit la chaîne en un objet [TimeSpan](../) équivalent en utilisant les formats spécifiés et le fournisseur de format, et renvoie le résultat de la conversion.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Chaîne d'entrée. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) de chaînes de format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format qui fournit des informations de mise en forme spécifiques à la culture. |
| result | [TimeSpan](../)\& | Intervalle de temps correspondant à la chaîne. |

### Valeur de retour

True si la chaîne a été convertie avec succès ; sinon, false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) méthode

Convertit la chaîne en un objet [TimeSpan](../) équivalent en utilisant le format spécifié, le fournisseur de format et les styles, et renvoie le résultat de la conversion.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Chaîne d'entrée. |
| format | const [String](../../string/)\& | Chaîne de format standard ou personnalisée. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format qui fournit des informations de mise en forme spécifiques à la culture. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Définit les éléments pouvant être présents dans la chaîne d'entrée. |
| result | [TimeSpan](../)\& | Intervalle de temps correspondant à la chaîne. |

### Valeur de retour

True si la chaîne a été convertie avec succès ; sinon, false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) méthode

Convertit la chaîne en un objet [TimeSpan](../) équivalent en utilisant les formats spécifiés, le fournisseur de format et les styles, et renvoie le résultat de la conversion.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Chaîne d'entrée. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) de chaînes de format. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format qui fournit des informations de mise en forme spécifiques à la culture. |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | Définit les éléments pouvant être présents dans la chaîne d'entrée. |
| result | [TimeSpan](../)\& | Intervalle de temps correspondant à la chaîne. |

### Valeur de retour

True si la chaîne a été convertie avec succès ; sinon, false.

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) méthode

Convertit la chaîne en un objet [TimeSpan](../) équivalent en utilisant le format spécifié et le fournisseur de format, et renvoie le résultat de la conversion.

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Chaîne d'entrée. |
| format | const [String](../../string/)\& | Chaîne de format standard ou personnalisée. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format qui fournit des informations de mise en forme spécifiques à la culture. |
| result | [TimeSpan](../)\& | Intervalle de temps correspondant à la chaîne. |

### Valeur de retour

True si la chaîne a été convertie avec succès ; sinon, false.

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) méthode

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## Voir aussi

* Enum [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [TimeSpan](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)