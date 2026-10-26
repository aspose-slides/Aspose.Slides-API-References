---
title: ForceStaticCast()
second_title: Référence de l'API Aspose.Slides pour C++
description: Effectue un cast statique réel sur les objets SmartPtr.
type: docs
weight: 2549
url: /fr/system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) fonction

Effectue un cast statique réel sur les objets [SmartPtr](../smartptr/).

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
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

Résultat du cast si le cast est autorisé, sinon le comportement est indéfini.

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Structure [CastResult](../castresult/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)