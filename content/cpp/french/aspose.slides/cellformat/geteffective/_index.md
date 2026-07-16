---
title: GetEffective()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les propriétés de formatage effectif des cellules de tableau avec héritage et styles de tableau appliqués.
type: docs
weight: 118
url: /fr/aspose.slides/cellformat/geteffective/
---
## CellFormat::GetEffective() méthode


Obtient les propriétés de formatage de cellule de tableau effectives avec héritage et styles de tableau appliqués.

```cpp
System::SharedPtr<ICellFormatEffectiveData> Aspose::Slides::CellFormat::GetEffective() override
```


### Valeur de retour

Un [ICellFormatEffectiveData](../../icellformateffectivedata/).
## Remarques



Cet exemple montre comment obtenir le format de remplissage effectif pour différentes parties logiques du tableau. Veuillez noter que le formatage des cellules a toujours une priorité plus élevée que le formatage des lignes, les lignes - plus haut que les colonnes, les colonnes - plus haut que le tableau entier. Ainsi, les propriétés CellFormatEffectiveData sont finalement toujours utilisées pour dessiner le tableau. Le code suivant n'est qu'un exemple d'API. 
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
* Classe [ICellFormatEffectiveData](../../icellformateffectivedata/)
* Classe [CellFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)