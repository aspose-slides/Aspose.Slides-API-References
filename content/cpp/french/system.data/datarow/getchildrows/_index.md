---
title: GetChildRows()
second_title: Référence API Aspose.Slides pour C++
description: Récupère les lignes qui sont considérées comme enfants via la relation spécifiée.
type: docs
weight: 27
url: /fr/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) méthode

Récupère les lignes qui sont considérées comme enfants via la relation spécifiée.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Objet Relation permettant de spécifier la relation ligne parent - ligne enfant. |

### Valeur de retour

[Array](../../../system/array/) des lignes enfants récupérées.

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [DataRow](../)
* Classe [DataRelation](../../datarelation/)
* Espace de noms [System::Data](../../)
* Bibliothèque [Aspose.Slides](../../../)