---
title: GetEffective
second_title: Référence de l'API Aspose.Sildes pour .NET
description: Obtient les propriétés de formatage de table effectives avec héritage et styles de table appliqués.
type: docs
weight: 30
url: /fr/aspose.slides/tableformat/geteffective/
---

## TableFormat.GetEffective method

Obtient les propriétés de formatage de table effectives avec héritage et styles de table appliqués.

```csharp
public ITableFormatEffectiveData GetEffective()
```

### Return Value

Un [`ITableFormatEffectiveData`](../../itableformateffectivedata).

### Examples

Cet exemple démontre comment obtenir le format de remplissage effectif pour différentes parties logiques de la table. Veuillez noter que le formatage des cellules a toujours une priorité plus élevée que le formatage des lignes, que le formatage des lignes a une priorité plus élevée que celui des colonnes, et que le formatage des colonnes a une priorité plus élevée que celui de la table entière. Ainsi, les propriétés de CellFormatEffectiveData sont toujours utilisées pour dessiner la table. Le code suivant est juste un exemple de l'API.

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

### See Also

* interface [ITableFormatEffectiveData](../../itableformateffectivedata)
* class [TableFormat](../../tableformat)
* namespace [Aspose.Slides](../../tableformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->