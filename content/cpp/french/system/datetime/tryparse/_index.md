---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la représentation sous forme de chaîne spécifiée d’une valeur de date et d’heure en l’objet DateTime équivalent.
type: docs
weight: 885
url: /fr/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) méthode

Convertit la représentation sous forme de chaîne spécifiée d’une valeur de date et d’heure en l’objet [DateTime](../) équivalent.

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d’une valeur de date et d’heure à convertir. |
| result | [DateTime](../)\& | L’argument de sortie qui, si la conversion réussit, contient le résultat de la conversion. |

### Valeur de retour

True si la conversion réussit, sinon - false.

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) méthode

Convertit la représentation sous forme de chaîne spécifiée d’une valeur de date et d’heure en l’objet [DateTime](../) équivalent en utilisant les informations de format spécifiques à la culture et le style spécifiés.

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | La représentation sous forme de chaîne d’une valeur de date et d’heure à convertir. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L’objet [IFormatProvider](../../iformatprovider/) qui fournit les informations de format spécifiques à la culture. |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | Une combinaison binaire des valeurs d’énumération qui fournit des informations supplémentaires sur **s**, sur les éléments de style pouvant être présents dans **s**, ou sur la conversion de **s** vers un objet [DateTime](../). |
| result | [DateTime](../)\& | L’argument de sortie qui, si la conversion réussit, contient le résultat de la conversion. |

### Valeur de retour

True si la conversion réussit, sinon - false.

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) méthode




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## Voir aussi

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTime](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)