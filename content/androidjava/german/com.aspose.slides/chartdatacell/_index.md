---
title: ChartDataCell
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Zelle für Diagrammdaten dar.
type: docs
url: /de/com.aspose.slides/chartdatacell/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

Stellt eine Zelle für Diagrammdaten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRow()](#getRow--) | Gibt den Index der Zeile des Arbeitsblatts zurück, in der sich die Zelle befindet. |
| [getColumn()](#getColumn--) | Gibt den Index der Spalte des Arbeitsblatts zurück, in der sich die Zelle befindet. |
| [getValue()](#getValue--) | Liest oder setzt den Wert einer Zelle. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Liest oder setzt den Wert einer Zelle. |
| [getFormula()](#getFormula--) | Liest oder setzt die Formel im A1-Stil. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Liest oder setzt die Formel im A1-Stil. |
| [getR1C1Formula()](#getR1C1Formula--) | Liest oder setzt die Formel im R1C1-Stil. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Liest oder setzt die Formel im R1C1-Stil. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Liest das Arbeitsblatt. |
| [isHidden()](#isHidden--) | Bestimmt, ob die Zelle ausgeblendet ist. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Liest oder setzt das benutzerdefinierte Anzeigeformat für Zahlen und Datumsangaben. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Liest oder setzt das benutzerdefinierte Anzeigeformat für Zahlen und Datumsangaben. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Liest oder setzt das integrierte Anzeigeformat für Zahlen und Datumsangaben. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Liest oder setzt das integrierte Anzeigeformat für Zahlen und Datumsangaben. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Wenn die Zelle eine Formel enthält, wird der Wert anhand dieser Formel aktualisiert. |
### getRow() {#getRow--}
```
public final int getRow()
```

Gibt den Index der Zeile des Arbeitsblatts zurück, in der sich die Zelle befindet. Nur lesend int.

**Rückgabe:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Gibt den Index der Spalte des Arbeitsblatts zurück, in der sich die Zelle befindet. Nur lesend int.

**Rückgabe:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```

Liest oder setzt den Wert einer Zelle. Lese/Schreib  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Rückgabe:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Liest oder setzt den Wert einer Zelle. Lese/Schreib  Object .

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
public final String getFormula()
```

Liest oder setzt die Formel im A1-Stil.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Rückgabe:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Liest oder setzt die Formel im A1-Stil.

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
public final String getR1C1Formula()
```

Liest oder setzt die Formel im R1C1-Stil.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Rückgabe:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

Liest oder setzt die Formel im R1C1-Stil.

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
public final IChartDataWorksheet getChartDataWorksheet()
```

Liest das Arbeitsblatt. Nur lesend [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Rückgabe:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Bestimmt, ob die Zelle ausgeblendet ist. Nur lesend boolean.

**Rückgabe:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

Liest oder setzt das benutzerdefinierte Anzeigeformat für Zahlen und Datumsangaben. Wenn der Wert leer ist, wird der PresetNumberFormat-Wert verwendet. Lese/Schreib String.

**Rückgabe:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

Liest oder setzt das benutzerdefinierte Anzeigeformat für Zahlen und Datumsangaben. Wenn der Wert leer ist, wird der PresetNumberFormat-Wert verwendet. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

Liest oder setzt das integrierte Anzeigeformat für Zahlen und Datumsangaben. Der voreingestellte Wert muss in [0..22] oder [37..49] liegen. Lese/Schreib byte.

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

**Rückgabe:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

Liest oder setzt das integrierte Anzeigeformat für Zahlen und Datumsangaben. Der voreingestellte Wert muss in [0..22] oder [37..49] liegen. Lese/Schreib byte.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

Wenn die Zelle eine Formel enthält, wird der Wert anhand dieser Formel aktualisiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| updateValues | boolean | Wenn false, wird keine tatsächliche Berechnung durchgeführt. Verwenden Sie true, um mögliche Ausnahmen zu prüfen. |