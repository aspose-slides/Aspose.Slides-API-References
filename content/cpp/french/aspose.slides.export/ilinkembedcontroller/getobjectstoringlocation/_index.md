---
title: GetObjectStoringLocation()
second_title: Référence de l'API Aspose.Slides pour C++
description: Détermine où l'objet doit être stocké. Cette méthode est appelée une fois pour chaque identifiant d'objet. Il n'est pas garanti qu'il n'y aura pas deux objets avec les mêmes données, semanticName et contentType mais avec des identifiants différents.
type: docs
weight: 1
url: /fr/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) méthode


Détermine où l'objet doit être stocké. Cette méthode est appelée une fois pour chaque identifiant d'objet. Il n'est pas garanti qu'il n'y aura pas deux objets avec les mêmes données, semanticName et contentType mais avec des identifiants différents.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| id | **int32_t** | Identifiant d'objet. Cet identifiant est unique pour l'opération de sauvegarde. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Données binaires de l'objet. Ce paramètre peut être nul, si les données binaires de l'objet n'ont pas encore été générées. |
| semanticName | [System::String](../../../system/string/) | Un texte court, décrivant la signification de l'objet. Le contrôleur peut l'utiliser comme partie du nom externe de l'objet, mais il appartient au répartiteur de s'assurer que les noms seront uniques et ne contiendront que les caractères autorisés. |
| contentType | [System::String](../../../system/string/) | Type MIME de l'objet. |
| recomendedExtension | [System::String](../../../system/string/) | Extension de nom de fichier, recommandée pour ce type MIME. |

### Valeur de retour

Décision

## Voir également

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)