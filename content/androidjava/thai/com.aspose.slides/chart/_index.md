---
title: Chart
second_title: แอสโพรเซส.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของแผนภูกิกราฟิกบนสไลด์
type: docs
url: /th/com.aspose.slides/chart/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

แสดงกราฟิกแผนภูมิบนสไลด์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | คำนวณค่าจริงขององค์ประกอบแผนภูมิ |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | กำหนดว่ามีการพล็อตเฉพาะเซลล์ที่มองเห็นหรือไม่ |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | กำหนดว่ามีการพล็อตเฉพาะเซลล์ที่มองเห็นหรือไม่ |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | คืนค่า หรือ ตั้งค่าวิธีการพล็อตเซลล์ว่างในแผนภูมิ |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | คืนค่า หรือ ตั้งค่าวิธีการพล็อตเซลล์ว่างในแผนภูมิ |
| [getChartData()](#getChartData--) | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังอยู่ที่เกี่ยวข้องกับแผนภูมิ |
| [hasTitle()](#hasTitle--) | กำหนดว่าแผนภูมิมีหัวเรื่องที่มองเห็นหรือไม่ |
| [setTitle(boolean value)](#setTitle-boolean-) | กำหนดว่าแผนภูมิมีหัวเรื่องที่มองเห็นหรือไม่ |
| [getChartTitle()](#getChartTitle--) | คืนค่า หรือ ตั้งค่าหัวเรื่องของแผนภูมิ |
| [hasDataTable()](#hasDataTable--) | กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่ |
| [setDataTable(boolean value)](#setDataTable-boolean-) | กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่ |
| [hasLegend()](#hasLegend--) | กำหนดว่าแผนภูมิมีคำอธิบายหรือไม่ |
| [setLegend(boolean value)](#setLegend-boolean-) | กำหนดว่าแผนภูมิมีคำอธิบายหรือไม่ |
| [getLegend()](#getLegend--) | คืนค่า หรือ ตั้งค่าคำอธิบายสำหรับแผนภูมิ |
| [getChartDataTable()](#getChartDataTable--) | คืนค่าตารางข้อมูลของแผนภูมิ |
| [getStyle()](#getStyle--) | คืนค่า หรือ ตั้งค่าแบบแผนภูมิ |
| [setStyle(int value)](#setStyle-int-) | คืนค่า หรือ ตั้งค่าแบบแผนภูมิ |
| [getType()](#getType--) | คืนค่า หรือ ตั้งค่าชนิดแผนภูมิ |
| [setType(int value)](#setType-int-) | คืนค่า หรือ ตั้งค่าชนิดแผนภูมิ |
| [getPlotArea()](#getPlotArea--) | แสดงพื้นที่พล็อตของแผนภูมิ |
| [getRotation3D()](#getRotation3D--) | คืนค่าการหมุนแบบ 3 มิติของแผนภูมิ |
| [getBackWall()](#getBackWall--) | คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของกำแพงหลังของแผนภูมิ 3 มิติ |
| [getSideWall()](#getSideWall--) | คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของกำแพงด้านของแผนภูมิ 3 มิติ |
| [getFloor()](#getFloor--) | คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ |
| [getTextFormat()](#getTextFormat--) | คืนรูปแบบข้อความของแผนภูมิ |
| [createThemeEffective()](#createThemeEffective--) | คืนธีมที่ใช้ได้สำหรับแผนภูมินี้ |
| [getThemeManager()](#getThemeManager--) | คืนผู้จัดการธีม |
| [getUserShapes()](#getUserShapes--) | ระบุรูปทรงที่วาดบนแผนภูมิ |
| [getAxes()](#getAxes--) | ให้การเข้าถึงแกนของแผนภูมิ |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิ |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิ |
| [hasRoundedCorners()](#hasRoundedCorners--) | ระบุว่าพื้นที่แผนภูมิจะมีมุมโค้ง |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | ระบุว่าพื้นที่แผนภูมิจะมีมุมโค้ง |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

คำนวณค่าจริงขององค์ประกอบแผนภูมิ ค่าจริงประกอบด้วยตำแหน่งขององค์ประกอบที่ทำงาน IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

กำหนดว่ามีการพล็อตเฉพาะเซลล์ที่มองเห็นหรือไม่ ค่า False เพื่อพล็อตทั้งเซลล์ที่มองเห็นและซ่อนอยู่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

กำหนดว่ามีการพล็อตเฉพาะเซลล์ที่มองเห็นหรือไม่ ค่า False เพื่อพล็อตทั้งเซลล์ที่มองเห็นและซ่อนอยู่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

คืนค่า หรือ ตั้งค่าวิธีการพล็อตเซลล์ว่างในแผนภูมิ อ่าน/เขียน [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**คืนค่า:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

คืนค่า หรือ ตั้งค่าวิธีการพล็อตเซลล์ว่างในแผนภูมิ อ่าน/เขียน [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังอยู่ที่เกี่ยวข้องกับแผนภูมิ อ่านอย่างเดียว [IChartData](../../com.aspose.slides/ichartdata).

**คืนค่า:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

กำหนดว่าแผนภูมิมีหัวเรื่องที่มองเห็นหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

กำหนดว่าแผนภูมิมีหัวเรื่องที่มองเห็นหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

คืนค่า หรือ ตั้งค่าหัวเรื่องของแผนภูมิ อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle).

**คืนค่า:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

กำหนดว่าแผนภูมิมีตารางข้อมูลหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

กำหนดว่าแผนภูมิมีคำอธิบายหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

กำหนดว่าแผนภูมิมีคำอธิบายหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

คืนค่า หรือ ตั้งค่าคำอธิบายสำหรับแผนภูมิ อ่านอย่างเดียว [ILegend](../../com.aspose.slides/ilegend).

**คืนค่า:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

คืนค่าตารางข้อมูลของแผนภูมิ อ่านอย่างเดียว [IDataTable](../../com.aspose.slides/idatatable).

**คืนค่า:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

คืนค่า หรือ ตั้งค่าแบบแผนภูมิ อ่าน/เขียน [StyleType](../../com.aspose.slides/styletype).

**คืนค่า:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

คืนค่า หรือ ตั้งค่าแบบแผนภูมิ อ่าน/เขียน [StyleType](../../com.aspose.slides/styletype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

คืนค่า หรือ ตั้งค่าชนิดแผนภูมิ อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**คืนค่า:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

คืนค่า หรือ ตั้งค่าชนิดแผนภูมิ อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

แสดงพื้นที่พล็อตของแผนภูมิ อ่านอย่างเดียว [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**คืนค่า:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

คืนค่าการหมุนแบบ 3 มิติของแผนภูมิ อ่านอย่างเดียว [IRotation3D](../../com.aspose.slides/irotation3d).

**คืนค่า:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของกำแพงหลังของแผนภูมิ 3 มิติ อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**คืนค่า:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของกำแพงด้านของแผนภูมิ 3 มิติ อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**คืนค่า:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

คืนออบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**คืนค่า:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

คืนรูปแบบข้อความของแผนภูมิ คุณสมบัตินี้ไม่สามารถใช้ได้กับประเภทต่อไปนี้: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**คืนค่า:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

คืนธีมที่ใช้ได้สำหรับแผนภูมินี้.

**คืนค่า:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

คืนผู้จัดการธีม อ่านอย่างเดียว [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**คืนค่า:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

ระบุรูปทรงที่วาดบนแผนภูมิ อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

ให้การเข้าถึงแกนของแผนภูมิ อ่านอย่างเดียว [IAxesManager](../../com.aspose.slides/iaxesmanager).

**คืนค่า:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

ระบุว่าพื้นที่แผนภูมิจะมีมุมโค้ง อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

ระบุว่าพื้นที่แผนภูมิจะมีมุมโค้ง อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนแผนภูมิ อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)