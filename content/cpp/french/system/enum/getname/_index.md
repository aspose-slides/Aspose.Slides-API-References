---
title: GetName()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le nom de la constante d'énumération qui possède la valeur spécifiée.
type: docs
weight: 40
url: /fr/system/enum/getname/
---
## Enum::GetName(T) méthode

Renvoie le nom de la constante d'énumération qui a la valeur spécifiée.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T | La valeur de la constante d'énumération dont le nom doit être renvoyé |

### Valeur de retour

Le nom de la constante d'énumération spécifiée

## Voir aussi

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)