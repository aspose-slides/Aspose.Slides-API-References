---
title: InternalAdd()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute le cookie spécifié à la collection.
type: docs
weight: 118
url: /fr/system.net/cookiecollection/internaladd/
---
## CookieCollection::InternalAdd(System::SharedPtr\<Cookie\>, bool) méthode

Ajoute le cookie spécifié à la collection.

```cpp
int32_t System::Net::CookieCollection::InternalAdd(System::SharedPtr<Cookie> cookie, bool isStrict)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| cookie | [System::SharedPtr](../../../system/sharedptr/)\<[Cookie](../../cookie/)\> | Le cookie à ajouter. |
| isStrict | **bool** | Vrai lorsque le cookie spécifié doit remplacer l'ancien, sinon faux. |

### Valeur de retour

0 lorsque le cookie spécifié a remplacé l'ancien, sinon 1.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Cookie](../../cookie/)
* Classe [CookieCollection](../)
* Espace de noms [System::Net](../../)
* Bibliothèque [Aspose.Slides](../../../)