---
title: ToString()
second_title: Référence de l'API Aspose.Slides for C++
description: Convertit le GUID représenté par l'objet actuel en sa représentation sous forme de chaîne.
type: docs
weight: 79
url: /fr/system/guid/tostring/
---
## Guid::ToString() const méthode

Convertit le GUID représenté par l'objet actuel en sa représentation sous forme de chaîne.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const méthode

Convertit le GUID représenté par l'objet actuel en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié.

```cpp
String System::Guid::ToString(const String &format) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Le format à utiliser |

### Valeur de retour

La représentation sous forme de chaîne de la valeur GUID représentée par l'objet actuel

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const méthode

Convertit le GUID représenté par l'objet actuel en sa représentation sous forme de chaîne en utilisant le format de chaîne spécifié et la Culture.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [String](../../string/)\& | Le format à utiliser |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture à utiliser |

### Valeur de retour

La représentation sous forme de chaîne de la valeur GUID représentée par l'objet actuel

## Voir également

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Guid](../)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Espace de noms [System](../../)
* Library [Aspose.Slides](../../../)