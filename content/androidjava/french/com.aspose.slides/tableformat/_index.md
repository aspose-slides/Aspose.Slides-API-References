---
title: TableFormat
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le format d'un tableau.
type: docs
url: /fr/com.aspose.slides/tableformat/
---
**Héritage:**
java.lang.Object, com.aspose.slides.DomObject

**Toutes les interfaces implémentées:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Représente le format d'un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Renvoie un objet de propriétés de remplissage de tableau. |
| [getTransparency()](#getTransparency--) | Obtient ou définit la transparence de la couleur de remplissage. |
| [setTransparency(float value)](#setTransparency-float-) | Obtient ou définit la transparence de la couleur de remplissage. |
| [getEffective()](#getEffective--) | Obtient les propriétés de formatage de tableau effectives avec héritage et styles de tableau appliqués. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Renvoie un objet de propriétés de remplissage de tableau. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Obtient ou définit la transparence de la couleur de remplissage. Lecture/écriture  float .

**Renvoie :**
float

### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Obtient ou définit la transparence de la couleur de remplissage. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Obtient les propriétés de formatage de tableau effectives avec héritage et styles de tableau appliqués.

--------------------

> ```
> Cet exemple montre comment obtenir le format de remplissage effectif pour différentes parties logiques d'un tableau.
>  Veuillez noter que le formatage des cellules a toujours une priorité supérieure à celui des lignes, les lignes sont supérieures aux colonnes, et les colonnes sont supérieures à l'ensemble du tableau.
>  Ainsi, les propriétés de CellFormatEffectiveData sont toujours utilisées pour dessiner le tableau. Le code suivant n'est qu'un exemple d'API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
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
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
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

Renvoie le parent IPresentationComponent. Lecture seule [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Renvoie :**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)