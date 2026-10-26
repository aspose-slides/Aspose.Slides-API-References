---
title: ChartDataCell
second_title: Référence de l'API Java pour Aspose.Slides pour Android
description: Représente une cellule pour les données de graphique.
type: docs
url: /fr/com.aspose.slides/chartdatacell/
---
**Héritage :**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)  
```
public class ChartDataCell implements IChartDataCell
```

Représente une cellule pour les données de graphique.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getRow()](#getRow--) | Renvoie l'indice de la ligne de la feuille de calcul dans laquelle la cellule se trouve. |
| [getColumn()](#getColumn--) | Renvoie l'indice de la colonne de la feuille de calcul dans laquelle la cellule se trouve. |
| [getValue()](#getValue--) | Obtient ou définit la valeur d'une cellule. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtient ou définit la valeur d'une cellule. |
| [getFormula()](#getFormula--) | Obtient ou définit la formule au format A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Obtient ou définit la formule au format A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Obtient ou définit la formule au format R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Obtient ou définit la formule au format R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Obtient la feuille de calcul. |
| [isHidden()](#isHidden--) | Détermine si la cellule est masquée. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Obtient ou définit le format d'affichage personnalisé des nombres et des dates. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Obtient ou définit le format d'affichage personnalisé des nombres et des dates. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Obtient ou définit le format d'affichage intégré des nombres et des dates. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Obtient ou définit le format d'affichage intégré des nombres et des dates. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Si la cellule contient une formule, la valeur sera mise à jour en fonction de cette formule. |

### getRow() {#getRow--}
```
public final int getRow()
```

Renvoie l'indice de la ligne de la feuille de calcul dans laquelle la cellule se trouve. Lecture seule int.

**Renvoie :**  
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

Renvoie l'indice de la colonne de la feuille de calcul dans laquelle la cellule se trouve. Lecture seule int.

**Renvoie :**  
int

### getValue() {#getValue--}
```
public final Object getValue()
```

Obtient ou définit la valeur d'une cellule. Lecture/écriture  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Gets or sets the value of a cell. Read/write  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Gets or sets the formula in A1-style.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Returns:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Gets or sets the formula in A1-style.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

Gets or sets the formula in R1C1-style.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Returns:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

Gets or sets the formula in R1C1-style.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

Gets the worksheet. Read-only [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Returns:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```
Determines whether the cell is hidden. Read-only boolean.

**Returns:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String.

**Returns:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

Gets or sets the custom display format of numbers and dates. If value is empty will be used PresetNumberFormat value. Read/write String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write byte.

--------------------

> ```
> 0	General
>  1	0
>  2	0.00
>  3	#,##0
>  4	#,##0.00
>  5	$#,##0;$-#,##0
>  6	$#,##0;[Red]$-#,##0
>  7	$#,##0.00;$-#,##0.00
>  8	$#,##0.00;[Red]$-#,##0.00
>  9	0%
>  10	0.00%
>  11	0.00E+00
>  12	# ?/?
>  13	# /
>  14	m/d/yy
>  15	d-mmm-yy
>  16	d-mmm
>  17	mmm-yy
>  18	h:mm AM/PM
>  19	h:mm:ss AM/PM
>  20	h:mm
>  21	h:mm:ss
>  22	m/d/yy h:mm
>  37	#,##0;-#,##0
>  38	#,##0;[Red]-#,##0
>  39	#,##0.00;-#,##0.00
>  40	#,##0.00;[Red]-#,##0.00
>  41	_ * #,##0_ ;_ * "_ ;_ @_
>  42	_ $* #,##0_ ;_ $* "_ ;_ @_
>  43	_ * #,##0.00_ ;_ * "??_ ;_ @_
>  44	_("$"* # ##0,00_);_("$"* (# ##0,00);_("$"* "-"??_);_(@_)
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Returns:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

Gets or sets the built-in display format of numbers and dates. Preset number must be in [0..22] or [37..49]. Read/write byte.

--------------------

> ```
> 0	General
>  1	0
>  2	0.00
>  3	#,##0
>  4	#,##0.00
>  5	$#,##0;$-#,##0
>  6	$#,##0;[Red]$-#,##0
>  7	$#,##0.00;$-#,##0.00
>  8	$#,##0.00;[Red]$-#,##0.00
>  9	0%
>  10	0.00%
>  11	0.00E+00
>  12	# ?/?
>  13	# /
>  14	m/d/yy
>  15	d-mmm-yy
>  16	d-mmm
>  17	mmm-yy
>  18	h:mm AM/PM
>  19	h:mm:ss AM/PM
>  20	h:mm
>  21	h:mm:ss
>  22	m/d/yy h:mm
>  37	#,##0;-#,##0
>  38	#,##0;[Red]-#,##0
>  39	#,##0.00;-#,##0.00
>  40	#,##0.00;[Red]-#,##0.00
>  41	_ * #,##0_ ;_ * "_ ;_ @_
>  42	_ $* #,##0_ ;_ $* "_ ;_ @_
>  43	_ * #,##0.00_ ;_ * "??_ ;_ @_
>  44	_("$"* # ##0,00_);_("$"* (# ##0,00);_("$"* "-"??_);_(@_)
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)

Si la cellule contient une formule, la valeur sera mise à jour en fonction de cette formule.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Si false, aucun calcul réel ne sera effectué. Utilisez true pour vérifier d'éventuelles exceptions. |