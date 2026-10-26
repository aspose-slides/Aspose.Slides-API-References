---
title: MergeCells()
second_title: Référence de l'API Aspose.Slides pour C++
description: Fusionne les cellules adjacentes.
type: docs
weight: 261
url: /fr/aspose.slides/itable/mergecells/
---
## ITable::MergeCells(System::SharedPtr\<ICell\>, System::SharedPtr\<ICell\>, bool) méthode

Fusionne les cellules adjacentes.

```cpp
virtual System::SharedPtr<ICell> Aspose::Slides::ITable::MergeCells(System::SharedPtr<ICell> cell1, System::SharedPtr<ICell> cell2, bool allowSplitting)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| cell1 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) à fusionner. |
| cell2 | [System::SharedPtr](../../../system/sharedptr/)\<[ICell](../../icell/)\> | [Cell](../../cell/) à fusionner. |
| allowSplitting | **bool** | Vrai pour autoriser la division des cellules. |

### Valeur de retour

Cellule fusionnée.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICell](../../icell/)
* Classe [ITable](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)