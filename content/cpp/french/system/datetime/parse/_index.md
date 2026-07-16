---
title: Parse()
second_title: Référence de l'API Aspose.Slides for C++
description: Convertit la représentation sous forme de chaîne d'une date et d'une heure spécifiée en l'objet DateTime équivalent.
type: docs
weight: 859
url: /fr/system/datetime/parse/
---
## DateTime::Parse(const String\&) méthode

Convertit la représentation sous forme de chaîne d'une date et d'une heure spécifiée en l'objet [DateTime](../) équivalent.

```cpp
static DateTime System::DateTime::Parse(const String &s)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d'une date et d'une heure à convertir. |

### Valeur de retour

Une nouvelle instance de la classe [DateTime](../) qui représente la valeur de date et d'heure équivalente à celle représentée par la chaîne spécifiée.

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) méthode

Convertit la représentation sous forme de chaîne d'une date et d'une heure spécifiée en l'objet [DateTime](../) équivalent en utilisant les informations de format spécifiques à la culture.

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d'une date et d'une heure à convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'objet [IFormatProvider](../../iformatprovider/) qui fournit les informations de format spécifiques à la culture. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Une combinaison binaire des valeurs d'énumération qui fournit des informations supplémentaires sur **s**, sur les éléments de style pouvant être présents dans **s**, ou sur la conversion de **s** en un objet [DateTime](../). |

### Valeur de retour

Une nouvelle instance de la classe [DateTime](../) qui représente la valeur de date et d'heure équivalente à celle représentée par la chaîne spécifiée.

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) méthode

```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## Voir aussi

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [DateTime](../)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)