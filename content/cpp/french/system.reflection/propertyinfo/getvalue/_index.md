---
title: GetValue()
second_title: Référence de l'API Aspose.Slides for C++
description: Obtient la valeur de la propriété à partir d'un objet spécifique.
type: docs
weight: 1
url: /fr/system.reflection/propertyinfo/getvalue/
---
## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>) méthode


Obtient la valeur de la propriété à partir d'un objet spécifique.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) pour lire la propriété depuis. |

### Valeur de retour

Valeur de la propriété spécifiée pour l'objet spécifié.

## PropertyInfo::GetValue(System::SharedPtr\<System::Object\>, System::ArrayPtr\<System::SharedPtr\<System::Object\>\>) méthode


Obtient la valeur de la propriété à partir d'un objet spécifique.

```cpp
System::SharedPtr<System::Object> System::Reflection::PropertyInfo::GetValue(System::SharedPtr<System::Object> obj, System::ArrayPtr<System::SharedPtr<System::Object>> indexer)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | [Object](../../../system/object/) pour lire la propriété depuis. |
| indexer | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\> | Ce sont des valeurs d'index facultatives pour les propriétés indexées. Pour les propriétés non indexées, cette valeur doit être null. |

### Valeur de retour

Valeur de la propriété spécifiée pour l'objet spécifié.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Object](../../../system/object/)
* Classe [PropertyInfo](../)
* Espace de noms [System::Reflection](../../)
* Bibliothèque [Aspose.Slides](../../../)