---
title: GetNameValueListLength()
second_title: Référence API Aspose.Slides pour C++
description: Convertit une chaîne passée à partir de l'index spécifié en une collection d'instances de la classe NameValueHeaderValue et renvoie la longueur d'une sous-chaîne analysée.
type: docs
weight: 131
url: /fr/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) method


Convertit une chaîne passée à partir de l'index spécifié en une collection d'instances de la classe NameValueHeaderValue et renvoie la longueur d'une sous-chaîne analysée.

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | Une chaîne à analyser. |
| startIndex | **int32_t** | Une position de départ pour l'analyse. |
| delimiter | char16_t | Une chaîne utilisée pour délimiter les éléments dans la chaîne spécifiée. |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | Le paramètre de sortie où une collection analysée sera affectée. |

### Valeur de retour

La longueur d'une sous-chaîne analysée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [ObjectCollection](../../objectcollection/)
* Classe [NameValueHeaderValue](../)
* Espace de noms [System::Net::Http::Headers](../../)
* Bibliothèque [Aspose.Slides](../../../)