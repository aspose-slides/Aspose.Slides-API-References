---
title: ChartDataCell
second_title: Aspose.Slides dla Androida - odniesienie do API Java
description: Reprezentuje komórkę danych wykresu.
type: docs
url: /pl/com.aspose.slides/chartdatacell/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

Reprezentuje komórkę danych wykresu.
## Metody

| Method | Description |
| --- | --- |
| [getRow()](#getRow--) | Zwraca indeks wiersza arkusza, w którym znajduje się komórka. |
| [getColumn()](#getColumn--) | Zwraca indeks kolumny arkusza, w której znajduje się komórka. |
| [getValue()](#getValue--) | Pobiera lub ustawia wartość komórki. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Pobiera lub ustawia wartość komórki. |
| [getFormula()](#getFormula--) | Pobiera lub ustawia formułę w stylu A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Pobiera lub ustawia formułę w stylu A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Pobiera lub ustawia formułę w stylu R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Pobiera lub ustawia formułę w stylu R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Pobiera arkusz. |
| [isHidden()](#isHidden--) | Określa, czy komórka jest ukryta. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Pobiera lub ustawia niestandardowy format wyświetlania liczb i dat. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Pobiera lub ustawia niestandardowy format wyświetlania liczb i dat. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Pobiera lub ustawia wbudowany format wyświetlania liczb i dat. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Pobiera lub ustawia wbudowany format wyświetlania liczb i dat. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Jeśli komórka zawiera formułę, wartość zostanie zaktualizowana na podstawie tej formuły. |
### getRow() {#getRow--}
```
public final int getRow()
```

Zwraca indeks wiersza arkusza, w którym znajduje się komórka. Read-only int.

**Zwraca:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Zwraca indeks kolumny arkusza, w której znajduje się komórka. Read-only int.

**Zwraca:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```

Pobiera lub ustawia wartość komórki. Read/write  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Zwraca:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Pobiera lub ustawia wartość komórki. Read/write  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public final String getFormula()
```

Pobiera lub ustawia formułę w stylu A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Zwraca:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Pobiera lub ustawia formułę w stylu A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

Pobiera lub ustawia formułę w stylu R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Zwraca:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

Pobiera lub ustawia formułę w stylu R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

Pobiera arkusz. Read-only [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Zwraca:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Określa, czy komórka jest ukryta. Read-only boolean.

**Zwraca:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

Pobiera lub ustawia niestandardowy format wyświetlania liczb i dat. If value is empty will be used PresetNumberFormat value. Read/write String.

**Zwraca:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

Pobiera lub ustawia niestandardowy format wyświetlania liczb i dat. If value is empty will be used PresetNumberFormat value. Read/write String.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

Pobiera lub ustawia wbudowany format wyświetlania liczb i dat. Preset number must be in [0..22] or [37..49]. Read/write byte.

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

**Zwraca:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

Pobiera lub ustawia wbudowany format wyświetlania liczb i dat. Preset number must be in [0..22] or [37..49]. Read/write byte.

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

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

Jeśli komórka zawiera formułę, wartość zostanie zaktualizowana na podstawie tej formuły.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| updateValues | boolean | Jeśli false, nie zostanie wykonane żadne rzeczywiste obliczenie. Użyj true, aby sprawdzić możliwe wyjątki. |