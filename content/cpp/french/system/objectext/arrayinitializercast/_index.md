---
title: ArrayInitializerCast()
second_title: Référence API Aspose.Slides pour C++
description: Convertit les valeurs fondamentales d'un tableau (ce que C# fait implicitement mais C++ ne le fait apparemment pas).
type: docs
weight: 209
url: /fr/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) méthode

Convertit les valeurs fondamentales d'un tableau (ce que C# fait implicitement mais C++ ne le fait apparemment pas).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| To | Target type. |
| From | Source types. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| args | From ... | Values to convert and push to target array. |

### Valeur de retour

[Array](../../array/) contenant des copies converties de tous les arguments dans le même ordre.

## Voir aussi

* Classe [ObjectExt](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)