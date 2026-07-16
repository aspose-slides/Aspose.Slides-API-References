---
title: ToString()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la représentation sous forme de chaîne de la valeur représentée par l'objet.
type: docs
weight: 352
url: /fr/system/decimal/tostring/
---
## Decimal::ToString() const méthode

Renvoie la représentation sous forme de chaîne de la valeur représentée par l'objet.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const méthode

Convertit l'objet actuel en chaîne en utilisant les informations de format spécifiques à la culture.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'objet [IFormatProvider](../../iformatprovider/) fournissant les informations de format spécifiques à la culture. |

### Valeur de retour

La représentation sous forme de chaîne de l'objet actuel.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const méthode

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const méthode

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const méthode

```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const méthode

Convertit l'objet actuel en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et les informations de format spécifiques à la culture fournies par l'objet [IFormatProvider](../../iformatprovider/) spécifié.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Le format de chaîne. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | L'objet [IFormatProvider](../../iformatprovider/) fournissant les informations de format spécifiques à la culture. |

### Valeur de retour

La représentation sous forme de chaîne de l'objet actuel.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const méthode

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const méthode

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const méthode

```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Decimal](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)