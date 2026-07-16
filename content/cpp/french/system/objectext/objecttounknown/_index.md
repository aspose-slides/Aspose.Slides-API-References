---
title: ObjectToUnknown()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit Object en type inconnu, en gérant à la fois le type pointeur intelligent et les situations de valeur encapsulée.
type: docs
weight: 131
url: /fr/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) méthode


Convertit [Object](../../object/) en type inconnu, en gérant à la fois le type pointeur intelligent et les situations de valeur encapsulée.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type vers lequel convertir [Object](../../object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) à convertir. |

### Valeur de retour

Valeur non encapsulée ou pointeur converti.

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) méthode


Convertit [Object](../../object/) en type inconnu, en gérant à la fois le type pointeur intelligent et les situations de valeur encapsulée.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type vers lequel convertir [Object](../../object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) à convertir. |

### Valeur de retour

Valeur non encapsulée ou pointeur converti.

## Voir aussi

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Structure [IsSmartPtr](../../issmartptr/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)