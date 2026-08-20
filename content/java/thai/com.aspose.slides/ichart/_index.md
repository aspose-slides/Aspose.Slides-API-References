---
title: IChart
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของแผนภูมิกราฟิกบนสไลด์
type: docs
url: /th/com.aspose.slides/ichart/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

เป็นตัวแทนของแผนภูมิกราฟิกบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | กำหนดว่ามีการพล็อตเฉพาะเซลล์ที่มองเห็นเท่านั้นหรือไม่ |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | กำหนดว่ามีการพล็อตเฉพาะเซลล์ที่มองเห็นเท่านั้นหรือไม่ |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | คืนค่า หรือกำหนดวิธีการพล็อตเซลล์ว่างในแผนภูมิ |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | คืนค่า หรือกำหนดวิธีการพล็อตเซลล์ว่างในแผนภูมิ |
| [getChartData()](#getChartData--) | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เกี่ยวข้องกับแผนภูมิ |
| [hasTitle()](#hasTitle--) | กำหนดว่ามีชื่อแผนภูมิที่มองเห็นได้หรือไม่ |
| [setTitle(boolean value)](#setTitle-boolean-) | กำหนดว่ามีชื่อแผนภูมิที่มองเห็นได้หรือไม่ |
| [getChartTitle()](#getChartTitle--) | คืนค่า หรือกำหนดชื่อแผนภูมิ อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle) |
| [hasDataTable()](#hasDataTable--) | กำหนดว่ามีตารางข้อมูลในแผนภูมิหรือไม่ |
| [setDataTable(boolean value)](#setDataTable-boolean-) | กำหนดว่ามีตารางข้อมูลในแผนภูมิหรือไม่ |
| [hasLegend()](#hasLegend--) | กำหนดว่ามีคำอธิบาย (legend) ในแผนภูมิหรือไม่ |
| [setLegend(boolean value)](#setLegend-boolean-) | กำหนดว่ามีคำอธิบาย (legend) ในแผนภูมิหรือไม่ |
| [getLegend()](#getLegend--) | คืนค่า หรือกำหนดคำอธิบาย (legend) สำหรับแผนภูมิ |
| [getChartDataTable()](#getChartDataTable--) | คืนค่าตารางข้อมูลของแผนภูมิ |
| [getStyle()](#getStyle--) | คืนค่า หรือกำหนดรูปแบบของแผนภูมิ |
| [setStyle(int value)](#setStyle-int-) | คืนค่า หรือกำหนดรูปแบบของแผนภูมิ |
| [getType()](#getType--) | คืนค่า หรือกำหนดประเภทของแผนภูมิ |
| [setType(int value)](#setType-int-) | คืนค่า หรือกำหนดประเภทของแผนภูมิ |
| [getPlotArea()](#getPlotArea--) | แสดงพื้นที่พล็อตของแผนภูมิ |
| [getRotation3D()](#getRotation3D--) | คืนค่าการหมุน 3 มิติของแผนภูมิ |
| [getBackWall()](#getBackWall--) | คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของกำแพงด้านหลังของแผนภูมิ 3 มิติ |
| [getSideWall()](#getSideWall--) | คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของกำแพงด้านข้างของแผนภูมิ 3 มิติ |
| [getFloor()](#getFloor--) | คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ |
| [getUserShapes()](#getUserShapes--) | ระบุรูปร่างที่วาดอยู่บนแผนภูมิ |
| [getAxes()](#getAxes--) | ให้การเข้าถึงแกนของแผนภูมิ |
| [validateChartLayout()](#validateChartLayout--) | คำนวณค่าจริงขององค์ประกอบในแผนภูมิ |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | ระบุตำแหน่งที่จะแสดงป้ายข้อมูลเมื่อเกินค่าสูงสุดของแผนภูมิ |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | ระบุตำแหน่งที่จะแสดงป้ายข้อมูลเมื่อเกินค่าสูงสุดของแผนภูมิ |
| [hasRoundedCorners()](#hasRoundedCorners--) | ระบุให้พื้นที่แผนภูมิมีมุมโค้ง |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | ระบุให้พื้นที่แผนภูมิมีมุมโค้ง |

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

กำหนดว่ามีการพล็อตเฉพาะเซลล์ที่มองเห็นเท่านั้นหรือไม่. False เพื่อพล็อตทั้งเซลล์ที่มองเห็นและที่ซ่อน. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

กำหนดว่ามีการพล็อตเฉพาะเซลล์ที่มองเห็นเท่านั้นหรือไม่. False เพื่อพล็อตทั้งเซลล์ที่มองเห็นและที่ซ่อน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

คืนค่า หรือกำหนดวิธีการพล็อตเซลล์ว่างในแผนภูมิ. อ่าน/เขียน [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**ผลลัพธ์:**
int

### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

คืนค่า หรือกำหนดวิธีการพล็อตเซลล์ว่างในแผนภูมิ. อ่าน/เขียน [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เกี่ยวข้องกับแผนภูมิ. อ่านอย่างเดียว [IChartData](../../com.aspose.slides/ichartdata).

**ผลลัพธ์:**
[IChartData](../../com.aspose.slides/ichartdata)

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

กำหนดว่ามีชื่อแผนภูมิที่มองเห็นได้หรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

กำหนดว่ามีชื่อแผนภูมิที่มองเห็นได้หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

คืนค่า หรือกำหนดชื่อแผนภูมิ อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle).

**ผลลัพธ์:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

กำหนดว่ามีตารางข้อมูลในแผนภูมิหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

กำหนดว่ามีตารางข้อมูลในแผนภูมิหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

กำหนดว่ามีคำอธิบาย (legend) ในแผนภูมิหรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

กำหนดว่ามีคำอธิบาย (legend) ในแผนภูมิหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

คืนค่า หรือกำหนดคำอธิบาย (legend) สำหรับแผนภูมิ. อ่านอย่างเดียว [ILegend](../../com.aspose.slides/ilegend).

**ผลลัพธ์:**
[ILegend](../../com.aspose.slides/ilegend)

### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

คืนค่าตารางข้อมูลของแผนภูมิ. อ่านอย่างเดียว [IDataTable](../../com.aspose.slides/idatatable).

**ผลลัพธ์:**
[IDataTable](../../com.aspose.slides/idatatable)

### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

คืนค่า หรือกำหนดรูปแบบของแผนภูมิ. อ่าน/เขียน [StyleType](../../com.aspose.slides/styletype).

**ผลลัพธ์:**
int

### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

คืนค่า หรือกำหนดรูปแบบของแผนภูมิ. อ่าน/เขียน [StyleType](../../com.aspose.slides/styletype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public abstract int getType()
```

คืนค่า หรือกำหนดประเภทของแผนภูมิ. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**ผลลัพธ์:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

คืนค่า หรือกำหนดประเภทของแผนภูมิ. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

แสดงพื้นที่พล็อตของแผนภูมิ. อ่านอย่างเดียว [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**ผลลัพธ์:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)

### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

คืนค่าการหมุน 3 มิติของแผนภูมิ. อ่านอย่างเดียว [IRotation3D](../../com.aspose.slides/irotation3d).

**ผลลัพธ์:**
[IRotation3D](../../com.aspose.slides/irotation3d)

### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของกำแพงด้านหลังของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**ผลลัพธ์:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของกำแพงด้านข้างของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**ผลลัพธ์:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

คืนอ็อบเจ็กต์ที่อนุญาตให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**ผลลัพธ์:**
[IChartWall](../../com.aspose.slides/ichartwall)

### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

ระบุรูปร่างที่วาดอยู่บนแผนภูมิ. อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

**ผลลัพธ์:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

ให้การเข้าถึงแกนของแผนภูมิ. อ่านอย่างเดียว [IAxesManager](../../com.aspose.slides/iaxesmanager).

**ผลลัพธ์:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)

### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

คำนวณค่าจริงขององค์ประกอบในแผนภูมิ. ค่าจริงรวมตำแหน่งขององค์ประกอบที่ทำการ Implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

ระบุตำแหน่งที่จะแสดงป้ายข้อมูลเมื่อเกินค่าสูงสุดของแผนภูมิ. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

ระบุตำแหน่งที่จะแสดงป้ายข้อมูลเมื่อเกินค่าสูงสุดของแผนภูมิ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

ระบุให้พื้นที่แผนภูมิมีมุมโค้ง. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

ระบุให้พื้นที่แผนภูมิมีมุมโค้ง. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |