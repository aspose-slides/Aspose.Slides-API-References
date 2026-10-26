---
title: GetDateTimeFormats()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l'objet actuel formaté avec l'un des spécificateurs de format de date et d'heure standard.
type: docs
weight: 547
url: /fr/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const méthode


Renvoie un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l'objet actuel formaté avec l'un des spécificateurs de format de date et d'heure standard.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const méthode


Renvoie un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l'objet actuel formaté avec le spécificateur de format de date et d'heure standard spécifié.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | char_t | Spécificateur de format de date et d'heure standard. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const méthode


Renvoie un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l'objet actuel formaté avec l'un des spécificateurs de format de date et d'heure standard et le fournisseur de format spécifié.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const méthode


Renvoie un tableau de chaînes où chaque élément est la représentation sous forme de chaîne de l'objet actuel formaté avec le spécificateur de format de date et d'heure standard spécifié et le fournisseur de format.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | char_t | Spécificateur de format de date et d'heure standard. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Fournisseur de format. |

## Voir aussi

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [DateTime](../)
* Classe [IFormatProvider](../../iformatprovider/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)