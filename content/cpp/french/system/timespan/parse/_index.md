---
title: Parse()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit une chaîne en l'objet TimeSpan équivalent.
type: docs
weight: 534
url: /fr/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) méthode

Convertit la chaîne en l’objet [TimeSpan](../) équivalent.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Chaîne d’entrée. |

### Valeur de retour

Intervalle de temps correspondant à la chaîne.

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) méthode

Convertit la chaîne en l’objet [TimeSpan](../) équivalent en utilisant le fournisseur de format spécifié.

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | Chaîne d’entrée. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format qui fournit les informations de mise en forme spécifiques à la culture. |

### Valeur de retour

Intervalle de temps correspondant à la chaîne.

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) méthode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) méthode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) méthode




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)