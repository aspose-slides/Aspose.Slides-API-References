---
title: Cast_noexcept()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue une conversion sur les objets SmartPtr.
type: docs
weight: 2458
url: /fr/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) fonction

Effectue une conversion de type sur les objets [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type du pointeur cible. |
| TFrom | Type du pointeur source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Pointeur source. |

### Valeur de retour

Résultat de la conversion si la conversion est autorisée ou nullptr sinon.

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Structure [IsExceptionWrapper](../isexceptionwrapper/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)