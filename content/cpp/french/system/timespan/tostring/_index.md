---
title: ToString()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la représentation sous forme de chaîne de l'intervalle de temps représenté par l'objet actuel.
type: docs
weight: 261
url: /fr/system/timespan/tostring/
---
## TimeSpan::ToString() const méthode

Retourne la représentation sous forme de chaîne de l'intervalle de temps représenté par l'objet actuel.

```cpp
String System::TimeSpan::ToString() const
```

## TimeSpan::ToString(const String\&) const méthode

Convertit la valeur de l'objet actuel en une représentation sous forme de chaîne équivalente, en utilisant le format spécifié.

```cpp
String System::TimeSpan::ToString(const String &format) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const méthode

Convertit la valeur de l'objet actuel en une représentation sous forme de chaîne équivalente, en utilisant le format spécifié et le fournisseur de format.

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const méthode




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const méthode




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## TimeSpan::ToString(const String\&, std::nullptr_t) const méthode




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
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