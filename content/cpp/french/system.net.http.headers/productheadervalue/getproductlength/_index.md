---
title: GetProductLength()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit une chaîne passée à partir de l'index spécifié en une instance de la classe ProductHeaderValue.
type: docs
weight: 105
url: /fr/system.net.http.headers/productheadervalue/getproductlength/
---
## ProductHeaderValue::GetProductLength(String, int32_t, System::SharedPtr\<ProductHeaderValue\>\&) method


Convertit une chaîne passée à partir de l'index spécifié en une instance de la classe [ProductHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::ProductHeaderValue::GetProductLength(String input, int32_t startIndex, System::SharedPtr<ProductHeaderValue> &parsedValue)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Une chaîne à analyser. |
| startIndex | **int32_t** | Une position de départ pour l'analyse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductHeaderValue](../)\>\& | Une instance où un objet analysé sera affecté. |

### Valeur de retour

Renvoie la longueur d'une sous-chaîne analysée, sinon 0.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ProductHeaderValue](../)
* Espace de noms [System::Net::Http::Headers](../../)
* Bibliothèque [Aspose.Slides](../../../)