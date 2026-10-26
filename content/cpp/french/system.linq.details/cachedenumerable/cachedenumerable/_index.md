---
title: CachedEnumerable()
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 1
url: /fr/system.linq.details/cachedenumerable/cachedenumerable/
---
## CachedEnumerable::CachedEnumerable(System::Func\<bool\>) constructeur



```cpp
System::Linq::Details::CachedEnumerable<TItem>::CachedEnumerable(System::Func<bool> requestNext)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| requestNext | [System::Func](../../../system/func/)\<**bool**\> | callback qui est appelé lorsqu'un élément suivant est nécessaire. le callback doit utiliser la méthode Add pour insérer l'élément suivant ou renvoyer false lorsqu'il n'y a plus d'éléments |

## Voir aussi

* Classe [Func](../../../system/func/)
* Classe [CachedEnumerable](../)
* Espace de noms [System::Linq::Details](../../)
* Bibliothèque [Aspose.Slides](../../../)