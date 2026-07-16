---
title: RegisterPrefix()
second_title: Référence de l'API Aspose.Slides pour C++
description: Enregistre le descendant WebRequest pour l'URI spécifié.
type: docs
weight: 92
url: /fr/system.net/webrequest/registerprefix/
---
## WebRequest::RegisterPrefix(String, System::SharedPtr\<IWebRequestCreate\>) méthode


Enregistre le descendant [WebRequest](../) pour l'URI spécifié.

```cpp
static bool System::Net::WebRequest::RegisterPrefix(String prefix, System::SharedPtr<IWebRequestCreate> creator)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | L'URI ou le préfixe d'URI. |
| creator | [System::SharedPtr](../../../system/sharedptr/)\<[IWebRequestCreate](../../iwebrequestcreate/)\> | Crée de nouvelles instances de la classe [WebRequest](../). |

### Valeur de retour

True lorsque le descendant [WebRequest](../) est enregistré avec succès pour l'URI spécifié, sinon false.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [IWebRequestCreate](../../iwebrequestcreate/)
* Classe [WebRequest](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)