---
title: GetDescription()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie le nom de la constante d'énumération qui possède la valeur spécifiée.
type: docs
weight: 53
url: /fr/system/enum/getdescription/
---
## Enum::GetDescription(T) méthode


Renvoie le nom de la constante d'énumération qui possède la valeur spécifiée.

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetDescription(T value)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | T | La valeur de la constante d'énumération dont le nom doit être renvoyé |

### Valeur de retour

Le nom de la constante enum spécifiée

## Voir aussi

* Typedef [UnderlyingType](../underlyingtype/)
* Classe [String](../../string/)
* Structure [Enum](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)