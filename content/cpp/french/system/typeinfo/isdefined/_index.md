---
title: IsDefined()
second_title: Référence API Aspose.Slides pour C++
description: NON IMPLEMENTÉ. Indique si un ou plusieurs attributs du type spécifié ou de ses types dérivés sont appliqués à cet élément.
type: docs
weight: 157
url: /fr/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const méthode

NON IMPLEMENTÉ. Indique si un ou plusieurs attributs du type spécifié ou de ses types dérivés sont appliqués à cet élément.

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Le type d'attribut personnalisé à rechercher. La recherche inclut les types dérivés. |
| inherit | **bool** | true pour rechercher dans la chaîne d'héritage de cet élément afin de trouver les attributs ; sinon, false. Ce paramètre est ignoré pour les propriétés et les événements. |

### Valeur de retour

true si une ou plusieurs instances de attributeType ou de l'un de ses types dérivés sont appliquées à cet élément ; sinon, false.

## Voir aussi

* Classe [TypeInfo](../)
* Espace de noms [System](../../)
* Bibliothèque [Aspose.Slides](../../../)