---
title: GetEffective()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient les propriétés effectives de mise en forme des colonnes de tableau avec héritage et styles de tableau appliqués.
type: docs
weight: 1
url: /fr/aspose.slides/columnformat/geteffective/
---
## ColumnFormat::GetEffective() method


Obtient les propriétés effectives de mise en forme des colonnes de tableau avec héritage et styles de tableau appliqués.

```cpp
System::SharedPtr<IColumnFormatEffectiveData> Aspose::Slides::ColumnFormat::GetEffective() override
```


### Valeur de retour

Un [IColumnFormatEffectiveData](../../icolumnformateffectivedata/).
## Remarques



Cet exemple montre comment obtenir le format de remplissage effectif pour différentes parties logiques du tableau. Veuillez noter que la mise en forme des cellules a toujours une priorité plus élevée que la mise en forme des lignes, les lignes plus que les colonnes, les colonnes plus que le tableau entier. Ainsi, les propriétés CellFormatEffectiveData sont toujours utilisées pour dessiner le tableau. Le code suivant n'est qu'un exemple d'API. 
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
* Classe [IColumnFormatEffectiveData](../../icolumnformateffectivedata/)
* Classe [ColumnFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)