---
title: ToType()
second_title: Référence API Aspose.Slides pour C++
description: "Convertit la valeur de cette instance en un System::Object du System::Type spécifié qui possède une valeur équivalente, en utilisant les informations de formatage spécifiques à la culture spécifiées."
type: docs
weight: 209
url: /fr/system/iconvertible/totype/
---
## IConvertible::ToType(const TypeInfo\&, System::SharedPtr\<System::IFormatProvider\>) méthode

Convertit la valeur de cette instance en un [System::Object](../../object/) du System::Type spécifié qui possède une valeur équivalente, en utilisant les informations de formatage spécifiques à la culture spécifiées.

```cpp
virtual System::SharedPtr<System::Object> System::IConvertible::ToType(const TypeInfo &conversionType, System::SharedPtr<System::IFormatProvider> provider)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| conversionType | const [TypeInfo](../../typeinfo/)\& | Le System::Type vers lequel la valeur de cette instance est convertie. |
| provider | [System::SharedPtr](../../sharedptr/)\<[System::IFormatProvider](../../iformatprovider/)\> | Une implémentation d'interface [System::IFormatProvider](../../iformatprovider/) qui fournit des informations de formatage spécifiques à la culture. |

### Valeur de retour

Une instance [System::Object](../../object/) de type conversionType dont la valeur est équivalente à la valeur de cette instance.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Object](../../object/)
* Classe [TypeInfo](../../typeinfo/)
* Classe [IFormatProvider](../../iformatprovider/)
* Classe [IConvertible](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)