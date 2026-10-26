---
title: ConstCast()
second_title: Référence de l'API Aspose.Slides pour C++
description: Fin des conversions obsolètes.
type: docs
weight: 2536
url: /fr/system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) fonction


Fin des conversions obsolètes.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| TTo | Type du pointeur cible. |
| TFrom | Type du pointeur source. |

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Pointeur source. |

### Valeur de retour

Résultat du cast si le cast est autorisé ou nullptr sinon.
## Remarques


Effectue un const cast sur les objets [SmartPtr](../smartptr/). 
## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Structure [CastResult](../castresult/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)