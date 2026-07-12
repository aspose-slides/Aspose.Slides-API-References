---
title: ChartDataCell
second_title: Aspose.Slides for Android の Java API リファレンス
description: チャート データのセルを表します。
type: docs
url: /ja/com.aspose.slides/chartdatacell/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

チャート データのセルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRow()](#getRow--) | セルが配置されているワークシートの行インデックスを返します。 |
| [getColumn()](#getColumn--) | セルが配置されているワークシートの列インデックスを返します。 |
| [getValue()](#getValue--) | セルの値を取得または設定します。 |
| [setValue(Object value)](#setValue-java.lang.Object-) | セルの値を取得または設定します。 |
| [getFormula()](#getFormula--) | A1 形式の数式を取得または設定します。 |
| [setFormula(String value)](#setFormula-java.lang.String-) | A1 形式の数式を取得または設定します。 |
| [getR1C1Formula()](#getR1C1Formula--) | R1C1 形式の数式を取得または設定します。 |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | R1C1 形式の数式を取得または設定します。 |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | ワークシートを取得します。 |
| [isHidden()](#isHidden--) | セルが非表示かどうかを判定します。 |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | 数値と日付のカスタム表示形式を取得または設定します。 |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | 数値と日付のカスタム表示形式を取得または設定します。 |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | 数値と日付の組み込み表示形式を取得または設定します。 |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | 数値と日付の組み込み表示形式を取得または設定します。 |
| [calculate(boolean updateValues)](#calculate-boolean-) | セルに数式が含まれている場合、値はその数式に基づいて更新されます。 |

### getRow() {#getRow--}
```
public final int getRow()
```


セルが配置されているワークシートの行インデックスを返します。読み取り専用 int.

**戻り値:**
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```


セルが配置されているワークシートの列インデックスを返します。読み取り専用 int.

**戻り値:**
int

### getValue() {#getValue--}
```
public final Object getValue()
```


セルの値を取得または設定します。読み取り/書き込み Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**戻り値:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


セルの値を取得または設定します。読み取り/書き込み Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


A1 形式の数式を取得または設定します。

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**戻り値:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


A1 形式の数式を取得または設定します。

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```


R1C1 形式の数式を取得または設定します。

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**戻り値:**
java.lang.String

### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```


R1C1 形式の数式を取得または設定します。

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```


ワークシートを取得します。読み取り専用 [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)。

**戻り値:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


セルが非表示かどうかを判定します。読み取り専用 boolean。

**戻り値:**
boolean

### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```


数値と日付のカスタム表示形式を取得または設定します。値が空の場合は PresetNumberFormat の値が使用されます。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```


数値と日付のカスタム表示形式を取得または設定します。値が空の場合は PresetNumberFormat の値が使用されます。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```


数値と日付の組み込み表示形式を取得または設定します。プリセット番号は [0..22] または [37..49] の範囲でなければなりません。読み取り/書き込み byte。

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

**戻り値:**
byte

### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```


数値と日付の組み込み表示形式を取得または設定します。プリセット番号は [0..22] または [37..49] の範囲でなければなりません。読み取り/書き込み byte。

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

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```


セルに数式が含まれている場合、値はその数式に基づいて更新されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| updateValues | boolean | false の場合、実際の計算は行われません。true を使用すると、例外が発生する可能性のチェックが行えます。 |