---
title: InsertClone()
second_title: Référence de l'API Aspose.Slides for C++
description: Insère une copie d’une diapositive maître spécifiée à la position indiquée de la collection. Les diapositives de mise en page liées seront également copiées.
type: docs
weight: 66
url: /fr/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) méthode


Insère une copie d’une diapositive maître spécifiée à la position indiquée de la collection. Les diapositives de mise en page liées seront également copiées.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Indice de la nouvelle diapositive. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) à cloner. |

### Valeur de retour

Diapositive maître insérée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterSlide](../../imasterslide/)
* Classe [IMasterSlideCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)