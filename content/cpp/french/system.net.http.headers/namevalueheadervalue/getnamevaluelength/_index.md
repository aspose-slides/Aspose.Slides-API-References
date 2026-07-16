---
title: GetNameValueLength()
second_title: Référence API Aspose.Slides pour C++
description: Convertit une chaîne transmise à partir de l'index spécifié en une instance de la classe NameValueHeaderValue.
type: docs
weight: 118
url: /fr/system.net.http.headers/namevalueheadervalue/getnamevaluelength/
---
## NameValueHeaderValue::GetNameValueLength(String, int32_t, System::SharedPtr\<NameValueHeaderValue\>\&) méthode


Convertit une chaîne transmise à partir de l'index spécifié en une instance de la classe [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Une chaîne à analyser. |
| startIndex | **int32_t** | Une position de départ pour l'analyse. |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Une instance où l'objet analysé sera affecté. |

### Valeur de retour

Renvoie la longueur d'une sous-chaîne analysée, sinon 0.

## NameValueHeaderValue::GetNameValueLength(String, int32_t, HeaderFunc\<System::SharedPtr\<NameValueHeaderValue\>\>, System::SharedPtr\<NameValueHeaderValue\>\&) méthode


Convertit une chaîne transmise à partir de l'index spécifié en une instance de la classe [NameValueHeaderValue](../).

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueLength(String input, int32_t startIndex, HeaderFunc<System::SharedPtr<NameValueHeaderValue>> nameValueCreator, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Une chaîne à analyser. |
| startIndex | **int32_t** | Une position de départ pour l'analyse. |
| nameValueCreator | [HeaderFunc](../../headerfunc/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\> | Une fonction utilisée pour créer de nouvelles instances de la classe [NameValueHeaderValue](../). |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | Une instance où l'objet analysé sera affecté. |

### Valeur de retour

Renvoie la longueur d'une sous-chaîne analysée, sinon 0.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [HeaderFunc](../../headerfunc/)
* Classe [String](../../../system/string/)
* Classe [NameValueHeaderValue](../)
* Espace de noms [System::Net::Http::Headers](../../)
* Bibliothèque [Aspose.Slides](../../../)