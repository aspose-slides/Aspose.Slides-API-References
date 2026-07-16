---
title: GetTransferCodingLength()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit une chaîne passée depuis l'index spécifié en une instance de la classe TransferCodingHeaderValue.
type: docs
weight: 105
url: /fr/system.net.http.headers/transfercodingheadervalue/gettransfercodinglength/
---
## TransferCodingHeaderValue::GetTransferCodingLength(String, int32_t, const HeaderFunc\<System::SharedPtr\<TransferCodingHeaderValue\>\>\&, System::SharedPtr\<TransferCodingHeaderValue\>\&) méthode

Convertit une chaîne passée depuis l'index spécifié en une instance de la classe [TransferCodingHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::TransferCodingHeaderValue::GetTransferCodingLength(String input, int32_t startIndex, const HeaderFunc<System::SharedPtr<TransferCodingHeaderValue>> &transferCodingCreator, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Une chaîne à analyser. |
| startIndex | **int32_t** | Une position de départ pour l'analyse. |
| parsedValue | const [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\>\& | Une instance où un objet analysé sera assigné. |
| transferCodingCreator | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | Le délégué utilisé pour créer des instances de la classe [TransferCodingHeaderValue](../). |

### Valeur de retour

Renvoie la longueur d'une sous-chaîne analysée, sinon 0.

## Voir aussi

* Typedef [HeaderFunc](../../headerfunc/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [TransferCodingHeaderValue](../)
* Espace de noms [System::Net::Http::Headers](../../)
* Bibliothèque [Aspose.Slides](../../../)