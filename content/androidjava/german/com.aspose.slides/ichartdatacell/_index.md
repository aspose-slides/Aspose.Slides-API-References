---
title: IChartDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt eine Zelle für Diagrammdaten dar.
type: docs
url: /de/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

Stellt eine Zelle für Diagrammdaten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRow()](#getRow--) | Gibt den Index der Zeile des Arbeitsblatts zurück, in dem sich die Zelle befindet. |
| [getColumn()](#getColumn--) | Gibt den Index der Spalte des Arbeitsblatts zurück, in dem sich die Zelle befindet. |
| [getValue()](#getValue--) | Gibt den Wert einer Zelle zurück oder legt ihn fest. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gibt den Wert einer Zelle zurück oder legt ihn fest. |
| [getFormula()](#getFormula--) | Gibt die Formel im A1-Stil zurück oder legt sie fest. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Gibt die Formel im A1-Stil zurück oder legt sie fest. |
| [getR1C1Formula()](#getR1C1Formula--) | Gibt die Formel im R1C1-Stil zurück oder legt sie fest. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Gibt die Formel im R1C1-Stil zurück oder legt sie fest. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Gibt das Arbeitsblatt zurück. |
| [isHidden()](#isHidden--) | Bestimmt, ob die Zelle ausgeblendet ist. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Gibt das benutzerdefinierte Anzeigeformat für Zahlen und Datumswerte zurück oder legt es fest. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Gibt das benutzerdefinierte Anzeigeformat für Zahlen und Datumswerte zurück oder legt es fest. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Gibt das integrierte Anzeigeformat für Zahlen und Datumswerte zurück oder legt es fest. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Gibt das integrierte Anzeigeformat für Zahlen und Datumswerte zurück oder legt es fest. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Wenn die Zelle eine Formel enthält, wird der Wert basierend auf dieser Formel aktualisiert. |
### getRow() {#getRow--}
```
public abstract int getRow()
```


Gibt den Index der Zeile des Arbeitsblatts zurück, in dem sich die Zelle befindet. Nur-Lesen int.

**Rückgabewert:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


Gibt den Index der Spalte des Arbeitsblatts zurück, in dem sich die Zelle befindet. Nur-Lesen int.

**Rückgabewert:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Gibt den Wert einer Zelle zurück oder legt ihn fest. Lesen/Schreiben Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Rückgabewert:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Gibt den Wert einer Zelle zurück oder legt ihn fest. Lesen/Schreiben Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Gibt die Formel im A1-Stil zurück oder legt sie fest.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Rückgabewert:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Gibt die Formel im A1-Stil zurück oder legt sie fest.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```


Gibt die Formel im R1C1-Stil zurück oder legt sie fest.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Rückgabewert:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```


Gibt die Formel im R1C1-Stil zurück oder legt sie fest.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```


Gibt das Arbeitsblatt zurück. Nur-Lesen [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Rückgabewert:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Bestimmt, ob die Zelle ausgeblendet ist. Nur-Lesen boolean.

**Rückgabewert:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```


Gibt das benutzerdefinierte Anzeigeformat für Zahlen und Datumswerte zurück oder legt es fest. Wenn der Wert leer ist, wird der Wert von PresetNumberFormat verwendet. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```


Gibt das benutzerdefinierte Anzeigeformat für Zahlen und Datumswerte zurück oder legt es fest. Wenn der Wert leer ist, wird der Wert von PresetNumberFormat verwendet. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```


Gibt das integrierte Anzeigeformat für Zahlen und Datumswerte zurück oder legt es fest. Der voreingestellte Nummerwert muss in [0..22] oder [37..49] liegen. Lesen/Schreiben byte.

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
>  44	_ $* #,##0.00_ ;_ $* "??_ ;_ @_
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Rückgabewert:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```


Gibt das integrierte Anzeigeformat für Zahlen und Datumswerte zurück oder legt es fest. Der voreingestellte Nummerwert muss in [0..22] oder [37..49] liegen. Lesen/Schreiben byte.

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
>  44	_ $* #,##0.00_ ;_ $* "??_ ;_ @_
>  45	mm:ss
>  46	h :mm:ss
>  47	mm:ss.0
>  48	##0.0E+00
>  49	@
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```


Wenn die Zelle eine Formel enthält, wird der Wert basierend auf dieser Formel aktualisiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| updateValues | boolean | Wenn false, wird keine eigentliche Berechnung durchgeführt. Verwenden Sie true, um mögliche Ausnahmen zu prüfen. |