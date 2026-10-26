---
title: Axis
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ห่อหุ้มอ็อบเจ็กต์ที่เป็นตัวแทนแกนของแผนภูมิ
type: docs
url: /th/com.aspose.slides/axis/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Encapsulates the object that represents a chart's axis.  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChart()](#getChart--) | ส่งคืน chart พาเรนท์ |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | แสดงว่าตำแหน่ง value axis ข้าม category axis ระหว่างหมวดหมู่ |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | แสดงว่าตำแหน่ง value axis ข้าม category axis ระหว่างหมวดหมู่ |
| [getCategoryAxisType()](#getCategoryAxisType--) | กำหนดประเภทของ category axis |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | กำหนดประเภทของ category axis |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | ตั้งค่า IAxis.CategoryAxisType property ด้วยค่าที่กำหนดโดยอัตโนมัติตามข้อมูลของแกน |
| [getCrossAt()](#getCrossAt--) | แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน |
| [setCrossAt(float value)](#setCrossAt-float-) | แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน |
| [getDisplayUnit()](#getDisplayUnit--) | กำหนดค่าการสเกลของหน่วยแสดงผลสำหรับ value axis |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | กำหนดค่าการสเกลของหน่วยแสดงผลสำหรับ value axis |
| [getActualMaxValue()](#getActualMaxValue--) | กำหนดค่าสูงสุดจริงบนแกน |
| [getActualMinValue()](#getActualMinValue--) | กำหนดค่าต่ำสุดจริงบนแกน |
| [getActualMajorUnit()](#getActualMajorUnit--) | กำหนดหน่วยหลักจริงของแกน |
| [getActualMinorUnit()](#getActualMinorUnit--) | กำหนดหน่วยรองจริงของแกน |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | กำหนดสเกลหน่วยหลักจริงของแกน |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | กำหนดสเกลหน่วยรองจริงของแกน |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | บ่งชี้ว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | บ่งชี้ว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [getMaxValue()](#getMaxValue--) | แสดงค่าสูงสุดบน value axis |
| [setMaxValue(double value)](#setMaxValue-double-) | แสดงค่าสูงสุดบน value axis |
| [getMinorUnit()](#getMinorUnit--) | แสดงหน่วยรองสำหรับ date หรือ value axis |
| [setMinorUnit(double value)](#setMinorUnit-double-) | แสดงหน่วยรองสำหรับ date หรือ value axis |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [getMajorUnit()](#getMajorUnit--) | แสดงหน่วยหลักสำหรับ date หรือ value axis |
| [setMajorUnit(double value)](#setMajorUnit-double-) | แสดงหน่วยหลักสำหรับ date หรือ value axis |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | บ่งชี้ว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | บ่งชี้ว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [getMinValue()](#getMinValue--) | แสดงค่าต่ำสุดบน value axis |
| [setMinValue(double value)](#setMinValue-double-) | แสดงค่าต่ำสุดบน value axis |
| [isLogarithmic()](#isLogarithmic--) | แสดงว่า type การสเกลของ value axis เป็นลอการิทึมหรือไม่ |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | แสดงว่า type การสเกลของ value axis เป็นลอการิทึมหรือไม่ |
| [getLogBase()](#getLogBase--) | แสดงฐานลอการิทึม |
| [setLogBase(double value)](#setLogBase-double-) | แสดงฐานลอการิทึม |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | แสดงว่า MS PowerPoint วาดจุดข้อมูลจากท้ายไปแรก |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | แสดงว่า MS PowerPoint วาดจุดข้อมูลจากท้ายไปแรก |
| [isVisible()](#isVisible--) | แสดงว่าแกนมองเห็นได้หรือไม่ |
| [setVisible(boolean value)](#setVisible-boolean-) | แสดงว่าแกนมองเห็นได้หรือไม่ |
| [getMajorTickMark()](#getMajorTickMark--) | แสดงประเภทของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | แสดงประเภทของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ |
| [getMinorTickMark()](#getMinorTickMark--) | แสดงประเภทของเครื่องหมายติ๊กรองสำหรับแกนที่ระบุ |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | แสดงประเภทของเครื่องหมายติ๊กรองสำหรับแกนที่ระบุ |
| [getTickLabelPosition()](#getTickLabelPosition--) | แสดงตำแหน่งของป้ายกำกับเครื่องหมายติ๊กบนแกนที่ระบุ |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | แสดงตำแหน่งของป้ายกำกับเครื่องหมายติ๊กบนแกนที่ระบุ |
| [getMajorUnitScale()](#getMajorUnitScale--) | แสดงสเกลหน่วยหลักสำหรับ date axis |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | แสดงสเกลหน่วยหลักสำหรับ date axis |
| [getMinorUnitScale()](#getMinorUnitScale--) | แสดงสเกลหน่วยหลักสำหรับ date axis |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | แสดงสเกลหน่วยหลักสำหรับ date axis |
| [getBaseUnitScale()](#getBaseUnitScale--) | กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบน date axis |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบน date axis |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | แสดงรูปแบบของเส้นกริดรองบนแกนแผนภูมิ |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | แสดงรูปแบบของเส้นกริดหลักบนแกนแผนภูมิ |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | เพื่อซ่อนเส้นกริดรอง ให้ตั้งค่า MinorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | เพื่อซ่อนเส้นกริดหลัก ให้ตั้งค่า MajorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill |
| [getFormat()](#getFormat--) | แสดงรูปแบบของแกน |
| [getTextFormat()](#getTextFormat--) | แสดงรูปแบบของข้อความ |
| [getTitle()](#getTitle--) | รับชื่อเรื่องของ axis |
| [getCrossType()](#getCrossType--) | แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้าม |
| [setCrossType(int value)](#setCrossType-int-) | แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้าม |
| [getPosition()](#getPosition--) | แสดงตำแหน่งของแกน |
| [setPosition(int value)](#setPosition-int-) | แสดงตำแหน่งของแกน |
| [hasTitle()](#hasTitle--) | กำหนดว่าแกนมีชื่อเรื่องที่มองเห็นได้หรือไม่ |
| [setTitle(boolean value)](#setTitle-boolean-) | กำหนดว่าแกนมีชื่อเรื่องที่มองเห็นได้หรือไม่ |
| [getNumberFormat()](#getNumberFormat--) | แสดงสตริงรูปแบบสำหรับป้ายชื่อ Axis |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | แสดงสตริงรูปแบบสำหรับป้ายชื่อ Axis |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | แสดงมุมการหมุนของป้ายกำกับติ๊ก |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | แสดงมุมการหมุนของป้ายกำกับติ๊ก |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | กำหนดจำนวนป้ายกำกับติ๊กที่ข้ามระหว่างป้ายที่ถูกวาด |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | กำหนดจำนวนป้ายกำกับติ๊กที่ข้ามระหว่างป้ายที่ถูกวาด |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | กำหนดค่าการเว้นระยะป้ายกำกับติ๊กอัตโนมัติ |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | กำหนดค่าการเว้นระยะป้ายกำกับติ๊กอัตโนมัติ |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | กำหนดจำนวนเครื่องหมายติ๊กที่ควรข้ามก่อนที่เครื่องหมายถัดไปจะถูกวาด |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | กำหนดจำนวนเครื่องหมายติ๊กที่ควรข้ามก่อนที่เครื่องหมายถัดไปจะถูกวาด |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | กำหนดค่าการเว้นระยะเครื่องหมายติ๊กอัตโนมัติ |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | กำหนดค่าการเว้นระยะเครื่องหมายติ๊กอัตโนมัติ |
| [getLabelOffset()](#getLabelOffset--) | กำหนดระยะห่างของป้ายจากแกน |
| [setLabelOffset(int value)](#setLabelOffset-int-) | กำหนดระยะห่างของป้ายจากแกน |
| [getAggregationType()](#getAggregationType--) | แสดงประเภทการรวมของ category axis (binning) |
| [setAggregationType(int value)](#setAggregationType-int-) | แสดงประเภทการรวมของ category axis (binning) |
| [getBinWidth()](#getBinWidth--) | กำหนดความกว้างของ bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth |
| [setBinWidth(double value)](#setBinWidth-double-) | กำหนดความกว้างของ bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth |
| [getNumberOfBins()](#getNumberOfBins--) | กำหนดจำนวน bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | กำหนดจำนวน bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins |
| [isOverflowBin()](#isOverflowBin--) | กำหนดว่ามีการใช้ overflow bin หรือไม่ |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | กำหนดว่ามีการใช้ overflow bin หรือไม่ |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | กำหนดค่าของ overflow bin อัตโนมัติ |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | กำหนดค่าของ overflow bin อัตโนมัติ |
| [getOverflowBin()](#getOverflowBin--) | กำหนดค่าที่กำหนดเองของ overflow bin |
| [setOverflowBin(double value)](#setOverflowBin-double-) | กำหนดค่าที่กำหนดเองของ overflow bin |
| [isUnderflowBin()](#isUnderflowBin--) | กำหนดว่ามีการใช้ underflow bin หรือไม่ |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | กำหนดว่ามีการใช้ underflow bin หรือไม่ |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | กำหนดค่าของ underflow bin อัตโนมัติ |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | กำหนดค่าของ underflow bin อัตโนมัติ |
| [getUnderflowBin()](#getUnderflowBin--) | กำหนดค่าที่กำหนดเองของ underflow bin |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | กำหนดค่าที่กำหนดเองของ underflow bin |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของ FillFormat |
| [getPresentation()](#getPresentation--) | ส่งคืนพรีเซนเทชันแม่ของ FillFormat |

### getChart() {#getChart--}
```
public final IChart getChart()
```

ส่งคืน chart พาเรนท์. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

แสดงว่าตำแหน่ง value axis ข้าม category axis ระหว่างหมวดหมู่. คุณสมบัตินี้ใช้กับ category axis เท่านั้นและไม่ใช้กับแผนภูมิ 3-D. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

แสดงว่าตำแหน่ง value axis ข้าม category axis ระหว่างหมวดหมู่. คุณสมบัตินี้ใช้กับ category axis เท่านั้นและไม่ใช้กับแผนภูมิ 3-D. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

กำหนดประเภทของ category axis. อ่าน/เขียน [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**คืนค่า:**  
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

กำหนดประเภทของ category axis. อ่าน/เขียน [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

ตั้งค่า IAxis.CategoryAxisType property ด้วยค่าที่กำหนดโดยอัตโนมัติตามข้อมูลของแกน.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. อ่าน/เขียน float.

**คืนค่า:**  
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน. อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

กำหนดค่าการสเกลของหน่วยแสดงผลสำหรับ value axis. อ่าน/เขียน [DisplayUnitType](../../com.aspose.slides/displayunittype).

**คืนค่า:**  
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

กำหนดค่าการสเกลของหน่วยแสดงผลสำหรับ value axis. อ่าน/เขียน [DisplayUnitType](../../com.aspose.slides/displayunittype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

กำหนดค่าสูงสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.

**คืนค่า:**  
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

กำหนดค่าต่ำสุดจริงบนแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.

**คืนค่า:**  
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

กำหนดหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.

**คืนค่า:**  
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

กำหนดหน่วยรองจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.

**คืนค่า:**  
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

กำหนดสเกลหน่วยหลักจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.

**คืนค่า:**  
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

กำหนดสเกลหน่วยรองจริงของแกน. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง.

**คืนค่า:**  
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

บ่งชี้ว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

บ่งชี้ว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

แสดงค่าสูงสุดบน value axis. อ่าน/เขียน double.

**คืนค่า:**  
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

แสดงค่าสูงสุดบน value axis. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

แสดงหน่วยรองสำหรับ date หรือ value axis. อ่าน/เขียน double.

**คืนค่า:**  
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

แสดงหน่วยรองสำหรับ date หรือ value axis. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

แสดงหน่วยหลักสำหรับ date หรือ value axis. อ่าน/เขียน double.

**คืนค่า:**  
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

แสดงหน่วยหลักสำหรับ date หรือ value axis. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

บ่งชี้ว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

บ่งชี้ว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

แสดงค่าต่ำสุดบน value axis. อ่าน/เขียน double.

**คืนค่า:**  
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

แสดงค่าต่ำสุดบน value axis. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

แสดงว่า type การสเกลของ value axis เป็นลอการิทึมหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

แสดงว่า type การสเกลของ value axis เป็นลอการิทึมหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

แสดงฐานลอการิทึม. ค่าเริ่มต้นคือ 10. อ่าน/เขียน double.

**คืนค่า:**  
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

แสดงฐานลอการิทึม. ค่าเริ่มต้นคือ 10. อ่าน/เขียน double.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public  final  boolean  isPlotOrderReversed()
```

แสดงว่า MS PowerPoint วาดจุดข้อมูลจากท้ายไปแรก. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

แสดงว่า MS PowerPoint วาดจุดข้อมูลจากท้ายไปแรก. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

แสดงประเภทของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ. อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**คืนค่า:**  
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

แสดงประเภทของเครื่องหมายติ๊กหลักสำหรับแกนที่ระบุ. อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

แสดงประเภทของเครื่องหมายติ๊กรองสำหรับแกนที่ระบุ. อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**คืนค่า:**  
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

แสดงประเภทของเครื่องหมายติ๊กรองสำหรับแกนที่ระบุ. อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

แสดงตำแหน่งของป้ายกำกับติ๊กบนแกนที่ระบุ. อ่าน/เขียน [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**คืนค่า:**  
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

แสดงตำแหน่งของป้ายกำกับติ๊กบนแกนที่ระบุ. อ่าน/เขียน [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

แสดงสเกลหน่วยหลักสำหรับ date axis. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**คืนค่า:**  
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

แสดงสเกลหน่วยหลักสำหรับ date axis. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

แสดงสเกลหน่วยหลักสำหรับ date axis. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**คืนค่า:**  
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

แสดงสเกลหน่วยหลักสำหรับ date axis. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบน date axis. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**คืนค่า:**  
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบน date axis. อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

แสดงรูปแบบของเส้นกริดรองบนแกนแผนภูมิ. อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**คืนค่า:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

แสดงรูปแบบของเส้นกริดหลักบนแกนแผนภูมิ. อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**คืนค่า:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

เพื่อซ่อนเส้นกริดรอง ให้ตั้งค่า MinorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

เพื่อซ่อนเส้นกริดหลัก ให้ตั้งค่า MajorGridLinesFormat.Line.FillFormat.FillType เป็น FillType.NoFill. อ่านอย่างเดียว boolean.

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

รับชื่อเรื่องของ axis. อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle).

**คืนค่า:**  
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้าม. อ่าน/เขียน [CrossesType](../../com.aspose.slides/crossestype).

**คืนค่า:**  
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้าม. อ่าน/เขียน [CrossesType](../../com.aspose.slides/crossestype).

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

กำหนดว่าแกนมีชื่อเรื่องที่มองเห็นได้หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

กำหนดว่าแกนมีชื่อเรื่องที่มองเห็นได้หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

แสดงสตริงรูปแบบสำหรับป้ายชื่อ Axis. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

แสดงสตริงรูปแบบสำหรับป้ายชื่อ Axis. อ่าน/เขียน String.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

แสดงมุมการหมุนของป้ายกำกับติ๊ก. อ่าน/เขียน float.

**คืนค่า:**  
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

แสดงมุมการหมุนของป้ายกำกับติ๊ก. อ่าน/เขียน float.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

กำหนดจำนวนป้ายกำกับติ๊กที่ข้ามระหว่างป้ายที่ถูกวาด. ใช้กับแกนประเภท category หรือ series. อ่าน/เขียน long.

**คืนค่า:**  
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

กำหนดจำนวนป้ายกำกับติ๊กที่ข้ามระหว่างป้ายที่ถูกวาด. ใช้กับแกนประเภท category หรือ series. อ่าน/เขียน long.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

กำหนดค่าการเว้นระยะป้ายกำกับติ๊กอัตโนมัติ. หาก false: ใช้ TickLabelSpacing property. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

กำหนดค่าการเว้นระยะป้ายกำกับติ๊กอัตโนมัติ. หาก false: ใช้ TickLabelSpacing property. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

กำหนดจำนวนเครื่องหมายติ๊กที่ควรข้ามก่อนที่เครื่องหมายถัดไปจะถูกวาด. ใช้กับแกนประเภท category หรือ series. อ่าน/เขียน int.

**คืนค่า:**  
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

กำหนดจำนวนเครื่องหมายติ๊กที่ควรข้ามก่อนที่เครื่องหมายถัดไปจะถูกวาด. ใช้กับแกนประเภท category หรือ series. อ่าน/เขียน int.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

กำหนดค่าการเว้นระยะเครื่องหมายติ๊กอัตโนมัติ. หาก false: ใช้ TickMarksSpacing property. อ่าน/เขียน boolean.

**คืนค่า:**  
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

กำหนดค่าการเว้นระยะเครื่องหมายติ๊กอัตโนมัติ. หาก false: ใช้ TickMarksSpacing property. อ่าน/เขียน boolean.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

กำหนดระยะห่างของป้ายจากแกน. ใช้กับแกนประเภท category หรือ date. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. อ่าน/เขียน int.

**คืนค่า:**  
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

กำหนดระยะห่างของป้ายจากแกน. ใช้กับแกนประเภท category หรือ date. ค่าต้องอยู่ระหว่าง 0% ถึง 1000%. อ่าน/เขียน int.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

แสดงประเภทการรวมของ category axis (binning). ใช้กับ category เท่านั้น. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**คืนค่า:**  
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

แสดงประเภทการรวมของ category axis (binning). ใช้กับ category เท่านั้น. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

กำหนดความกว้างของ bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth. ใช้กับแกนประเภท category. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**คืนค่า:**  
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

กำหนดความกว้างของ bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByBinWidth. ใช้กับแกนประเภท category. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

กำหนดจำนวน bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins. ใช้กับแกนประเภท category. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**คืนค่า:**  
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

กำหนดจำนวน bin เมื่อค่า AggregationType ถูกตั้งเป็น AxisAggregationType.ByNumberOfBins. ใช้กับแกนประเภท category. ใช้กับซีรีส์ Histogram หรือ HistogramPareto เท่านั้น.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

กำหนดว่ามีการใช้ overflow bin หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่า overflow bin.

**คืนค่า:**  
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

กำหนดว่ามีการใช้ overflow bin หรือไม่. ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่า overflow bin.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

กำหนดค่าของ overflow bin อัตโนมัติ. หาก false: ใช้ OverflowBin property.

**คืนค่า:**  
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

กำหนดค่าของ overflow bin อัตโนมัติ. หาก false: ใช้ OverflowBin property.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

กำหนดค่าที่กำหนดเองของ overflow bin. ใช้เมื่อ IsAutomaticOverflowBin ถูกตั้งเป็น false และ IsOverflowBin เป็น true.

**คืนค่า:**  
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

กำหนดค่าที่กำหนดเองของ overflow bin. ใช้เมื่อ IsAutomaticOverflowBin ถูกตั้งเป็น false และ IsOverflowBin เป็น true.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

กำหนดว่ามีการใช้ underflow bin หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่า underflow bin.

**คืนค่า:**  
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

กำหนดว่ามีการใช้ underflow bin หรือไม่. ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่า underflow bin.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

กำหนดค่าของ underflow bin อัตโนมัติ. หาก false: ใช้ UnderflowBin property.

**คืนค่า:**  
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

กำหนดค่าของ underflow bin อัตโนมัติ. หาก false: ใช้ UnderflowBin property.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

กำหนดค่าที่กำหนดเองของ underflow bin. ใช้เมื่อ IsAutomaticUnderflowBin ถูกตั้งเป็น false และ IsUnderflowBin เป็น true.

**คืนค่า:**  
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

กำหนดค่าที่กำหนดเองของ underflow bin. ใช้เมื่อ IsAutomaticUnderflowBin ถูกตั้งเป็น false และ IsUnderflowBin เป็น true.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนพรีเซนเทชันแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)