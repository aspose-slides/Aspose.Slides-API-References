---
title: GetUrl()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Renvoie une URL vers un objet externe. Cette méthode est toujours appelée si ILinkEmbedController::GetObjectStoringLocation a renvoyé LinkEmbedDecision::Link et peut être appelée si ILinkEmbedController::GetObjectStoringLocation a renvoyé LinkEmbedDecision::Embed mais l'intégration est impossible. Elle peut être appelée plusieurs fois pour le même identifiant d'objet."
type: docs
weight: 14
url: /fr/aspose.slides.export/ilinkembedcontroller/geturl/
---
## ILinkEmbedController::GetUrl(int32_t, int32_t) méthode


Renvoie une URL vers un objet externe. Cette méthode est toujours appelée si [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) a renvoyé [LinkEmbedDecision::Link](../../linkembeddecision/) et peut être appelée si [ILinkEmbedController::GetObjectStoringLocation](../getobjectstoringlocation/) a renvoyé [LinkEmbedDecision::Embed](../../linkembeddecision/) mais l’intégration est impossible. Elle peut être appelée plusieurs fois pour le même identifiant d'objet.

```cpp
virtual System::String Aspose::Slides::Export::ILinkEmbedController::GetUrl(int32_t id, int32_t referrer)=0
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| id | **int32_t** | Identifiant de l'objet. Cet identifiant est unique pour l'ensemble de l'opération. |
| referrer | **int32_t** | Identifiant de l'objet référent ou 0, si l'objet est référencé par le document racine. Peut être utilisé pour générer un lien relatif. |

### Valeur de retour

URL de l'objet externe ou null si cet objet doit être ignoré.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [ILinkEmbedController](../)
* Espace de noms [Aspose::Slides::Export](../../)
* Bibliothèque [Aspose.Slides](../../../)