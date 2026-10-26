---
title: Cast()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue une conversion sur les objets SmartPtr.
type: docs
weight: 2471
url: /fr/system/cast/
---
## System::Cast(SmartPtr\<TFrom\> const\&) fonction

Effectue une conversion de type sur les objets [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type de pointeur cible. |
| TFrom | Type de pointeur source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Pointeur source. |

### Valeur de retour

Résultat de la conversion si la conversion est autorisée.

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Structure [IsExceptionWrapper](../isexceptionwrapper/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)