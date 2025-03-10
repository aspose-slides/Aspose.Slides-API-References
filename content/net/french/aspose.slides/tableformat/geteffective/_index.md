---
title: GetEffective
second_title: Référence de l'API Aspose.Slides pour .NET
description: Obtient les propriétés de formatage de tableau efficaces avec lhéritage et les styles de tableau appliqués.
type: docs
weight: 20
url: /fr/aspose.slides/tableformat/geteffective/
---
## TableFormat.GetEffective method

Obtient les propriétés de formatage de tableau efficaces avec l'héritage et les styles de tableau appliqués.

```csharp
public ITableFormatEffectiveData GetEffective()
```

### Return_Value

UN[`ITableFormatEffectiveData`](../../itableformateffectivedata).

### Exemples

Cet exemple montre comment obtenir un format de remplissage efficace pour différentes parties logiques de tableau. Veuillez noter que le formatage des cellules a toujours une priorité plus élevée que le formatage des lignes, la ligne - plus élevée que la colonne, la colonne - plus élevée que le tableau entier. Donc, finalement, les propriétés CellFormatEffectiveData sont toujours utilisées pour dessiner la table. Le code suivant n'est qu'un exemple d'API.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    ITable tbl = pres.Slides[0].Shapes[0] as Table;
    IFillFormatEffectiveData tableFillFormatEffective = tbl.TableFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData rowFillFormatEffective = tbl.Rows[0].RowFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData columnFillFormatEffective = tbl.Columns[0].ColumnFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData cellFillFormatEffective = tbl[0, 0].CellFormat.GetEffective().FillFormat;
    /* Output and comparison */
}
```

### Voir également

* interface [ITableFormatEffectiveData](../../itableformateffectivedata)
* class [TableFormat](../../tableformat)
* espace de noms [Aspose.Slides](../../tableformat)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
