---
title: Axis
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: บรรจุอ็อบเจ็กต์ที่เป็นตัวแทนของแกนของแผนภูมิ
type: docs
url: /th/com.aspose.slides/axis/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

บรรจุวัตถุที่เป็นตัวแทนของแกนของแผนภูมิ.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChart()](#getChart--) | ส่งคืนแผนภูมิแม่. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | ระบุว่าแกนค่าข้ามแกนประเภทระหว่างหมวดหมู่หรือไม่. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | ระบุว่าแกนค่าข้ามแกนประเภทระหว่างหมวดหมู่หรือไม่. |
| [getCategoryAxisType()](#getCategoryAxisType--) | ระบุประเภทของแกนหมวดหมู่. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | ระบุประเภทของแกนหมวดหมู่. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดโดยอัตโนมัติตามข้อมูลแกน. |
| [getCrossAt()](#getCrossAt--) | ระบุจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. |
| [setCrossAt(float value)](#setCrossAt-float-) | ระบุจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. |
| [getDisplayUnit()](#getDisplayUnit--) | ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. |
| [getActualMaxValue()](#getActualMaxValue--) | ระบุค่าสูงสุดจริงบนแกน. |
| [getActualMinValue()](#getActualMinValue--) | ระบุค่าต่ำสุดจริงบนแกน. |
| [getActualMajorUnit()](#getActualMajorUnit--) | ระบุหน่วยหลักจริงของแกน. |
| [getActualMinorUnit()](#getActualMinorUnit--) | ระบุหน่วยย่อยจริงของแกน. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | ระบุสเกลหน่วยหลักจริงของแกน. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | ระบุสเกลหน่วยย่อยจริงของแกน. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | ระบุว่าค่ามากสุดถูกกำหนดโดยอัตโนมัติหรือไม่. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | ระบุว่าค่ามากสุดถูกกำหนดโดยอัตโนมัติหรือไม่. |
| [getMaxValue()](#getMaxValue--) | ระบุค่าสูงสุดบนแกนค่า. |
| [setMaxValue(double value)](#setMaxValue-double-) | ระบุค่าสูงสุดบนแกนค่า. |
| [getMinorUnit()](#getMinorUnit--) | ระบุหน่วยย่อยสำหรับแกนวันที่หรือค่า. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | ระบุหน่วยย่อยสำหรับแกนวันที่หรือค่า. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | ระบุว่าหน่วยย่อยของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | ระบุว่าหน่วยย่อยของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. |
| [getMajorUnit()](#getMajorUnit--) | ระบุหน่วยหลักสำหรับแกนวันที่หรือค่า. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | ระบุหน่วยหลักสำหรับแกนวันที่หรือค่า. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | ระบุว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | ระบุว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | ระบุว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | ระบุว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่. |
| [getMinValue()](#getMinValue--) | ระบุค่าต่ำสุดบนแกนค่า. |
| [setMinValue(double value)](#setMinValue-double-) | ระบุค่าต่ำสุดบนแกนค่า. |
| [isLogarithmic()](#isLogarithmic--) | ระบุว่าแบบสเกลของแกนค่าคือแบบลอการิทึมหรือไม่. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | ระบุว่าแบบสเกลของแกนค่าคือแบบลอการิทึมหรือไม่. |
| [getLogBase()](#getLogBase--) | ระบุฐานของลอการิทึม. |
| [setLogBase(double value)](#setLogBase-double-) | ระบุฐานของลอการิทึม. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | ระบุว่า MS PowerPoint วางจุดข้อมูลจากสุดท้ายไปยังแรกหรือไม่. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | ระบุว่า MS PowerPoint วางจุดข้อมูลจากสุดท้ายไปยังแรกหรือไม่. |
| [isVisible()](#isVisible--) | ระบุว่าแกนแสดงหรือไม่. |
| [setVisible(boolean value)](#setVisible-boolean-) | ระบุว่าแกนแสดงหรือไม่. |
| [getMajorTickMark()](#getMajorTickMark--) | ระบุประเภทของเครื่องหมาย tick หลักสำหรับแกนที่ระบุ. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | ระบุประเภทของเครื่องหมาย tick หลักสำหรับแกนที่ระบุ. |
| [getMinorTickMark()](#getMinorTickMark--) | ระบุประเภทของเครื่องหมาย tick ย่อยสำหรับแกนที่ระบุ. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | ระบุประเภทของเครื่องหมาย tick ย่อยสำหรับแกนที่ระบุ. |
| [getTickLabelPosition()](#getTickLabelPosition--) | ระบุตำแหน่งของป้ายกำกับ tick-mark บนแกนที่ระบุ. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | ระบุตำแหน่งของป้ายกำกับ tick-mark บนแกนที่ระบุ. |
| [getMajorUnitScale()](#getMajorUnitScale--) | ระบุสเกลหน่วยหลักสำหรับแกนวันที่. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | ระบุสเกลหน่วยหลักสำหรับแกนวันที่. |
| [getMinorUnitScale()](#getMinorUnitScale--) | ระบุสเกลหน่วยหลักสำหรับแกนวันที่. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | ระบุสเกลหน่วยหลักสำหรับแกนวันที่. |
| [getBaseUnitScale()](#getBaseUnitScale--) | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | ระบุหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | ระบุรูปแบบเส้นกริดย่อยบนแกนของแผนภูมิ. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | ระบุรูปแบบเส้นกริดหลักบนแกนของแผนภูมิ. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | เพื่อซ่อนเส้นกริดย่อย ให้ตั้งค่า MinorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | เพื่อซ่อนเส้นกริดหลัก ให้ตั้งค่า MajorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. |
| [getFormat()](#getFormat--) | ระบุรูปแบบของแกน. |
| [getTextFormat()](#getTextFormat--) | ระบุรูปแบบของข้อความ. |
| [getTitle()](#getTitle--) | รับชื่อแกน. |
| [getCrossType()](#getCrossType--) | ระบุประเภทการตัดบนแกนที่ระบุที่แกนอื่นตัด. |
| [setCrossType(int value)](#setCrossType-int-) | ระบุประเภทการตัดบนแกนที่ระบุที่แกนอื่นตัด. |
| [getPosition()](#getPosition--) | ระบุตำแหน่งของแกน. |
| [setPosition(int value)](#setPosition-int-) | ระบุตำแหน่งของแกน. |
| [hasTitle()](#hasTitle--) | กำหนดว่าแกนมีชื่อที่มองเห็นได้หรือไม่. |
| [setTitle(boolean value)](#setTitle-boolean-) | กำหนดว่าแกนมีชื่อที่มองเห็นได้หรือไม่. |
| [getNumberFormat()](#getNumberFormat--) | ระบุสตริงรูปแบบสำหรับป้ายแกน. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | ระบุสตริงรูปแบบสำหรับป้ายแกน. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | ระบุว่ารูปแบบเชื่อมโยงข้อมูลต้นทางหรือไม่. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | ระบุว่ารูปแบบเชื่อมโยงข้อมูลต้นทางหรือไม่. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | ระบุมุมการหมุนของป้าย tick. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | ระบุมุมการหมุนของป้าย tick. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | ระบุจำนวนป้าย tick ที่ข้ามระหว่างป้ายที่วาด. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | ระบุจำนวนป้าย tick ที่ข้ามระหว่างป้ายที่วาด. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | ระบุค่าการเว้นระยะป้าย tick อัตโนมัติ. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | ระบุค่าการเว้นระยะป้าย tick อัตโนมัติ. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | ระบุจำนวนเครื่องหมาย tick ที่ข้ามก่อนที่จะวาดเครื่องหมายถัดไป. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | ระบุจำนวนเครื่องหมาย tick ที่ข้ามก่อนที่จะวาดเครื่องหมายถัดไป. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | ระบุค่าการเว้นระยะเครื่องหมาย tick อัตโนมัติ. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | ระบุค่าการเว้นระยะเครื่องหมาย tick อัตโนมัติ. |
| [getLabelOffset()](#getLabelOffset--) | ระยะห่างของป้ายจากแกน. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | ระยะห่างของป้ายจากแกน. |
| [getAggregationType()](#getAggregationType--) | ระบุประเภทการรวมของแกนหมวดหมู่ (การจัดกลุ่ม). |
| [setAggregationType(int value)](#setAggregationType-int-) | ระบุประเภทการรวมของแกนหมวดหมู่ (การจัดกลุ่ม). |
| [getBinWidth()](#getBinWidth--) | ระบุความกว้างของ bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | ระบุความกว้างของ bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | ระบุจำนวน bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | ระบุจำนวน bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | ระบุว่ามีการใช้ bin เกินขนาดหรือไม่. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | ระบุว่ามีการใช้ bin เกินขนาดหรือไม่. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | ระบุค่าของ overflow bin อัตโนมัติ. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | ระบุค่าของ overflow bin อัตโนมัติ. |
| [getOverflowBin()](#getOverflowBin--) | ระบุค่าที่กำหนดเองของ overflow bin. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | ระบุค่าที่กำหนดเองของ overflow bin. |
| [isUnderflowBin()](#isUnderflowBin--) | ระบุว่ามีการใช้ bin ต่ำกว่าหรือไม่. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | ระบุว่ามีการใช้ bin ต่ำกว่าหรือไม่. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | ระบุค่าของ underflow bin อัตโนมัติ. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | ระบุค่าของ underflow bin อัตโนมัติ. |
| [getUnderflowBin()](#getUnderflowBin--) | ระบุค่าที่กำหนดเองของ underflow bin. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | ระบุค่าที่กำหนดเองของ underflow bin. |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | ส่งคืนการนำเสนอแม่ของ FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

ส่งคืนแผนภูมิแม่. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

ระบุว่าแกนค่าข้ามแกนประเภทระหว่างหมวดหมู่หรือไม่. คุณสมบัตินี้ใช้ได้เฉพาะกับแกนประเภทเท่านั้นและไม่ใช้กับแผนภูมิ 3 มิติ. อ่าน/เขียน boolean.

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

ระบุว่าแกนค่าข้ามแกนประเภทระหว่างหมวดหมู่หรือไม่. คุณสมบัตินี้ใช้ได้เฉพาะกับแกนประเภทเท่านั้นและไม่ใช้กับแผนภูมิ 3 มิติ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

ระบุประเภทของแกนหมวดหมู่. อ่าน/เขียน [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**คืนค่า:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

ระบุประเภทของแกนหมวดหมู่. อ่าน/เขียน [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดโดยอัตโนมัติตามข้อมูลแกน.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

ระบุจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. อ่าน/เขียน float.

**คืนค่า:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

ระบุจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. อ่าน/เขียน [DisplayUnitType](../../com.aspose.slides/displayunittype).

**คืนค่า:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

ระบุค่าการปรับสเกลของหน่วยแสดงผลสำหรับแกนค่า. อ่าน/เขียน [DisplayUnitType](../../com.aspose.slides/displayunittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

ระบุค่าสูงสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**คืนค่า:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

ระบุค่าต่ำสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**คืนค่า:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

ระบุหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**คืนค่า:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

ระบุหน่วยย่อยจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**คืนค่า:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

ระบุสเกลหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**คืนค่า:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

ระบุสเกลหน่วยย่อยจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนหน้าเพื่อรับค่าจริง.

**คืนค่า:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

ระบุว่าค่ามากสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

ระบุว่าค่ามากสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

ระบุค่าสูงสุดบนแกนค่า. อ่าน/เขียน double.

**คืนค่า:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

ระบุค่าสูงสุดบนแกนค่า. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

ระบุหน่วยย่อยสำหรับแกนวันที่หรือค่า. อ่าน/เขียน double.

**คืนค่า:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

ระบุหน่วยย่อยสำหรับแกนวันที่หรือค่า. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
ระบุว่าหน่วยย่อยของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


ระบุว่าหน่วยย่อยของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า. อ่าน/เขียน double.

**คืนค่า:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


ระบุว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


ระบุว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


ระบุว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


ระบุว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


แสดงค่าต่ำสุดบนแกนค่า. อ่าน/เขียน double.

**คืนค่า:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


แสดงค่าต่ำสุดบนแกนค่า. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


แสดงว่าประเภทสเกลของแกนค่าคือเชิงลอการิทึมหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


แสดงว่าประเภทสเกลของแกนค่าคือเชิงลอการิทึมหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


แสดงฐานเชิงลอการิทึม. ค่าปริยายคือ 10. อ่าน/เขียน double.

**คืนค่า:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


แสดงฐานเชิงลอการิทึม. ค่าปริยายคือ 10. อ่าน/เขียน double.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


แสดงว่า MS PowerPoint วาดจุดข้อมูลจากท้ายไปเริ่มต้นหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


แสดงว่า MS PowerPoint วาดจุดข้อมูลจากท้ายไปเริ่มต้นหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


แสดงว่าแกนมองเห็นได้หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


แสดงว่าแกนมองเห็นได้หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


แสดงประเภทของเครื่องหมายหลักสำหรับแกนที่ระบุ. อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**คืนค่า:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


แสดงประเภทของเครื่องหมายหลักสำหรับแกนที่ระบุ. อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


แสดงประเภทของเครื่องหมายย่อยสำหรับแกนที่ระบุ. อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**คืนค่า:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


แสดงประเภทของเครื่องหมายย่อยสำหรับแกนที่ระบุ. อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ. อ่าน/เขียน [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**คืนค่า:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ. อ่าน/เขียน [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


แสดงสเกลหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**คืนค่า:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


แสดงสเกลหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


แสดงสเกลหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**คืนค่า:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


แสดงสเกลหน่วยหลักสำหรับแกนวันที่. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**คืนค่า:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


แสดงรูปแบบเส้นกริดย่อยบนแกนแผนภูมิ. อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**คืนค่า:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


แสดงรูปแบบเส้นกริดหลักบนแกนแผนภูมิ. อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**คืนค่า:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


เพื่อซ่อนเส้นกริดย่อยให้ตั้งค่า MinorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


เพื่อซ่อนเส้นกริดหลักให้ตั้งค่า MajorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


แสดงรูปแบบของแกน. อ่านอย่างเดียว [IAxisFormat](../../com.aspose.slides/iaxisformat).

**คืนค่า:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


แสดงรูปแบบของข้อความ. อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**คืนค่า:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


รับชื่อหัวเรื่องของแกน. อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle).

**คืนค่า:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


แสดง CrossType บนแกนที่ระบุที่แกนอื่นตัดกัน. อ่าน/เขียน [CrossesType](../../com.aspose.slides/crossestype).

**คืนค่า:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


แสดง CrossType บนแกนที่ระบุที่แกนอื่นตัดกัน. อ่าน/เขียน [CrossesType](../../com.aspose.slides/crossestype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


แสดงตำแหน่งของแกน. อ่าน/เขียน [AxisPositionType](../../com.aspose.slides/axispositiontype).

**คืนค่า:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


แสดงตำแหน่งของแกน. อ่าน/เขียน [AxisPositionType](../../com.aspose.slides/axispositiontype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


กำหนดว่ามีชื่อหัวเรื่องที่มองเห็นได้บนแกนหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


กำหนดว่ามีชื่อหัวเรื่องที่มองเห็นได้บนแกนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


แสดงสตริงรูปแบบสำหรับป้ายแกน. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


แสดงสตริงรูปแบบสำหรับป้ายแกน. อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


ระบุว่ารูปแบบเชื่อมโยงกับข้อมูลแหล่งที่มาหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


ระบุว่ารูปแบบเชื่อมโยงกับข้อมูลแหล่งที่มาหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


แสดงมุมการหมุนของป้ายกำกับเครื่องหมาย. อ่าน/เขียน float.

**คืนค่า:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


แสดงมุมการหมุนของป้ายกำกับเครื่องหมาย. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


กำหนดจำนวนป้ายกำกับเครื่องหมายที่ข้ามระหว่างป้ายที่ถูกวาด. ใช้กับแกนประเภทหรือแกนชุดข้อมูล. อ่าน/เขียน long.

**คืนค่า:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


กำหนดจำนวนป้ายกำกับเครื่องหมายที่ข้ามระหว่างป้ายที่ถูกวาด. ใช้กับแกนประเภทหรือแกนชุดข้อมูล. อ่าน/เขียน long.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


กำหนดค่าการเว้นระยะของป้ายกำกับเครื่องหมายอัตโนมัติ. หากเป็น false ให้ใช้คุณสมบัติ TickLabelSpacing. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


กำหนดค่าการเว้นระยะของป้ายกำกับเครื่องหมายอัตโนมัติ. หากเป็น false ให้ใช้คุณสมบัติ TickLabelSpacing. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


กำหนดจำนวนเครื่องหมายที่ต้องข้ามก่อนวาดเครื่องหมายถัดไป. ใช้กับแกนประเภทหรือแกนชุดข้อมูล. อ่าน/เขียน int.

**คืนค่า:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


กำหนดจำนวนเครื่องหมายที่ต้องข้ามก่อนวาดเครื่องหมายถัดไป. ใช้กับแกนประเภทหรือแกนชุดข้อมูล. อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


กำหนดค่าการเว้นระยะของเครื่องหมายอัตโนมัติ. หากเป็น false ให้ใช้คุณสมบัติ TickMarksSpacing. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


กำหนดค่าการเว้นระยะของเครื่องหมายอัตโนมัติ. หากเป็น false ให้ใช้คุณสมบัติ TickMarksSpacing. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


กำหนดระยะห่างของป้ายจากแกน. ใช้กับแกนประเภทหรือแกนวันที่. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. อ่าน/เขียน int.

**คืนค่า:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


กำหนดระยะห่างของป้ายจากแกน. ใช้กับแกนประเภทหรือแกนวันที่. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. อ่าน/เขียน int.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

แสดงประเภทการรวมของแกนหมวดหมู่ (การจัดกลุ่ม). ใช้กับหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**คืนค่า:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

แสดงประเภทการรวมของแกนหมวดหมู่ (การจัดกลุ่ม). ใช้กับหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

ระบุความกว้างของบิ้นเมื่อค่าคุณสมบัติ AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth. ใช้กับแกนหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**คืนค่า:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

ระบุความกว้างของบิ้นเมื่อค่าคุณสมบัติ AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth. ใช้กับแกนหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

ระบุจำนวนของบิ้นเมื่อค่าคุณสมบัติ AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins. ใช้กับแกนหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**คืนค่า:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

ระบุจำนวนของบิ้นเมื่อค่าคุณสมบัติ AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins. ใช้กับแกนหมวดหมู่. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

ระบุว่ามีการใช้บิ้น overflow หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบิ้น overflow.

**คืนค่า:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

ระบุว่ามีการใช้บิ้น overflow หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบิ้น overflow.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

ระบุค่าบิ้น overflow อัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ OverflowBin.

**คืนค่า:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

ระบุค่าบิ้น overflow อัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ OverflowBin.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

ระบุค่าบิ้น overflow ที่กำหนดเอง. ใช้เมื่อคุณสมบัติ IsAutomaticOverflowBin ถูกตั้งเป็น false และคุณสมบัติ IsOverflowBin มีค่า true.

**คืนค่า:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

ระบุค่าบิ้น overflow ที่กำหนดเอง. ใช้เมื่อคุณสมบัติ IsAutomaticOverflowBin ถูกตั้งเป็น false และคุณสมบัติ IsOverflowBin มีค่า true.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

ระบุว่ามีการใช้บิ้น underflow หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบิ้น underflow.

**คืนค่า:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

ระบุว่ามีการใช้บิ้น underflow หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบิ้น underflow.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

ระบุค่าบิ้น underflow อัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ UnderflowBin.

**คืนค่า:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

ระบุค่าบิ้น underflow อัตโนมัติ. หากเป็น false: ใช้คุณสมบัติ UnderflowBin.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

ระบุค่าบิ้น underflow ที่กำหนดเอง. ใช้เมื่อคุณสมบัติ IsAutomaticUnderflowBin ถูกตั้งเป็น false และคุณสมบัติ IsUnderflowBin มีค่า true.

**คืนค่า:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

ระบุค่าบิ้น underflow ที่กำหนดเอง. ใช้เมื่อคุณสมบัติ IsAutomaticUnderflowBin ถูกตั้งเป็น false และคุณสมบัติ IsUnderflowBin มีค่า true.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์พาเรนต์ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนการพรีเซนเทชั่นพาเรนต์ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)