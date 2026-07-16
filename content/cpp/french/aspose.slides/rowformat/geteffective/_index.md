---
title: GetEffective()
second_title: Référence API Aspose.Slides pour C++
description: Obtient les propriétés de mise en forme effectives d’une ligne de tableau avec l’héritage et les styles de tableau appliqués.
type: docs
weight: 1
url: /fr/aspose.slides/rowformat/geteffective/
---
## RowFormat::GetEffective() méthode


Obtient les propriétés de mise en forme effectives d’une ligne de tableau avec l’héritage et les styles de tableau appliqués.

```cpp
System::SharedPtr<IRowFormatEffectiveData> Aspose::Slides::RowFormat::GetEffective() override
```


### Valeur de retour

Un [IRowFormatEffectiveData](../../irowformateffectivedata/).
## Remarques



Cet exemple montre comment obtenir le format de remplissage effectif pour différentes parties logiques du tableau. Veuillez noter que la mise en forme des cellules a toujours une priorité plus élevée que la mise en forme des lignes, la ligne - plus haute que la colonne, la colonne - plus haute que le tableau entier. Ainsi, les propriétés CellFormatEffectiveData sont finalement toujours utilisées pour dessiner le tableau. Le code suivant n’est qu’un exemple d’API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
// Sortie et comparaison
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IRowFormatEffectiveData](../../irowformateffectivedata/)
* Classe [RowFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)