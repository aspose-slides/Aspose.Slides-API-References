---
title: ToString()
second_title: Référence API Aspose.Slides for C++
description: Renvoie la représentation sous forme de chaîne de la date et de l'heure représentées par l'objet actuel en utilisant les conventions de formatage définies par la culture actuelle.
type: docs
weight: 482
url: /fr/system/datetime/tostring/
---
## DateTime::ToString() const méthode

Renvoie la représentation sous forme de chaîne de la date et de l'heure représentées par l'objet actuel en utilisant les conventions de formatage définies par la culture actuelle.

```cpp
String System::DateTime::ToString() const
```

### Valeur de retour

La représentation sous forme de chaîne de la valeur représentée par l'objet actuel

## DateTime::ToString(const String\&) const méthode

Renvoie une représentation sous forme de chaîne de la date et de l'heure représentées par l'objet actuel en utilisant le format spécifié et les conventions de formatage définies par la culture actuelle.

```cpp
String System::DateTime::ToString(const String &format) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Une chaîne de format |

### Valeur de retour

La représentation sous forme de chaîne de la valeur représentée par l'objet actuel formatée selon le format défini par **format** et la culture actuelle.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const méthode

Renvoie une représentation sous forme de chaîne de la date et de l'heure représentées par l'objet actuel en utilisant les informations de format spécifiées.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un objet représentant les informations de format |

### Valeur de retour

La représentation sous forme de chaîne de la valeur représentée par l'objet actuel formatée selon les informations de format fournies par **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const méthode




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const méthode




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const méthode




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const méthode

Renvoie une représentation sous forme de chaîne de la date et de l'heure représentées par l'objet actuel en utilisant les informations de format spécifiées.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Une chaîne de format |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Un objet représentant les informations de format |

### Valeur de retour

La représentation sous forme de chaîne de la valeur représentée par l'objet actuel formatée selon les informations de format fournies par **provider** et la chaîne de format **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const méthode




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const méthode




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const méthode




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTime](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)