---
title: MakeRelativeUri()
second_title: Référence API Aspose.Slides pour C++
description: Détermine la différence entre les URI représentés par l'objet actuel et les objets Uri spécifiés.
type: docs
weight: 352
url: /fr/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) méthode

Détermine la différence entre les URI représentés par l'objet actuel et les objets [Uri](../) spécifiés.

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Le comparand |

### Valeur retournée

Si le nom d'hôte et le schéma des URI représentés par l'objet actuel et **toUri** sont identiques, alors cette méthode renvoie un [Uri](../) relatif qui, lorsqu'il est ajouté à l'instance URI actuelle, produit **toUri**. Si le nom d'hôte ou le schéma diffèrent, alors cette méthode renvoie un objet [Uri](../) qui représente le paramètre **uri**.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Uri](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)