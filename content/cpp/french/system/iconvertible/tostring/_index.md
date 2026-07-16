---
title: ToString()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Convertit la valeur de cette instance en un System::String équivalent en utilisant les informations de formatage spécifiques à la culture spécifiées."
type: docs
weight: 196
url: /fr/system/iconvertible/tostring/
---
## IConvertible::ToString(System::SharedPtr\<System::IFormatProvider\>) méthode


Convertit la valeur de cette instance en un [System::String](../../string/) équivalent en utilisant les informations de formatage spécifiques à la culture spécifiées.

```cpp
virtual System::String System::IConvertible::ToString(System::SharedPtr<System::IFormatProvider> provider)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Une implémentation d'interface [System::IFormatProvider](../../iformatprovider/) qui fournit les informations de formatage spécifiques à la culture. |

### Valeur de retour

Une instance [System::String](../../string/) équivalente à la valeur de cette instance.

## IConvertible::ToString() const méthode


Analogue de la méthode C# [Object.ToString()](../../object/tostring/). Permet de convertir des objets personnalisés en chaîne de caractères.

```cpp
virtual String System::Object::ToString() const
```


### Valeur de retour

Représentation [String](../../string/) telle que fournie par la classe finale.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [IConvertible](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)