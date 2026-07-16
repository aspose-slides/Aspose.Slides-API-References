---
title: GetEffective()
second_title: Référence API Aspose.Slides pour C++
description: Récupère les propriétés de formatage de tableau effectives avec héritage et styles de tableau appliqués.
type: docs
weight: 40
url: /fr/aspose.slides/tableformat/geteffective/
---
## TableFormat::GetEffective() méthode


Récupère les propriétés de formatage de tableau effectives avec l'héritage et les styles de tableau appliqués.

```cpp
System::SharedPtr<ITableFormatEffectiveData> Aspose::Slides::TableFormat::GetEffective() override
```


### Valeur de retour

Un [ITableFormatEffectiveData](../../itableformateffectivedata/).

## Remarques



Cet exemple montre comment obtenir le format de remplissage effectif pour différentes parties logiques du tableau. Veuillez noter que le formatage des cellules a toujours une priorité plus élevée que le formatage des lignes, les lignes étant supérieures aux colonnes, les colonnes étant supérieures à l'ensemble du tableau. Ainsi, les propriétés CellFormatEffectiveData sont finalement toujours utilisées pour dessiner le tableau. Le code suivant n'est qu'un exemple d'API. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto tbl = AsCast<Table>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto tableFillFormatEffective = tbl->get_TableFormat()->GetEffective()->get_FillFormat();
auto rowFillFormatEffective = tbl->get_Rows()->idx_get(0)->get_RowFormat()->GetEffective()->get_FillFormat();
auto columnFillFormatEffective = tbl->get_Columns()->idx_get(0)->get_ColumnFormat()->GetEffective()->get_FillFormat();
auto cellFillFormatEffective = tbl->idx_get(0, 0)->get_CellFormat()->GetEffective()->get_FillFormat();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ITableFormatEffectiveData](../../itableformateffectivedata/)
* Classe [TableFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)