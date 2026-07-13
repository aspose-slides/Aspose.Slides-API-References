---
title: ChartDataCell
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en cell för diagramdata.
type: docs
url: /sv/com.aspose.slides/chartdatacell/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

Representerar en cell för diagramdata.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRow()](#getRow--) | Returnerar index för raden i kalkylbladet där cellen är placerad. |
| [getColumn()](#getColumn--) | Returnerar index för kolumnen i kalkylbladet där cellen är placerad. |
| [getValue()](#getValue--) | Hämtar eller anger värdet på en cell. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Hämtar eller anger värdet på en cell. |
| [getFormula()](#getFormula--) | Hämtar eller anger formeln i A1-stil. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Hämtar eller anger formeln i A1-stil. |
| [getR1C1Formula()](#getR1C1Formula--) | Hämtar eller anger formeln i R1C1-stil. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Hämtar eller anger formeln i R1C1-stil. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Hämtar kalkylbladet. |
| [isHidden()](#isHidden--) | Avgör om cellen är dold. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Hämtar eller anger det anpassade visningsformatet för tal och datum. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Hämtar eller anger det anpassade visningsformatet för tal och datum. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Hämtar eller anger det inbyggda visningsformatet för tal och datum. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Hämtar eller anger det inbyggda visningsformatet för tal och datum. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Om cellen innehåller en formel uppdateras värdet baserat på den formeln. |
### getRow() {#getRow--}
```
public final int getRow()
```

Returnerar index för raden i kalkylbladet där cellen är placerad. Skrivskyddad int.

**Returnerar:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```

Returnerar index för kolumnen i kalkylbladet där cellen är placerad. Skrivskyddad int.

**Returnerar:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```

Hämtar eller anger värdet på en cell. Läs/skriv  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Returnerar:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Hämtar eller anger värdet på en cell. Läs/skriv  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public final String getFormula()
```

Hämtar eller anger formeln i A1-stil.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Returnerar:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Hämtar eller anger formeln i A1-stil.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

Hämtar eller anger formeln i R1C1-stil.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Returnerar:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

Hämtar eller anger formeln i R1C1-stil.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

Hämtar kalkylbladet. Skrivskyddad [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Returnerar:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Avgör om cellen är dold. Skrivskyddad boolean.

**Returnerar:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

Hämtar eller anger det anpassade visningsformatet för tal och datum. Om värdet är tomt används PresetNumberFormat-värdet. Läs/skriv String.

**Returnerar:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

Hämtar eller anger det anpassade visningsformatet för tal och datum. Om värdet är tomt används PresetNumberFormat-värdet. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

Hämtar eller anger det inbyggda visningsformatet för tal och datum. Förinställt nummer måste ligga i [0..22] eller [37..49]. Läs/skriv byte.

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

**Returnerar:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

Hämtar eller anger det inbyggda visningsformatet för tal och datum. Förinställt nummer måste ligga i [0..22] eller [37..49]. Läs/skriv byte.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

Om cellen innehåller en formel uppdateras värdet baserat på den formeln.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| updateValues | boolean | Om false, utförs ingen faktisk beräkning. Använd true för att kontrollera möjliga undantag. |