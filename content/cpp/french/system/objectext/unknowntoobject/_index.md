---
title: UnknownToObject()
second_title: Référence API Aspose.Slides pour C++
description: Convertit le type inconnu en Object, en gérant à la fois les situations de type pointeur intelligent et de type valeur.
type: docs
weight: 118
url: /fr/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) méthode

Convertit le type inconnu en [Object](../../object/), en gérant à la fois les situations de type pointeur intelligent et de type valeur.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type à convertir en [Object](../../object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) à convertir. |

### Valeur de retour

Pointeur intelligent vers [Object](../../object/) étant soit le pointeur converti, soit la valeur encapsulée.

## ObjectExt::UnknownToObject(const T\&) méthode

Convertit le type inconnu en [Object](../../object/), en gérant à la fois les situations de type pointeur intelligent et de type valeur.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type à convertir en [Object](../../object/). |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) à convertir. |

### Valeur de retour

Pointeur intelligent vers [Object](../../object/) étant soit le pointeur converti, soit la valeur encapsulée.

## Voir aussi

* Classe [SmartPtr](../../smartptr/)
* Classe [Object](../../object/)
* Classe [ObjectExt](../)
* Structure [IsSmartPtr](../../issmartptr/)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)