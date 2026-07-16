---
title: idx_get()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Renvoie un cookie de la collection de cookies à l'index spécifié.
type: docs
weight: 40
url: /fr/system.net/cookiecollection/idx_get/
---
## CookieCollection::idx_get(int32_t) méthode

Retourne un cookie de la collection de cookies à l'index spécifié.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(int32_t index)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| index | **int32_t** | L'index du cookie qui doit être retourné. |

### Valeur de retour

Un cookie à l'index spécifié.

## CookieCollection::idx_get(String) méthode

Retourne un cookie de la collection de cookies selon le nom spécifié.

```cpp
System::SharedPtr<Cookie> System::Net::CookieCollection::idx_get(String name)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | Le nom du cookie qui doit être retourné. |

### Valeur de retour

Un cookie de la collection de cookies selon le nom spécifié lorsqu'il est trouvé, sinon nullptr.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Cookie](../../cookie/)
* Classe [CookieCollection](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)