---
title: MakeRelative()
second_title: Référence API Aspose.Slides pour C++
description: Détermine la différence entre deux instances Uri.
type: docs
weight: 365
url: /fr/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) méthode

Détermine la différence entre deux [Uri](../) instances.

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | L'URI à comparer à l'URI actuel |

### Valeur de retour

Si le nom d'hôte et le schéma des URI représentés par l'objet actuel et **toUri** sont identiques, alors cette méthode retourne un [String](../../string/) qui représente un [Uri](../) relatif, qui ajouté à l'instance URI actuelle donne **toUri**. Si le nom d'hôte ou le schéma diffèrent, alors cette méthode retourne un [String](../../string/) qui représente le paramètre **uri**.

## Voir aussi

* Typedef [SharedPtr](../../sharedptr/)
* Classe [String](../../string/)
* Classe [Uri](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)