---
title: ChartDataCell
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: चार्ट डेटा के लिए सेल का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/chartdatacell/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IChartDataCell](../../com.aspose.slides/ichartdatacell)  
```
public class ChartDataCell implements IChartDataCell
```

चार्ट डेटा के लिए सेल का प्रतिनिधित्व करता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getRow()](#getRow--) | सेल जिस कार्यपत्र में स्थित है, उसकी पंक्ति का सूचकांक लौटाता है। |
| [getColumn()](#getColumn--) | सेल जिस कार्यपत्र में स्थित है, उसके कॉलम का सूचकांक लौटाता है। |
| [getValue()](#getValue--) | सेल के मान को प्राप्त या निर्धारित करता है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | सेल के मान को प्राप्त या निर्धारित करता है। |
| [getFormula()](#getFormula--) | A1-शैली में सूत्र को प्राप्त या निर्धारित करता है। |
| [setFormula(String value)](#setFormula-java.lang.String-) | A1-शैली में सूत्र को प्राप्त या निर्धारित करता है। |
| [getR1C1Formula()](#getR1C1Formula--) | R1C1-शैली में सूत्र को प्राप्त या निर्धारित करता है। |
| [setR1C1Formula(String value)](#setR1C1Formula-java.lang.String-) | R1C1-शैली में सूत्र को प्राप्त या निर्धारित करता है। |
| [getChartDataWorksheet()](#getChartDataWorksheet--) | कार्यपत्र को प्राप्त करता है। |
| [isHidden()](#isHidden--) | निर्धारित करता है कि सेल छिपा है या नहीं। |
| [getCustomNumberFormat()](#getCustomNumberFormat--) | संख्याओं और तिथियों के लिए कस्टम डिस्प्ले फॉर्मेट को प्राप्त या निर्धारित करता है। |
| [setCustomNumberFormat(String value)](#setCustomNumberFormat-java.lang.String-) | संख्याओं और तिथियों के लिए कस्टम डिस्प्ले फॉर्मेट को प्राप्त या निर्धारित करता है। |
| [getPresetNumberFormat()](#getPresetNumberFormat--) | संख्याओं और तिथियों के लिए अंतर्निहित डिस्प्ले फॉर्मेट को प्राप्त या निर्धारित करता है। |
| [setPresetNumberFormat(byte value)](#setPresetNumberFormat-byte-) | संख्याओं और तिथियों के लिए अंतर्निहित डिस्प्ले फॉर्मेट को प्राप्त या निर्धारित करता है। |
| [calculate(boolean updateValues)](#calculate-boolean-) | यदि सेल में सूत्र है, तो मान उस सूत्र के आधार पर अपडेट किया जाएगा। |

### getRow() {#getRow--}
```
public final int getRow()
```

सेल जिस कार्यपत्र में स्थित है, उसकी पंक्ति का सूचकांक लौटाता है। केवल-पठनीय int.

**रिटर्न:**  
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

सेल जिस कार्यपत्र में स्थित है, उसके कॉलम का सूचकांक लौटाता है। केवल-पठनीय int.

**रिटर्न:**  
int

### getValue() {#getValue--}
```
public final Object getValue()
```

सेल के मान को प्राप्त या निर्धारित करता है। पढ़ने/लिखने योग्य Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**रिटर्न:**  
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

सेल के मान को प्राप्त या निर्धारित करता है। पढ़ने/लिखने योग्य Object.

--------------------

> ```
> workbook.getCell(0, "F2").setValue(-2.5f);
>  workbook.getCell(0, "G3").setValue(6.3f);
> ```


**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

A1-शैली में सूत्र को प्राप्त या निर्धारित करता है.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**रिटर्न:**  
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

A1-शैली में सूत्र को प्राप्त या निर्धारित करता है.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "B2");
>  cell.setFormula("1 + SUM(F2:H5)");
> ```


**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getR1C1Formula() {#getR1C1Formula--}
```
public final String getR1C1Formula()
```

R1C1-शैली में सूत्र को प्राप्त या निर्धारित करता है.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**रिटर्न:**  
java.lang.String

### setR1C1Formula(String value) {#setR1C1Formula-java.lang.String-}
```
public final void setR1C1Formula(String value)
```

R1C1-शैली में सूत्र को प्राप्त या निर्धारित करता है.

--------------------

> ```
> IChartDataCell cell = workbook.getCell(0, "C2");
>  cell.setR1C1Formula("MAX(R2C6:R5C8) / 3");
> ```


**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getChartDataWorksheet() {#getChartDataWorksheet--}
```
public final IChartDataWorksheet getChartDataWorksheet()
```

कार्यपत्र को प्राप्त करता है। केवल-पठनीय [IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet).

**रिटर्न:**  
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet)

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

निर्धारित करता है कि सेल छिपा है या नहीं। केवल-पठनीय boolean.

**रिटर्न:**  
boolean

### getCustomNumberFormat() {#getCustomNumberFormat--}
```
public final String getCustomNumberFormat()
```

संख्याओं और तिथियों के लिए कस्टम डिस्प्ले फॉर्मेट को प्राप्त या निर्धारित करता है। यदि मान खाली है तो PresetNumberFormat मान उपयोग होगा। पढ़ने/लिखने योग्य String.

**रिटर्न:**  
java.lang.String

### setCustomNumberFormat(String value) {#setCustomNumberFormat-java.lang.String-}
```
public final void setCustomNumberFormat(String value)
```

संख्याओं और तिथियों के लिए कस्टम डिस्प्ले फॉर्मेट को प्राप्त या निर्धारित करता है। यदि मान खाली है तो PresetNumberFormat मान उपयोग होगा। पढ़ने/लिखने योग्य String.

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresetNumberFormat() {#getPresetNumberFormat--}
```
public final byte getPresetNumberFormat()
```

संख्याओं और तिथियों के लिए अंतर्निहित डिस्प्ले फॉर्मेट को प्राप्त या निर्धारित करता है। Preset संख्या को [0..22] या [37..49] में होना चाहिए। पढ़ने/लिखने योग्य byte.

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

**रिटर्न:**  
byte

### setPresetNumberFormat(byte value) {#setPresetNumberFormat-byte-}
```
public final void setPresetNumberFormat(byte value)
```

संख्याओं और तिथियों के लिए अंतर्निहित डिस्प्ले फॉर्मेट को प्राप्त या निर्धारित करता है। Preset संख्या को [0..22] या [37..49] में होना चाहिए। पढ़ने/लिखने योग्य byte.

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

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | byte |  |

### calculate(boolean updateValues) {#calculate-boolean-}
```
public final void calculate(boolean updateValues)
```

यदि सेल में सूत्र है, तो मान उस सूत्र के आधार पर अपडेट किया जाएगा।

**परामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| updateValues | boolean | यदि false है, तो कोई वास्तविक गणना नहीं की जाएगी। संभावित अपवाद जांच के लिए true का उपयोग करें। |