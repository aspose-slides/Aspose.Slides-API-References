---
title: ColumnFormat
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Représente le format d’une colonne de tableau.
type: docs
url: /fr/com.aspose.slides/columnformat/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Représente le format d’une colonne de tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEffective()](#getEffective--) | Obtient les propriétés de format effectives d’une colonne de tableau, avec l’héritage et les styles de tableau appliqués. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

Obtient les propriétés de format effectives d’une colonne de tableau, avec l’héritage et les styles de tableau appliqués.

--------------------

> ```
> Cet exemple montre comment obtenir le format de remplissage effectif pour différentes parties logiques du tableau.
>  Veuillez noter que le formatage des cellules a toujours une priorité supérieure au formatage des lignes, les lignes sont supérieures aux colonnes, les colonnes sont supérieures à l’ensemble du tableau.
>  Ainsi, les propriétés CellFormatEffectiveData sont finalement toujours utilisées pour dessiner le tableau. Le code suivant n’est qu’un exemple d’API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
**Returns:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - A [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Read-only long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()

Returns parent IPresentationComponent. Read-only [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Returns:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)