---
title: IChartDataCell
second_title: Aspose.Slides for Android via Java API Reference
description: A diagram adatcelláját képviseli.
type: docs
url: /hu/com.aspose.slides/ichartdatacell/
---```
public interface IChartDataCell
```

A diagram adatcelláját képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRow()](#getRow--) | Visszaadja annak a munkalapnak a sorindexét, amelyben a cella található. |
| [getColumn()](#getColumn--) | Visszaadja annak a munkalapnak az oszlopindexét, amelyben a cella található. |
| [getValue()](#getValue--) | Lekérdezi vagy beállítja a cella értékét. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Lekérdezi vagy beállítja a cella értékét. |
| [getFormula()](#getFormula--) | Lekérdezi vagy beállítja a képletet A1-stílusban. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Lekérdezi vagy beállítja a képletet A1-stílusban. |
| [getR1C1Formula()](#getR1C1Formula--) | Lekérdezi vagy beállítja a képletet R1C1-stílusban. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Lekérdezi vagy beállítja a képletet R1C1-stílusban. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Lekéri a munkalapot. |
| [isHidden()](#isHidden--) | Megállapítja, hogy a cella rejtett-e. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Lekérdezi vagy beállítja a számok és dátumok egyéni megjelenítési formátumát. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Lekérdezi vagy beállítja a számok és dátumok egyéni megjelenítési formátumát. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Lekérdezi vagy beállítja a számok és dátumok beépített megjelenítési formátumát. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Lekérdezi vagy beállítja a számok és dátumok beépített megjelenítési formátumát. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Ha a cella képletet tartalmaz, az érték a képlet alapján frissül. |
### getRow() {#getRow--}
```
public abstract int getRow()
```

Visszaadja annak a munkalapnak a sorindexét, amelyben a cella található. **Csak olvasható** int.

**Visszatér:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```

Visszaadja annak a munkalapnak az oszlopindexét, amelyben a cella található. **Csak olvasható** int.

**Visszatér:**
int
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Lekérdezi vagy beállítja a cella értékét. **Olvasás/írás** Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**Visszatér:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Lekérdezi vagy beállítja a cella értékét. **Olvasás/írás** Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Lekérdezi vagy beállítja a képletet A1-stílusban.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Visszatér:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Lekérdezi vagy beállítja a képletet A1-stílusban.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public abstract String getR1C1Formula()
```

Lekérdezi vagy beállítja a képletet R1C1-stílusban.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Visszatér:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public abstract void setR1C1Formula(String value)
```

Lekérdezi vagy beállítja a képletet R1C1-stílusban.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public abstract IChartDataWorksheet getChartDataWorksheet()
```

Lekéri a munkalapot. **Csak olvasható** [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Visszatér:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Megállapítja, hogy a cella rejtett-e. **Csak olvasható** boolean.

**Visszatér:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public abstract String getCustomNumberFormat()
```

Lekérdezi vagy beállítja a számok és dátumok egyéni megjelenítési formátumát. Ha az érték üres, a PresetNumberFormat érték lesz használva. **Olvasás/írás** String.

**Visszatér:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public abstract void setCustomNumberFormat(String value)
```

Lekérdezi vagy beállítja a számok és dátumok egyéni megjelenítési formátumát. Ha az érték üres, a PresetNumberFormat érték lesz használva. **Olvasás/írás** String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public abstract byte getPresetNumberFormat()
```

Lekérdezi vagy beállítja a számok és dátumok beépített megjelenítési formátumát. Az előre beállított számnak a [0..22] vagy [37..49] tartományban kell lennie. **Olvasás/írás** byte.

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

**Visszatér:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public abstract void setPresetNumberFormat(byte value)
```

Lekérdezi vagy beállítja a számok és dátumok beépített megjelenítési formátumát. Az előre beállított számnak a [0..22] vagy [37..49] tartományban kell lennie. **Olvasás/írás** byte.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public abstract void calculate(boolean updateValues)
```

Ha a cella képletet tartalmaz, az érték a képlet alapján frissül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| updateValues | boolean | Ha hamis, nincs tényleges kiszámítás. A true használata lehetővé teszi a lehetséges kivételek ellenőrzését. |