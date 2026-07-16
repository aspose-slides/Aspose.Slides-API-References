---
title: GetEntityTagLength()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit une chaîne passée à partir de l'index spécifié en une instance de la classe EntityTagHeaderValue.
type: docs
weight: 118
url: /fr/system.net.http.headers/entitytagheadervalue/getentitytaglength/
---
## EntityTagHeaderValue::GetEntityTagLength(String, int32_t, System::SharedPtr\<EntityTagHeaderValue\>\&) méthode


Convertit une chaîne passée à partir de l'index spécifié en une instance de la classe [EntityTagHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::EntityTagHeaderValue::GetEntityTagLength(String input, int32_t startIndex, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Une chaîne à analyser. |
| startIndex | **int32_t** | Une position de départ pour l'analyse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | Une instance où un objet analysé sera assigné. |

### Valeur de retour

La longueur d'une sous-chaîne analysée, sinon 0.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [EntityTagHeaderValue](../)
* Espace de noms [System::Net::Http::Headers](../../)
* Bibliothèque [Aspose.Slides](../../../)