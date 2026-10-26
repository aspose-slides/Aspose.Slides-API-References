---
title: ChartDataCell
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет ячейку данных диаграммы.
type: docs
url: /ru/com.aspose.slides/chartdatacell/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)
```
public class ChartDataCell implements IChartDataCell
```

Представляет ячейку данных диаграммы.
## Методы

| Метод | Описание |
| --- | --- |
| [getRow()](#getRow--) | Возвращает индекс строки worksheet, в которой находится ячейка. |
| [getColumn()](#getColumn--) | Возвращает индекс столбца worksheet, в которой находится ячейка. |
| [getValue()](#getValue--) | Получает или задает значение ячейки. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Получает или задает значение ячейки. |
| [getFormula()](#getFormula--) | Получает или задает формулу в стиле A1. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Получает или задает формулу в стиле A1. |
| [getR1C1Formula()](#getR1C1Formula--) | Получает или задает формулу в стиле R1C1. |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | Получает или задает формулу в стиле R1C1. |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | Получает worksheet. |
| [isHidden()](#isHidden--) | Определяет, скрыта ли ячейка. |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | Получает или задает пользовательский формат отображения чисел и дат. |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | Получает или задает пользовательский формат отображения чисел и дат. |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | Получает или задает встроенный формат отображения чисел и дат. |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | Получает или задает встроенный формат отображения чисел и дат. |
| [calculate(boolean updateValues)](#calculate-boolean-) | Если ячейка содержит формулу, значение будет обновлено на основе этой формулы. |
### getRow() {#getRow--}
```
public final int getRow()
```


Возвращает индекс строки worksheet, в которой находится ячейка. **Только для чтения** int.

**Возвращаемое значение:**
int
### getColumn() {#getColumn--}
```
public final int getColumn()
```


Возвращает индекс столбца worksheet, в которой находится ячейка. **Только для чтения** int.

**Возвращаемое значение:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Получает или задает значение ячейки. **Чтение/запись**  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Возвращаемое значение:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Получает или задает значение ячейки. **Чтение/запись**  Object .

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Получает или задает формулу в стиле A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Возвращаемое значение:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Получает или задает формулу в стиле A1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```


Получает или задает формулу в стиле R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```

**Возвращаемое значение:**
java.lang.String
### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```


Получает или задает формулу в стиле R1C1.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```


Получает worksheet. **Только для чтения** [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**Возвращаемое значение:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


Определяет, скрыта ли ячейка. **Только для чтения** boolean.

**Возвращаемое значение:**
boolean
### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```


Получает или задает пользовательский формат отображения чисел и дат. Если значение пусто, будет использовано значение PresetNumberFormat. **Чтение/запись** String.

**Возвращаемое значение:**
java.lang.String
### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```


Получает или задает пользовательский формат отображения чисел и дат. Если значение пусто, будет использовано значение PresetNumberFormat. **Чтение/запись** String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```


Получает или задает встроенный формат отображения чисел и дат. Предустановленный номер должен быть в диапазоне [0..22] или [37..49]. **Чтение/запись** byte.

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

**Возвращаемое значение:**
byte
### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```


Получает или задает встроенный формат отображения чисел и дат. Предустановленный номер должен быть в диапазоне [0..22] или [37..49]. **Чтение/запись** byte.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```


Если ячейка содержит формулу, значение будет обновлено на основе этой формулы.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| updateValues | boolean | Если false, фактическое вычисление не будет выполнено. Используйте true для проверки возможных исключений. |