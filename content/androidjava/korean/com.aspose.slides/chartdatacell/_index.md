---
title: ChartDataCell
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 차트 데이터용 셀을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/chartdatacell/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

차트 데이터용 셀을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getRow()](#getRow--) | 셀의 위치한 워크시트 행 인덱스를 반환합니다. |
| [getColumn()](#getColumn--) | 셀의 위치한 워크시트 열 인덱스를 반환합니다. |
| [getValue()](#getValue--) | 셀의 값을 가져오거나 설정합니다. |
| [setValue(Object value)](#setValue-java.lang.Object-) | 셀의 값을 가져오거나 설정합니다. |
| [getFormula()](#getFormula--) | A1 스타일의 수식을 가져오거나 설정합니다. |
| [setFormula(String value)](#setFormula-java.lang.String-) | A1 스타일의 수식을 가져오거나 설정합니다. |
| [getR1C1Formula()](#getR1C1Formula--) | R1C1 스타일의 수식을 가져오거나 설정합니다. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | R1C1 스타일의 수식을 가져오거나 설정합니다. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | 워크시트를 가져옵니다. |
| [isHidden()](#isHidden--) | 셀이 숨겨져 있는지 판단합니다. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | 숫자와 날짜의 사용자 지정 표시 형식을 가져오거나 설정합니다. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | 숫자와 날짜의 사용자 지정 표시 형식을 가져오거나 설정합니다. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | 숫자와 날짜의 내장 표시 형식을 가져오거나 설정합니다. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | 숫자와 날짜의 내장 표시 형식을 가져오거나 설정합니다. |
| [calculate(boolean updateValues)](#calculate-boolean-) | 셀에 수식이 포함된 경우, 해당 수식에 따라 값이 업데이트됩니다. |
### getRow() {#getRow--}
```
public final int getRow()
```


셀의 위치한 워크시트 행 인덱스를 반환합니다. 읽기 전용 int.

**반환값:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


셀의 위치한 워크시트 열 인덱스를 반환합니다. 읽기 전용 int.

**반환값:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


셀의 값을 가져오거나 설정합니다. 읽기/쓰기 Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**반환값:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


셀의 값을 가져오거나 설정합니다. 읽기/쓰기 Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public final String getFormula()
```


A1 스타일의 수식을 가져오거나 설정합니다.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**반환값:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


A1 스타일의 수식을 가져오거나 설정합니다.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```


R1C1 스타일의 수식을 가져오거나 설정합니다.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**반환값:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```


R1C1 스타일의 수식을 가져오거나 설정합니다.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```


워크시트를 가져옵니다. 읽기 전용 [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**반환값:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


셀이 숨겨져 있는지 판단합니다. 읽기 전용 boolean.

**반환값:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```


숫자와 날짜의 사용자 지정 표시 형식을 가져오거나 설정합니다. 값이 비어 있으면 PresetNumberFormat 값이 사용됩니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```


숫자와 날짜의 사용자 지정 표시 형식을 가져오거나 설정합니다. 값이 비어 있으면 PresetNumberFormat 값이 사용됩니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |
### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```


숫자와 날짜의 내장 표시 형식을 가져오거나 설정합니다. 사전 설정 번호는 [0..22] 또는 [37..49] 범위에 있어야 합니다. 읽기/쓰기 byte.

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

**반환값:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```


숫자와 날짜의 내장 표시 형식을 가져오거나 설정합니다. 사전 설정 번호는 [0..22] 또는 [37..49] 범위에 있어야 합니다. 읽기/쓰기 byte.

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

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | byte |  |
### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```


셀에 수식이 포함된 경우, 해당 수식에 따라 값이 업데이트됩니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| updateValues | boolean | false이면 실제 계산이 수행되지 않습니다. true를 사용하면 예외 발생 가능성을 확인할 수 있습니다. |