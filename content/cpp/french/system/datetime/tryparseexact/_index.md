---
title: TryParseExact()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la représentation sous forme de chaîne spécifiée d'une valeur de date et d'heure en l'objet DateTime équivalent en utilisant le format spécifié, les informations de format spécifiques à la culture et le style. Le format de la représentation sous forme de chaîne doit correspondre exactement au format spécifié.
type: docs
weight: 898
url: /fr/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) méthode


Convertit la représentation sous forme de chaîne spécifiée d’une valeur de date et d’heure en l’objet [DateTime](../) équivalent en utilisant le format spécifié, les informations de format spécifiques à la culture et le style. Le format de la représentation sous forme de chaîne doit correspondre exactement au format spécifié.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d’une valeur de date et d’heure à convertir. |
| format | const [String](../../string/)\& | Le format de chaîne. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L’objet [IFormatProvider](../../iformatprovider/) qui fournit des informations de format spécifiques à la culture. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Une combinaison binaire des valeurs d’énumération qui fournit des informations supplémentaires sur **s**, sur les éléments de style pouvant être présents dans **s**, ou sur la conversion de **s** en un objet [DateTime](../). |
| result | [DateTime](../)\& | L’argument de sortie qui, si la conversion réussit, contient le résultat de la conversion. |

### Valeur de retour

True si la conversion réussit, sinon - false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) méthode


Convertit la représentation sous forme de chaîne spécifiée d’une valeur de date et d’heure en l’objet [DateTime](../) équivalent en utilisant les formats spécifiés, les informations de format spécifiques à la culture et le style. Le format de la représentation sous forme de chaîne doit correspondre exactement à un ou plusieurs des formats spécifiés.

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d’une valeur de date et d’heure à convertir. |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | Le tableau des formats de chaîne. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L’objet [IFormatProvider](../../iformatprovider/) qui fournit des informations de format spécifiques à la culture. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Une combinaison binaire des valeurs d’énumération qui fournit des informations supplémentaires sur **s**, sur les éléments de style pouvant être présents dans **s**, ou sur la conversion de **s** en un objet [DateTime](../). |
| result | [DateTime](../)\& | L’argument de sortie qui, si la conversion réussit, contient le résultat de la conversion. |

### Valeur de retour

True si la conversion réussit, sinon - false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Voir aussi

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)