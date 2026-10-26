---
title: TryParse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la chaîne en un objet TimeSpan équivalent et renvoie le résultat de la conversion.
type: docs
weight: 560
url: /fr/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) méthode


Convertit la chaîne en un objet [TimeSpan](../) équivalent et renvoie le résultat de la conversion.

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Chaîne d’entrée. |
| result | [TimeSpan](../)\& | Intervalle de temps qui correspond à la chaîne. |

### Valeur de retour

True si la chaîne a été convertie avec succès ; sinon, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) méthode


Convertit la chaîne en un objet [TimeSpan](../) équivalent en utilisant le fournisseur de format spécifié et renvoie le résultat de la conversion.

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Chaîne d’entrée. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format qui fournit les informations de formatage spécifiques à la culture. |
| result | [TimeSpan](../)\& | Intervalle de temps qui correspond à la chaîne. |

### Valeur de retour

True si la chaîne a été convertie avec succès ; sinon, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) méthode




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) méthode




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) méthode




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [TimeSpan](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)