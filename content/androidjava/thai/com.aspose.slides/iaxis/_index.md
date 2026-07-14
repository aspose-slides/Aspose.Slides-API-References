---
title: IAxis
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ห่อหุ้มอ็อบเจ็กต์ที่แทนแกนของแผนภูมิ
type: docs
url: /th/com.aspose.slides/iaxis/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

ห่อหุ้มอ็อบเจ็กต์ที่แทนแกนของแผนภูมิ
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | แสดงว่ากราฟแกนค่าข้ามแกนประเภทระหว่างหมวดหมู่หรือไม่ |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | แสดงว่ากราฟแกนค่าข้ามแกนประเภทระหว่างหมวดหมู่หรือไม่ |
| [getCrossAt()](#getCrossAt--) | แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน |
| [setCrossAt(float value)](#setCrossAt-float-) | แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน |
| [getDisplayUnit()](#getDisplayUnit--) | กำหนดค่าการสเกลของหน่วยการแสดงผลสำหรับแกนค่า |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | กำหนดค่าการสเกลของหน่วยการแสดงผลสำหรับแกนค่า |
| [getActualMaxValue()](#getActualMaxValue--) | ระบุค่าสูงสุดจริงบนแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง |
| [getActualMinValue()](#getActualMinValue--) | ระบุค่าต่ำสุดจริงบนแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง |
| [getActualMajorUnit()](#getActualMajorUnit--) | ระบุหน่วยหลักจริงของแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง |
| [getActualMinorUnit()](#getActualMinorUnit--) | ระบุหน่วยรองจริงของแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | ระบุสเกลหน่วยหลักจริงของแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | ระบุสเกลหน่วยรองจริงของแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | บ่งชี้ว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | บ่งชี้ว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [getMaxValue()](#getMaxValue--) | แสดงค่ามากสุดบนแกนค่า |
| [setMaxValue(double value)](#setMaxValue-double-) | แสดงค่ามากสุดบนแกนค่า |
| [getMinorUnit()](#getMinorUnit--) | แสดงหน่วยรองสำหรับแกนวันที่หรือค่า |
| [setMinorUnit(double value)](#setMinorUnit-double-) | แสดงหน่วยรองสำหรับแกนวันที่หรือค่า |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [getMajorUnit()](#getMajorUnit--) | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า |
| [setMajorUnit(double value)](#setMajorUnit-double-) | แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | บ่งชี้ว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | บ่งชี้ว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่ |
| [getMinValue()](#getMinValue--) | แสดงค่าต่ำสุดบนแกนค่า |
| [setMinValue(double value)](#setMinValue-double-) | แสดงค่าต่ำสุดบนแกนค่า |
| [isLogarithmic()](#isLogarithmic--) | แสดงว่าแบบสเกลของแกนค่ามีรูปแบบลอการิทึมหรือไม่ |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | แสดงว่าแบบสเกลของแกนค่ามีรูปแบบลอการิทึมหรือไม่ |
| [getLogBase()](#getLogBase--) | แสดงฐานของลอการิทึม |
| [setLogBase(double value)](#setLogBase-double-) | แสดงฐานของลอการิทึม |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | แสดงว่า Microsoft PowerPoint วางจุดข้อมูลจากสุดท้ายไปยังแรกหรือไม่ |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | แสดงว่า Microsoft PowerPoint วางจุดข้อมูลจากสุดท้ายไปยังแรกหรือไม่ |
| [isVisible()](#isVisible--) | แสดงว่าแกนมองเห็นได้หรือไม่ |
| [setVisible(boolean value)](#setVisible-boolean-) | แสดงว่าแกนมองเห็นได้หรือไม่ |
| [getMajorTickMark()](#getMajorTickMark--) | แสดงประเภทของเครื่องหมายหลักบนแกนที่ระบุ |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | แสดงประเภทของเครื่องหมายหลักบนแกนที่ระบุ |
| [getMinorTickMark()](#getMinorTickMark--) | แสดงประเภทของเครื่องหมายรองบนแกนที่ระบุ |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | แสดงประเภทของเครื่องหมายรองบนแกนที่ระบุ |
| [getTickLabelPosition()](#getTickLabelPosition--) | แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ |
| [getMajorUnitScale()](#getMajorUnitScale--) | แสดงสเกลหน่วยหลักสำหรับแกนวันที่ |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | แสดงสเกลหน่วยหลักสำหรับแกนวันที่ |
| [getMinorUnitScale()](#getMinorUnitScale--) | แสดงสเกลหน่วยหลักสำหรับแกนวันที่ |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | แสดงสเกลหน่วยหลักสำหรับแกนวันที่ |
| [getBaseUnitScale()](#getBaseUnitScale--) | กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่ |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่ |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | แสดงรูปแบบเส้นกริดรองบนแกนของแผนภูมิ |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | แสดงรูปแบบเส้นกริดหลักบนแกนของแผนภูมิ |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | แสดงว่าเส้นกริดรองแสดงหรือไม่ |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | แสดงว่าเส้นกริดหลักแสดงหรือไม่ |
| [getFormat()](#getFormat--) | แสดงรูปแบบของแกน |
| [getTitle()](#getTitle--) | รับชื่อแกน |
| [getCrossType()](#getCrossType--) | แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้ามผ่าน |
| [setCrossType(int value)](#setCrossType-int-) | แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้ามผ่าน |
| [getPosition()](#getPosition--) | แสดงตำแหน่งของแกน |
| [setPosition(int value)](#setPosition-int-) | แสดงตำแหน่งของแกน |
| [hasTitle()](#hasTitle--) | กำหนดว่าแกนมีชื่อที่มองเห็นได้หรือไม่ |
| [setTitle(boolean value)](#setTitle-boolean-) | กำหนดว่าแกนมีชื่อที่มองเห็นได้หรือไม่ |
| [getNumberFormat()](#getNumberFormat--) | แสดงสตริงรูปแบบสำหรับป้ายแกน |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | แสดงสตริงรูปแบบสำหรับป้ายแกน |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | แสดงมุมการหมุนของป้ายเครื่องหมาย อ่าน/เขียน float |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | แสดงมุมการหมุนของป้ายเครื่องหมาย อ่าน/เขียน float |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | กำหนดจำนวนป้ายเครื่องหมายที่ข้ามระหว่างป้ายที่จะแสดง |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | กำหนดจำนวนป้ายเครื่องหมายที่ข้ามระหว่างป้ายที่จะแสดง |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | กำหนดค่าระยะห่างอัตโนมัติของป้ายเครื่องหมาย |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | กำหนดค่าระยะห่างอัตโนมัติของป้ายเครื่องหมาย |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | กำหนดจำนวนเครื่องหมายที่จะข้ามก่อนที่เครื่องหมายต่อไปจะถูกวาด |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | กำหนดจำนวนเครื่องหมายที่จะข้ามก่อนที่เครื่องหมายต่อไปจะถูกวาด |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | กำหนดค่าระยะห่างอัตโนมัติของเครื่องหมาย |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | กำหนดค่าระยะห่างอัตโนมัติของเครื่องหมาย |
| [getLabelOffset()](#getLabelOffset--) | กำหนดระยะห่างของป้ายจากแกน |
| [setLabelOffset(int value)](#setLabelOffset-int-) | กำหนดระยะห่างของป้ายจากแกน |
| [getCategoryAxisType()](#getCategoryAxisType--) | กำหนดประเภทของแกนประเภท |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | กำหนดประเภทของแกนประเภท |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดอัตโนมัติตามข้อมูลแกน |
| [getAggregationType()](#getAggregationType--) | แสดงประเภทการรวมของแกนหมวดหมู่ (การแบ่งเป็นช่อง) |
| [setAggregationType(int value)](#setAggregationType-int-) | แสดงประเภทการรวมของแกนหมวดหมู่ (การแบ่งเป็นช่อง) |
| [getBinWidth()](#getBinWidth--) | กำหนดความกว้างของบิ้นเมื่อคุณสมบัติ AggregationType ตั้งค่าเป็น AxisAggregationType.ByBinWidth |
| [setBinWidth(double value)](#setBinWidth-double-) | กำหนดความกว้างของบิ้นเมื่อคุณสมบัติ AggregationType ตั้งค่าเป็น AxisAggregationType.ByBinWidth |
| [getNumberOfBins()](#getNumberOfBins--) | กำหนดจำนวนบิ้นเมื่อคุณสมบัติ AggregationType ตั้งค่าเป็น AxisAggregationType.ByNumberOfBins |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | กำหนดจำนวนบิ้นเมื่อคุณสมบัติ AggregationType ตั้งค่าเป็น AxisAggregationType.ByNumberOfBins |
| [isOverflowBin()](#isOverflowBin--) | ระบุว่ามีการใช้บิ้น overflow หรือไม่ |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | ระบุว่ามีการใช้บิ้น overflow หรือไม่ |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | ระบุค่าบิ้น overflow อัตโนมัติ |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | ระบุค่าบิ้น overflow อัตโนมัติ |
| [getOverflowBin()](#getOverflowBin--) | ระบุค่าบิ้น overflow ที่กำหนดเอง |
| [setOverflowBin(double value)](#setOverflowBin-double-) | ระบุค่าบิ้น overflow ที่กำหนดเอง |
| [isUnderflowBin()](#isUnderflowBin--) | ระบุว่ามีการใช้บิ้น underflow หรือไม่ |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | ระบุว่ามีการใช้บิ้น underflow หรือไม่ |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | ระบุค่าบิ้น underflow อัตโนมัติ |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | ระบุค่าบิ้น underflow อัตโนมัติ |
| [getUnderflowBin()](#getUnderflowBin--) | ระบุค่าบิ้น underflow ที่กำหนดเอง |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | ระบุค่าบิ้น underflow ที่กำหนดเอง |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

แสดงว่ากราฟแกนค่าข้ามแกนประเภทระหว่างหมวดหมู่หรือไม่ คุณสมบัตินี้ใช้ได้เฉพาะกับแกนประเภทเท่านั้นและไม่ใช้กับแผนภูมิ 3-D อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

แสดงว่ากราฟแกนค่าข้ามแกนประเภทระหว่างหมวดหมู่หรือไม่ คุณสมบัตินี้ใช้ได้เฉพาะกับแกนประเภทเท่านั้นและไม่ใช้กับแผนภูมิ 3-D อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน อ่าน/เขียน float

**ค่าที่ส่งคืน:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

แสดงจุดบนแกนที่แกนตั้งฉากข้ามผ่าน อ่าน/เขียน float

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

กำหนดค่าการสเกลของหน่วยการแสดงผลสำหรับแกนค่า อ่าน/เขียน [DisplayUnitType](../../com.aspose.slides/displayunittype)

**ค่าที่ส่งคืน:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

กำหนดค่าการสเกลของหน่วยการแสดงผลสำหรับแกนค่า อ่าน/เขียน [DisplayUnitType](../../com.aspose.slides/displayunittype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

ระบุค่าสูงสุดจริงบนแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง

**ค่าที่ส่งคืน:**
double
### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

ระบุค่าต่ำสุดจริงบนแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง

**ค่าที่ส่งคืน:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

ระบุหน่วยหลักจริงของแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง

**ค่าที่ส่งคืน:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

ระบุหน่วยรองจริงของแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง

**ค่าที่ส่งคืน:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

ระบุสเกลหน่วยหลักจริงของแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง

**ค่าที่ส่งคืน:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

ระบุสเกลหน่วยรองจริงของแกน ต้องเรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง

**ค่าที่ส่งคืน:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

บ่งชี้ว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

บ่งชี้ว่าค่าสูงสุดถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

แสดงค่ามากสุดบนแกนค่า อ่าน/เขียน double

**ค่าที่ส่งคืน:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

แสดงค่ามากสุดบนแกนค่า อ่าน/เขียน double

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

แสดงหน่วยรองสำหรับแกนวันที่หรือค่า อ่าน/เขียน double

**ค่าที่ส่งคืน:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

แสดงหน่วยรองสำหรับแกนวันที่หรือค่า อ่าน/เขียน double

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

บ่งชี้ว่าหน่วยรองของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า อ่าน/เขียน double

**ค่าที่ส่งคืน:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

แสดงหน่วยหลักสำหรับแกนวันที่หรือค่า อ่าน/เขียน double

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

บ่งชี้ว่าหน่วยหลักของแกนถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

บ่งชี้ว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

บ่งชี้ว่าค่าต่ำสุดถูกกำหนดโดยอัตโนมัติหรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

แสดงค่าต่ำสุดบนแกนค่า อ่าน/เขียน double

**ค่าที่ส่งคืน:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

แสดงค่าต่ำสุดบนแกนค่า อ่าน/เขียน double

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

แสดงว่าแบบสเกลของแกนค่ามีรูปแบบลอการิทึมหรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

แสดงว่าแบบสเกลของแกนค่ามีรูปแบบลอการิทึมหรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

แสดงฐานของลอการิทึม ค่าเริ่มต้นคือ 10 อ่าน/เขียน double

**ค่าที่ส่งคืน:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

แสดงฐานของลอการิทึม ค่าเริ่มต้นคือ 10 อ่าน/เขียน double

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

แสดงว่า Microsoft PowerPoint วางจุดข้อมูลจากสุดท้ายไปยังแรกหรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

แสดงว่า Microsoft PowerPoint วางจุดข้อมูลจากสุดท้ายไปยังแรกหรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

แสดงว่าแกนมองเห็นได้หรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

แสดงว่าแกนมองเห็นได้หรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

แสดงประเภทของเครื่องหมายหลักบนแกนที่ระบุ อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype)

**ค่าที่ส่งคืน:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

แสดงประเภทของเครื่องหมายหลักบนแกนที่ระบุ อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

แสดงประเภทของเครื่องหมายรองบนแกนที่ระบุ อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype)

**ค่าที่ส่งคืน:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

แสดงประเภทของเครื่องหมายรองบนแกนที่ระบุ อ่าน/เขียน [TickMarkType](../../com.aspose.slides/tickmarktype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ อ่าน/เขียน [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)

**ค่าที่ส่งคืน:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

แสดงตำแหน่งของป้ายกำกับเครื่องหมายบนแกนที่ระบุ อ่าน/เขียน [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

แสดงสเกลหน่วยหลักสำหรับแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype)

**ค่าที่ส่งคืน:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

แสดงสเกลหน่วยหลักสำหรับแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

แสดงสเกลหน่วยหลักสำหรับแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype)

**ค่าที่ส่งคืน:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

แสดงสเกลหน่วยหลักสำหรับแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype)

**ค่าที่ส่งคืน:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

กำหนดหน่วยเวลาที่เล็กที่สุดที่แสดงบนแกนวันที่ อ่าน/เขียน [TimeUnitType](../../com.aspose.slides/timeunittype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

แสดงรูปแบบเส้นกริดรองบนแกนของแผนภูมิ อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

**ค่าที่ส่งคืน:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

แสดงรูปแบบเส้นกริดหลักบนแกนของแผนภูมิ อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

**ค่าที่ส่งคืน:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

แสดงว่าเส้นกริดรองแสดงหรือไม่ อ่านอย่างเดียว boolean

**ค่าที่ส่งคืน:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

แสดงว่าเส้นกริดหลักแสดงหรือไม่ อ่านอย่างเดียว boolean

**ค่าที่ส่งคืน:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

แสดงรูปแบบของแกน อ่านอย่างเดียว [IAxisFormat](../../com.aspose.slides/iaxisformat)

**ค่าที่ส่งคืน:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

รับชื่อแกน อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle)

**ค่าที่ส่งคืน:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้ามผ่าน อ่าน/เขียน [CrossesType](../../com.aspose.slides/crossestype)

**ค่าที่ส่งคืน:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

 แสดง CrossType บนแกนที่ระบุที่แกนอื่นข้ามผ่าน อ่าน/เขียน [CrossesType](../../com.aspose.slides/crossestype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

แสดงตำแหน่งของแกน อ่าน/เขียน [AxisPositionType](../../com.aspose.slides/axispositiontype)

**ค่าที่ส่งคืน:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

แสดงตำแหน่งของแกน อ่าน/เขียน [AxisPositionType](../../com.aspose.slides/axispositiontype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

กำหนดว่าแกนมีชื่อที่มองเห็นได้หรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

กำหนดว่าแกนมีชื่อที่มองเห็นได้หรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

แสดงสตริงรูปแบบสำหรับป้ายแกน อ่าน/เขียน String

**ค่าที่ส่งคืน:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

แสดงสตริงรูปแบบสำหรับป้ายแกน อ่าน/เขียน String

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract       bool        isNumberFormatLinkedToSource()
```

บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

บ่งชี้ว่ารูปแบบเชื่อมโยงกับข้อมูลต้นทางหรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

แสดงมุมการหมุนของป้ายเครื่องหมาย อ่าน/เขียน float

**ค่าที่ส่งคืน:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

แสดงมุมการหมุนของป้ายเครื่องหมาย อ่าน/เขียน float

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

กำหนดจำนวนป้ายเครื่องหมายที่ข้ามระหว่างป้ายที่จะแสดง อ่าน/เขียน long

**ค่าที่ส่งคืน:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

กำหนดจำนวนป้ายเครื่องหมายที่ข้ามระหว่างป้ายที่จะแสดง อ่าน/เขียน long

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

กำหนดค่าระยะห่างอัตโนมัติของป้ายเครื่องหมาย หาก false: ใช้คุณสมบัติ TickLabelSpacing อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

กำหนดค่าระยะห่างอัตโนมัติของป้ายเครื่องหมาย หาก false: ใช้คุณสมบัติ TickLabelSpacing อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

กำหนดจำนวนเครื่องหมายที่จะข้ามก่อนที่เครื่องหมายต่อไปจะถูกวาด ใช้กับแกนประเภทหรือซีรีส์ อ่าน/เขียน int

**ค่าที่ส่งคืน:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

กำหนดจำนวนเครื่องหมายที่จะข้ามก่อนที่เครื่องหมายต่อไปจะถูกวาด ใช้กับแกนประเภทหรือซีรีส์ อ่าน/เขียน int

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

กำหนดค่าระยะห่างอัตโนมัติของเครื่องหมาย หาก false: ใช้คุณสมบัติ TickMarksSpacing อ่าน/เขียน boolean

**ค่าที่ส่งคืน:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

กำหนดค่าระยะห่างอัตโนมัติของเครื่องหมาย หาก false: ใช้คุณสมบัติ TickMarksSpacing อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

กำหนดระยะห่างของป้ายจากแกน ใช้กับแกนประเภทหรือวันที่ ค่าต้องอยู่ระหว่าง 0% และ 1000% อ่าน/เขียน int

**ค่าที่ส่งคืน:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

กำหนดระยะห่างของป้ายจากแกน ใช้กับแกนประเภทหรือวันที่ ค่าต้องอยู่ระหว่าง 0% และ 1000% อ่าน/เขียน int

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

กำหนดประเภทของแกนหมวดหมู่ อ่าน/เขียน [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))

**ค่าที่ส่งคืน:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

กำหนดประเภทของแกนหมวดหมู่ อ่าน/เขียน [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

ตั้งค่าคุณสมบัติ IAxis.CategoryAxisType ด้วยค่าที่กำหนดอัตโนมัติตามข้อมูลแกน

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

แสดงประเภทการรวมของแกนหมวดหมู่ (การแบ่งเป็นช่อง) ใช้กับแกนประเภทเท่านั้น ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น

**ค่าที่ส่งคืน:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

แสดงประเภทการรวมของแกนหมวดหมู่ (การแบ่งเป็นช่อง) ใช้กับแกนประเภทเท่านั้น ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

กำหนดความกว้างของบิ้นเมื่อคุณสมบัติ AggregationType ตั้งค่าเป็น AxisAggregationType.ByBinWidth ใช้กับแกนประเภทเท่านั้น ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น

**ค่าที่ส่งคืน:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

กำหนดความกว้างของบิ้นเมื่อคุณสมบัติ AggregationType ตั้งค่าเป็น AxisAggregationType.ByBinWidth ใช้กับแกนประเภทเท่านั้น ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

กำหนดจำนวนบิ้นเมื่อคุณสมบัติ AggregationType ตั้งค่าเป็น AxisAggregationType.ByNumberOfBins ใช้กับแกนประเภทเท่านั้น ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น

**ค่าที่ส่งคืน:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

กำหนดจำนวนบิ้นเมื่อคุณสมบัติ AggregationType ตั้งค่าเป็น AxisAggregationType.ByNumberOfBins ใช้กับแกนประเภทเท่านั้น ใช้กับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

ระบุว่ามีการใช้บิ้น overflow หรือไม่ ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบิ้น overflow

**ค่าที่ส่งคืน:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

ระบุว่ามีการใช้บิ้น overflow หรือไม่ ใช้ IsAutomaticOverflowBin และ OverflowBin เพื่อปรับค่าบิ้น overflow

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

ระบุค่าบิ้น overflow อัตโนมัติ หาก false: ใช้คุณสมบัติ OverflowBin

**ค่าที่ส่งคืน:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

ระบุค่าบิ้น overflow อัตโนมัติ หาก false: ใช้คุณสมบัติ OverflowBin

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

ระบุค่าบิ้น overflow ที่กำหนดเอง ใช้เมื่อ IsAutomaticOverflowBin ตั้งค่าเป็น false และ IsOverflowBin เป็น true

**ค่าที่ส่งคืน:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

ระบุค่าบิ้น overflow ที่กำหนดเอง ใช้เมื่อ IsAutomaticOverflowBin ตั้งค่าเป็น false และ IsOverflowBin เป็น true

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

ระบุว่ามีการใช้บิ้น underflow หรือไม่ ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบิ้น underflow

**ค่าที่ส่งคืน:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

ระบุว่ามีการใช้บิ้ง underflow หรือไม่ ใช้ IsAutomaticUnderflowBin และ UnderflowBin เพื่อปรับค่าบิ้น underflow

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

ระบุค่าบิ้ง underflow อัตโนมัติ หาก false: ใช้คุณสมบัติ UnderflowBin

**ค่าที่ส่งคืน:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

ระบุค่าบิ้ง underflow อัตโนมัติ หาก false: ใช้คุณสมบัติ UnderflowBin

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

ระบุค่าบิ้ง underflow ที่กำหนดเอง ใช้เมื่อ IsAutomaticUnderflowBin ตั้งค่าเป็น false และ IsUnderflowBin เป็น true

**ค่าที่ส่งคืน:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

ระบุค่าบิ้ง underflow ที่กำหนดเอง ใช้เมื่อ IsAutomaticUnderflowBin ตั้งค่าเป็น false และ IsUnderflowBin เป็น true

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |