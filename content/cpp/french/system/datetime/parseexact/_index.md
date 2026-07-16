---
title: ParseExact()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la representation sous forme de chaine specifiee d'une valeur de date et d'heure en l'objet DateTime equivalent en utilisant le format specifie et les informations de format specifique a la culture. Le format de la representation sous forme de chaine doit correspondre exactement au format specifie. Leve une exception si la conversion echoue.
type: docs
weight: 872
url: /fr/system/datetime/parseexact/
---
## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) méthode

Convertit la représentation sous forme de chaîne spécifiée d'une valeur de date et d'heure en l'objet [DateTime](../) équivalent en utilisant le format spécifié et les informations de format spécifiques à la culture. Le format de la représentation sous forme de chaîne doit correspondre exactement au format spécifié. Lève une exception si la conversion échoue.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d'une valeur de date et d'heure à convertir. |
| format | const [String](../../string/)\& | Le format de chaîne. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'objet [IFormatProvider](../../iformatprovider/) qui fournit les informations de format spécifiques à la culture. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Une combinaison bit à bit des valeurs d'énumération qui fournit des informations supplémentaires sur **s**, sur les éléments de style pouvant être présents dans **s**, ou sur la conversion de **s** en un objet [DateTime](../). |

### Valeur de retour

Une nouvelle instance de la classe [DateTime](../) qui représente la valeur de date et d'heure équivalente à celle représentée par la chaîne spécifiée.

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) méthode

Convertit la représentation sous forme de chaîne spécifiée d'une valeur de date et d'heure en l'objet [DateTime](../) équivalent en utilisant les formats spécifiés, les informations de format spécifiques à la culture et le style. Le format de la représentation sous forme de chaîne doit correspondre exactement à un ou plusieurs des formats spécifiés. Lève une exception si la conversion échoue.

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d'une valeur de date et d'heure à convertir. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Le tableau des formats de chaîne. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'objet [IFormatProvider](../../iformatprovider/) qui fournit les informations de format spécifiques à la culture. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Une combinaison bit à bit des valeurs d'énumération qui fournit des informations supplémentaires sur **s**, sur les éléments de style pouvant être présents dans **s**, ou sur la conversion de **s** en un objet [DateTime](../). |

### Valeur de retour

Une nouvelle instance de la classe [DateTime](../) qui représente la valeur de date et d'heure équivalente à celle représentée par la chaîne spécifiée.

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## Voir aussi

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)