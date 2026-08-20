---
title: IAxis
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: ห่อหุ้มอ็อบเจ็กต์ที่เป็นตัวแทนของแกนของแผนภูมิ
type: docs
url: /th/com.aspose.slides/iaxis/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

บรรจุอ็อบเจ็กต์ที่แทนแกนของแผนภูมิ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | ระบุว่ามีการข้ามแกนค่ากับแกนประเภทระหว่างหมวดหมู่หรือไม่. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | ระบุว่ามีการข้ามแกนค่ากับแกนประเภทระหว่างหมวดหมู่หรือไม่. |
| [getCrossAt()](#getCrossAt--) | ระบุจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. |
| [setCrossAt(float value)](#setCrossAt-float-) | ระบุจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. |
| [getDisplayUnit()](#getDisplayUnit--) | ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. |
| [getActualMaxValue()](#getActualMaxValue--) | ระบุค่ามากสุดจริงบนแกน. |
| [getActualMinValue()](#getActualMinValue--) | ระบุค่าต่ำสุดจริงบนแกน. |
| [getActualMajorUnit()](#getActualMajorUnit--) | ระบุหน่วยหลักจริงของแกน. |
| [getActualMinorUnit()](#getActualMinorUnit--) | ระบุหน่วยย่อยจริงของแกน. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | ระบุสเกลหน่วยหลักจริงของแกน. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | ระบุสเกลหน่วยย่อยจริงของแกน. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | ระบุว่าค่าสูงสุดถูกกำหนดอัตโนมัติหรือไม่. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | ระบุว่าค่าสูงสุดถูกกำหนดอัตโนมัติหรือไม่. |
| [getMaxValue()](#getMaxValue--) | ระบุค่ามากสุดบนแกนค่า. |
| [setMaxValue(double value)](#setMaxValue-double-) | ระบุค่ามากสุดบนแกนค่า. |
| [getMinorUnit()](#getMinorUnit--) | ระบุหน่วยย่อยสำหรับแกนวันที่หรือค่า. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | ระบุหน่วยย่อยสำหรับแกนวันที่หรือค่า. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | ระบุว่าหน่วยย่อยของแกนถูกกำหนดอัตโนมัติหรือไม่. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | ระบุว่าหน่วยย่อยของแกนถูกกำหนดอัตโนมัติหรือไม่. |
| [getMajorUnit()](#getMajorUnit--) | ระบุหน่วยหลักสำหรับแกนวันที่หรือค่า. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | ระบุหน่วยหลักสำหรับแกนวันที่หรือค่า. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | ระบุว่าหน่วยหลักของแกนถูกกำหนดอัตโนมัติหรือไม่. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | ระบุว่าหน่วยหลักของแกนถูกกำหนดอัตโนมัติหรือไม่. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | ระบุว่าค่าต่ำสุดถูกกำหนดอัตโนมัติหรือไม่. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | ระบุว่าค่าต่ำสุดถูกกำหนดอัตโนมัติหรือไม่. |
| [getMinValue()](#getMinValue--) | ระบุค่าต่ำสุดบนแกนค่า. |
| [setMinValue(double value)](#setMinValue-double-) | ระบุค่าต่ำสุดบนแกนค่า. |
| [isLogarithmic()](#isLogarithmic--) | ระบุว่าชนิดสเกลของแกนค่าคือโลการิทึมหรือไม่. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | ระบุว่าชนิดสเกลของแกนค่าคือโลการิทึมหรือไม่. |
| [getLogBase()](#getLogBase--) | ระบุฐานของโลการิทึม. |
| [setLogBase(double value)](#setLogBase-double-) | ระบุฐานของโลการิทึม. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | ระบุว่า MS PowerPoint วาดจุดข้อมูลจากหลังไปหน้า. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | ระบุว่า MS PowerPoint วาดจุดข้อมูลจากหลังไปหน้า. |
| [isVisible()](#isVisible--) | ระบุว่าแกนเป็นที่มองเห็นหรือไม่. |
| [setVisible(boolean value)](#setVisible-boolean-) | ระบุว่าแกนเป็นที่มองเห็นหรือไม่. |
| [getMajorTickMark()](#getMajorTickMark--) | ระบุชนิดของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | ระบุชนิดของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ. |
| [getMinorTickMark()](#getMinorTickMark--) | ระบุชนิดของเครื่องหมายติ๊กย่อยสำหรับแกนที่ระบุ. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | ระบุชนิดของเครื่องหมายติ๊กย่อยสำหรับแกนที่ระบุ. |
| [getTickLabelPosition()](#getTickLabelPosition--) | ระบุตำแหน่งของป้ายกำกับติ๊กบนแกนที่ระบุ. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | ระบุตำแหน่งของป้ายกำกับติ๊กบนแกนที่ระบุ. |
| [getMajorUnitScale()](#getMajorUnitScale--) | ระบุสเกลหน่วยหลักสำหรับแกนวันที่. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | ระบุสเกลหน่วยหลักสำหรับแกนวันที่. |
| [getMinorUnitScale()](#getMinorUnitScale--) | ระบุสเกลหน่วยหลักสำหรับแกนวันที่. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | ระบุสเกลหน่วยหลักสำหรับแกนวันที่. |
| [getBaseUnitScale()](#getBaseUnitScale--) | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | ระบุรูปแบบของเส้นกริดย่อยบนแกนแผนภูมิ. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | ระบุรูปแบบของเส้นกริดหลักบนแกนแผนภูมิ. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | ระบุว่ามีการแสดงเส้นกริดย่อยหรือไม่. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | ระบุว่ามีการแสดงเส้นกริดหลักหรือไม่. |
| [getFormat()](#getFormat--) | ระบุรูปแบบของแกน. |
| [getTitle()](#getTitle--) | รับชื่อของแกน. |
| [getCrossType()](#getCrossType--) | ระบุ CrossType บนแกนที่ระบุที่แกนอื่นข้าม. |
| [setCrossType(int value)](#setCrossType-int-) | ระบุ CrossType บนแกนที่ระบุที่แกนอื่นข้าม. |
| [getPosition()](#getPosition--) | ระบุตำแหน่งของแกน. |
| [setPosition(int value)](#setPosition-int-) | ระบุตำแหน่งของแกน. |
| [hasTitle()](#hasTitle--) | ตรวจสอบว่าแกนมีชื่อที่มองเห็นได้หรือไม่. |
| [setTitle(boolean value)](#setTitle-boolean-) | ตรวจสอบว่าแกนมีชื่อที่มองเห็นได้หรือไม่. |
| [getNumberFormat()](#getNumberFormat--) | ระบุสตริงรูปแบบสำหรับป้ายแกน. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | ระบุสตริงรูปแบบสำหรับป้ายแกน. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | ระบุว่ารูปแบบเชื่อมกับข้อมูลต้นทางหรือไม่. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | ระบุว่ารูปแบบเชื่อมกับข้อมูลต้นทางหรือไม่. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | ระบุมุมการหมุนของป้ายติ๊ก อ่าน/เขียน float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | ระบุมุมการหมุนของป้ายติ๊ก อ่าน/เขียน float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | ระบุจำนวนป้ายติ๊กที่ข้ามระหว่างป้ายที่วาด. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | ระบุจำนวนป้ายติ๊กที่ข้ามระหว่างป้ายที่วาด. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | ระบุค่าการเว้นระยะห่างของป้ายติ๊กอัตโนมัติ. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | ระบุค่าการเว้นระยะห่างของป้ายติ๊กอัตโนมัติ. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | ระบุจำนวนเครื่องหมายติ๊กที่ข้ามก่อนที่จะวาดเครื่องหมายถัดไป. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | ระบุจำนวนเครื่องหมายติ๊กที่ข้ามก่อนที่จะวาดเครื่องหมายถัดไป. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | ระบุค่าการเว้นระยะห่างของเครื่องหมายติ๊กอัตโนมัติ. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | ระบุค่าการเว้นระยะห่างของเครื่องหมายติ๊กอัตโนมัติ. |
| [getLabelOffset()](#getLabelOffset--) | ระบุระยะห่างของป้ายจากแกน. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | ระบุระยะห่างของป้ายจากแกน. |
| [getCategoryAxisType()](#getCategoryAxisType--) | ระบุชนิดของแกนประเภท. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | ระบุชนิดของแกนประเภท. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดอัตโนมัติตามข้อมูลแกน. |
| [getAggregationType()](#getAggregationType--) | ระบุชนิดการรวมของแกนประเภท (การจัดกลุ่ม). |
| [setAggregationType(int value)](#setAggregationType-int-) | ระบุชนิดการรวมของแกนประเภท (การจัดกลุ่ม). |
| [getBinWidth()](#getBinWidth--) | ระบุความกว้างของบินเมื่อค่า AggregationType ตั้งเป็น AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | ระบุความกว้างของบินเมื่อค่า AggregationType ตั้งเป็น AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | ระบุจำนวนบินเมื่อค่า AggregationType ตั้งเป็น AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | ระบุจำนวนบินเมื่อค่า AggregationType ตั้งเป็น AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | ระบุว่ามีการใช้บิน overflow หรือไม่. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | ระบุว่ามีการใช้บิน overflow หรือไม่. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | ระบุค่าบิน overflow อัตโนมัติ. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | ระบุค่าบิน overflow อัตโนมัติ. |
| [getOverflowBin()](#getOverflowBin--) | ระบุค่าบิน overflow ที่กำหนดเอง. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | ระบุค่าบิน overflow ที่กำหนดเอง. |
| [isUnderflowBin()](#isUnderflowBin--) | ระบุว่ามีการใช้บิน underflow หรือไม่. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | ระบุว่ามีการใช้บิน underflow หรือไม่. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | ระบุค่าบิน underflow อัตโนมัติ. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | ระบุค่าบิน underflow อัตโนมัติ. |
| [getUnderflowBin()](#getUnderflowBin--) | ระบุค่าบิน underflow ที่กำหนดเอง. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | ระบุค่าบิน underflow ที่กำหนดเอง. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

ระบุว่ามีการข้ามแกนค่ากับแกนประเภทระหว่างหมวดหมู่หรือไม่. คุณสมบัตินี้ใช้กับแกนประเภทเท่านั้นและไม่ใช้กับแผนภูมิ 3-D. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

ระบุว่ามีการข้ามแกนค่ากับแกนประเภทระหว่างหมวดหมู่หรือไม่. คุณสมบัตินี้ใช้กับแกนประเภทเท่านั้นและไม่ใช้กับแผนภูมิ 3-D. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

ระบุจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. อ่าน/เขียน float.

**ผลลัพธ์:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

ระบุจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. อ่าน/เขียน [DisplayUnitType](../../com.aspose.slides/displayunittype).

**ผลลัพธ์:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. อ่าน/เขียน [DisplayUnitType](../../com.aspose.slides/displayunittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

ระบุค่ามากสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**ผลลัพธ์:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

ระบุค่าต่ำสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**ผลลัพธ์:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

ระบุหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**ผลลัพธ์:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

ระบุหน่วยย่อยจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**ผลลัพธ์:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

ระบุสเกลหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**ผลลัพธ์:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

ระบุสเกลหน่วยย่อยจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**ผลลัพธ์:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

ระบุว่าค่าสูงสุดถูกกำหนดอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

ระบุว่าค่าสูงสุดถูกกำหนดอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

ระบุค่ามากสุดบนแกนค่า. อ่าน/เขียน double.

**ผลลัพธ์:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

ระบุค่ามากสุดบนแกนค่า. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

ระบุหน่วยย่อยสำหรับแกนวันที่หรือค่า. อ่าน/เขียน double.

**ผลลัพธ์:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

ระบุหน่วยย่อยสำหรับแกนวันที่หรือค่า. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

ระบุว่าหน่วยย่อยของแกนถูกกำหนดอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

ระบุว่าหน่วยย่อยของแกนถูกกำหนดอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

ระบุหน่วยหลักสำหรับแกนวันที่หรือค่า. อ่าน/เขียน double.

**ผลลัพธ์:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

ระบุหน่วยหลักสำหรับแกนวันที่หรือค่า. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

ระบุว่าหน่วยหลักของแกนถูกกำหนดอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

ระบุว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

ระบุว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

ระบุว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

แสดงค่าต่ำสุดบนแกนค่า อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

แสดงค่าต่ำสุดบนแกนค่า อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

แสดงว่าประเภทสเกลของแกนค่าคือโลการิทึมหรือไม่ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

แสดงว่าประเภทสเกลของแกนค่าคือโลการิทึมหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

แสดงฐานของระบบล็อการิทึม ค่าเริ่มต้นคือ 10 อ่าน/เขียน double.

**ผลลัพธ์:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

แสดงฐานของระบบล็อการิทึม ค่าเริ่มต้นคือ 10 อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

แสดงว่า MS PowerPoint วาดจุดข้อมูลจากท้ายไปหัวหรือไม่ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

แสดงว่า MS PowerPoint วาดจุดข้อมูลจากท้ายไปหัวหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

แสดงว่าแกนมองเห็นได้หรือไม่ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

แสดงว่าแกนมองเห็นได้หรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

แสดงประเภทของเครื่องหมายหลักสำหรับแกนที่ระบุ อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**ผลลัพธ์:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract int getMajorTickMark()
```

แสดงประเภทของเครื่องหมายหลักสำหรับแกนที่ระบุ อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

แสดงประเภทของเครื่องหมายย่อยสำหรับแกนที่ระบุ อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**ผลลัพธ์:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

แสดงประเภทของเครื่องหมายย่อยสำหรับแกนที่ระบุ อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ อ่าน/เขียน [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**ผลลัพธ์:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ อ่าน/เขียน [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

แสดงสเกลหน่วยหลักสำหรับแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**ผลลัพธ์:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

แสดงสเกลหน่วยหลักสำหรับแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

แสดงสเกลหน่วยรองสำหรับแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**ผลลัพธ์:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

แสดงสเกลหน่วยรองสำหรับแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**ผลลัพธ์:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

แสดงรูปแบบเส้นกริดย่อยบนแกนแผนภูมิ อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**ผลลัพธ์:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

แสดงรูปแบบเส้นกริดหลักบนแกนแผนภูมิ อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**ผลลัพธ์:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

แสดงว่าเส้นกริดย่อยแสดงหรือไม่ อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

แสดงว่าเส้นกริดหลักแสดงหรือไม่ อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

แสดงรูปแบบของแกน อ่านอย่างเดียว [IAxisFormat](../../com.aspose.slides/iaxisformat).

**ผลลัพธ์:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

รับหัวข้อของแกน อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle).

**ผลลัพธ์:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

แสดง CrossType บนแกนที่ระบุที่แกนอื่นตัดกัน อ่าน/เขียน [CrossesType](../../com.aspose.slides/crossestype).

**ผลลัพธ์:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

แสดง CrossType บนแกนที่ระบุที่แกนอื่นตัดกัน อ่าน/เขียน [CrossesType](../../com.aspose.slides/crossestype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

แสดงตำแหน่งของแกน อ่าน/เขียน [AxisPositionType](../../com.aspose.slides/axispositiontype).

**ผลลัพธ์:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

แสดงตำแหน่งของแกน อ่าน/เขียน [AxisPositionType](../../com.aspose.slides/axispositiontype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

กำหนดว่าแกนมีหัวข้อที่มองเห็นได้หรือไม่ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

กำหนดว่าแกนมีหัวข้อที่มองเห็นได้หรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

แสดงสตริงรูปแบบสำหรับป้ายแกน อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

แสดงสตริงรูปแบบสำหรับป้ายแกน อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

ระบุว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

ระบุว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

แสดงมุมการหมุนของป้ายกำกับเครื่องหมาย อ่าน/เขียน float.

**ผลลัพธ์:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

แสดงมุมการหมุนของป้ายกำกับเครื่องหมาย อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

ระบุจำนวนป้ายกำกับเครื่องหมายที่จะข้ามระหว่างป้ายที่วาด อ่าน/เขียน long.

**ผลลัพธ์:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

ระบุจำนวนป้ายกำกับเครื่องหมายที่จะข้ามระหว่างป้ายที่วาด อ่าน/เขียน long.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

ระบุค่าการเว้นระยะป้ายกำกับเครื่องหมายอัตโนมัติ หาก false: ใช้คุณสมบัติ TickLabelSpacing อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

ระบุค่าการเว้นระยะป้ายกำกับเครื่องหมายอัตโนมัติ หาก false: ใช้คุณสมบัติ TickLabelSpacing อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

ระบุจำนวนเครื่องหมายที่จะข้ามก่อนที่เครื่องหมายถัดไปจะถูกวาด ใช้กับแกนประเภทหรือซีรีส์ อ่าน/เขียน int.

**ผลลัพธ์:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

ระบุจำนวนเครื่องหมายที่จะข้ามก่อนที่เครื่องหมายถัดไปจะถูกวาด ใช้กับแกนประเภทหรือซีรีส์ อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

ระบุค่าการเว้นระยะเครื่องหมายอัตโนมัติ หาก false: ใช้คุณสมบัติ TickMarksSpacing อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

ระบุค่าการเว้นระยะเครื่องหมายอัตโนมัติ หาก false: ใช้คุณสมบัติ TickMarksSpacing อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

ระยะห่างของป้ายจากแกน ใช้กับแกนประเภทหรือวันที่ ค่า ต้องอยู่ระหว่าง 0% ถึง 1000% อ่าน/เขียน int.

**ผลลัพธ์:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

ระยะห่างของป้ายจากแกน ใช้กับแกนประเภทหรือวันที่ ค่า ต้องอยู่ระหว่าง 0% ถึง 1000% อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

ระบุประเภทของแกนประเภท อ่าน/เขียน [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**ผลลัพธ์:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

ระบุประเภทของแกนประเภท อ่าน/เขียน [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดโดยอัตโนมัติตามข้อมูลแกน.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

แสดงประเภทการรวมของแกนประเภท (การจัดกลุ่ม) ใช้กับประเภทเท่านั้น ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**ผลลัพธ์:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

แสดงประเภทการรวมของแกนประเภท (การจัดกลุ่ม) ใช้กับประเภทเท่านั้น ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

ระบุความกว้างของ bin เมื่อค่า property AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth ใช้กับแกนประเภทและใช้ร่วมกับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น

**คืนค่า:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

ระบุความกว้างของ bin เมื่อค่า property AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth ใช้กับแกนประเภทและใช้ร่วมกับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

ระบุจำนวนของ bin เมื่อค่า property AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins ใช้กับแกนประเภทและใช้ร่วมกับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น

**คืนค่า:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

ระบุจำนวนของ bin เมื่อค่า property AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins ใช้กับแกนประเภทและใช้ร่วมกับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

ระบุว่ามีการใช้ overflow bin หรือไม่ ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าของ overflow bin

**คืนค่า:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

ระบุว่ามีการใช้ overflow bin หรือไม่ ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าของ overflow bin

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

ระบุค่าของ automatic overflow bin หากเป็น false ให้ใช้ property OverflowBin

**คืนค่า:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

ระบุค่าของ automatic overflow bin หากเป็น false ให้ใช้ property OverflowBin

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

ระบุค่าที่กำหนดสำหรับ overflow bin ใช้เมื่อ property IsAutomaticOverflowBin ถูกตั้งเป็น false และ property IsOverflowBin มีค่าเป็น true

**คืนค่า:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

ระบุค่าที่กำหนดสำหรับ overflow bin ใช้เมื่อ property IsAutomaticOverflowBin ถูกตั้งเป็น false และ property IsOverflowBin มีค่าเป็น true

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

ระบุว่ามีการใช้ underflow bin หรือไม่ ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าของ underflow bin

**คืนค่า:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

ระบุว่ามีการใช้ underflow bin หรือไม่ ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าของ underflow bin

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

ระบุค่าของ automatic underflow bin หากเป็น false ให้ใช้ property UnderflowBin

**คืนค่า:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

ระบุค่าของ automatic underflow bin หากเป็น false ให้ใช้ property UnderflowBin

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

ระบุค่าที่กำหนดสำหรับ underflow bin ใช้เมื่อ property IsAutomaticUnderflowBin ถูกตั้งเป็น false และ property IsUnderflowBin มีค่าเป็น true

**คืนค่า:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

ระบุค่าที่กำหนดสำหรับ underflow bin ใช้เมื่อ property IsAutomaticUnderflowBin ถูกตั้งเป็น false และ property IsUnderflowBin มีค่าเป็น true

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |