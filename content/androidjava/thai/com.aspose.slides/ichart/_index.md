---
title: IChart
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นการแสดงแผนภูมิกราฟิกบนสไลด์.
type: docs
url: /th/com.aspose.slides/ichart/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface IChart extends IGraphicalObject, IFormattedTextContainer, IOverrideThemeable
```

เป็นการแสดงแผนภูมิกราฟิกบนสไลด์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นหรือไม่ |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นหรือไม่ |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | คืนค่าหรือกำหนดวิธีการแสดงเซลล์ว่างบนแผนภูมิ |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | คืนค่าหรือกำหนดวิธีการแสดงเซลล์ว่างบนแผนภูมิ |
| [getChartData()](#getChartData--) | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังอยู่ที่เกี่ยวข้องกับแผนภูมิ |
| [hasTitle()](#hasTitle--) | กำหนดว่าภาพแผนภูมิมีชื่อที่มองเห็นหรือไม่ |
| [setTitle(boolean value)](#setTitle-boolean-) | กำหนดว่าภาพแผนภูมิมีชื่อที่มองเห็นหรือไม่ |
| [getChartTitle()](#getChartTitle--) | คืนค่า หรือกำหนดชื่อแผนภูมิ อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle) |
| [hasDataTable()](#hasDataTable--) | กำหนดว่าภาพแผนภูมิมีตารางข้อมูลหรือไม่ |
| [setDataTable(boolean value)](#setDataTable-boolean-) | กำหนดว่าภาพแผนภูมิมีตารางข้อมูลหรือไม่ |
| [hasLegend()](#hasLegend--) | กำหนดว่าภาพแผนภูมิมีคำอธิบายหรือไม่ |
| [setLegend(boolean value)](#setLegend-boolean-) | กำหนดว่าภาพแผนภูมิมีคำอธิบายหรือไม่ |
| [getLegend()](#getLegend--) | คืนค่า หรือกำหนดคำอธิบายสำหรับแผนภูมิ |
| [getChartDataTable()](#getChartDataTable--) | คืนตารางข้อมูลของแผนภูมิ |
| [getStyle()](#getStyle--) | คืนค่า หรือกำหนดรูปแบบแผนภูมิ |
| [setStyle(int value)](#setStyle-int-) | คืนค่า หรือกำหนดรูปแบบแผนภูมิ |
| [getType()](#getType--) | คืนค่า หรือกำหนดประเภทของแผนภูมิ |
| [setType(int value)](#setType-int-) | คืนค่า หรือกำหนดประเภทของแผนภูมิ |
| [getPlotArea()](#getPlotArea--) | แสดงพื้นที่พล็อตของแผนภูมิ |
| [getRotation3D()](#getRotation3D--) | คืนค่าการหมุน 3 มิติของแผนภูมิ |
| [getBackWall()](#getBackWall--) | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของผนังด้านหลังของแผนภูมิ 3 มิติ |
| [getSideWall()](#getSideWall--) | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของผนังด้านข้างของแผนภูมิ 3 มิติ |
| [getFloor()](#getFloor--) | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ |
| [getUserShapes()](#getUserShapes--) | ระบุรูปร่างที่วาดบนแผนภูมิ |
| [getAxes()](#getAxes--) | ให้การเข้าถึงแกนของแผนภูมิ |
| [validateChartLayout()](#validateChartLayout--) | คำนวณค่าจริงขององค์ประกอบแผนภูมิ |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | ระบุว่าป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิจะต้องแสดง |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | ระบุว่าป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิจะต้องแสดง |
| [hasRoundedCorners()](#hasRoundedCorners--) | ระบุว่าพื้นที่แผนภูมิมีมุมโค้ง |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | ระบุว่าพื้นที่แผนภูมิมีมุมโค้ง |
### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public abstract boolean getPlotVisibleCellsOnly()
```

กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นหรือไม่. False เพื่อแสดงทั้งเซลล์ที่มองเห็นและที่ซ่อนอยู่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public abstract void setPlotVisibleCellsOnly(boolean value)
```

กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นหรือไม่. False เพื่อแสดงทั้งเซลล์ที่มองเห็นและที่ซ่อนอยู่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public abstract int getDisplayBlanksAs()
```

คืนค่า หรือกำหนดวิธีการแสดงเซลล์ว่างบนแผนภูมิ. อ่าน/เขียน [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**ส่งคืน:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public abstract void setDisplayBlanksAs(int value)
```

คืนค่า หรือกำหนดวิธีการแสดงเซลล์ว่างบนแผนภูมิ. อ่าน/เขียน [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getChartData() {#getChartData--}
```
public abstract IChartData getChartData()
```

คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังอยู่ที่เกี่ยวข้องกับแผนภูมิ. อ่านอย่างเดียว [IChartData](../../com.aspose.slides/ichartdata).

**ส่งคืน:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

กำหนดว่าภาพแผนภูมิมีชื่อที่มองเห็นหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

กำหนดว่าภาพแผนภูมิมีชื่อที่มองเห็นหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getChartTitle() {#getChartTitle--}
```
public abstract IChartTitle getChartTitle()
```

คืนค่า หรือกำหนดชื่อแผนภูมิ อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle).

**ส่งคืน:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public abstract boolean hasDataTable()
```

กำหนดว่าภาพแผนภูมิมีตารางข้อมูลหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public abstract void setDataTable(boolean value)
```

กำหนดว่าภาพแผนภูมิมีตารางข้อมูลหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### hasLegend() {#hasLegend--}
```
public abstract boolean hasLegend()
```

กำหนดว่าภาพแผนภูมิมีคำอธิบายหรือไม่. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public abstract void setLegend(boolean value)
```

กำหนดว่าภาพแผนภูมิมีคำอธิบายหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getLegend() {#getLegend--}
```
public abstract ILegend getLegend()
```

คืนค่า หรือกำหนดคำอธิบายสำหรับแผนภูมิ. อ่านอย่างเดียว [ILegend](../../com.aspose.slides/ilegend).

**ส่งคืน:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public abstract IDataTable getChartDataTable()
```

คืนตารางข้อมูลของแผนภูมิ. อ่านอย่างเดียว [IDataTable](../../com.aspose.slides/idatatable).

**ส่งคืน:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public abstract int getStyle()
```

คืนค่า หรือกำหนดรูปแบบแผนภูมิ. อ่าน/เขียน [StyleType](../../com.aspose.slides/styletype).

**ส่งคืน:**
int
### setStyle(int value) {#setStyle-int-}
```
public abstract void setStyle(int value)
```

คืนค่า หรือกำหนดรูปแบบแผนภูมิ. อ่าน/เขียน [StyleType](../../com.aspose.slides/styletype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```

คืนค่า หรือกำหนดประเภทของแผนภูมิ. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**ส่งคืน:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

คืนค่า หรือกำหนดประเภทของแผนภูมิ. อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getPlotArea() {#getPlotArea--}
```
public abstract IChartPlotArea getPlotArea()
```

แสดงพื้นที่พล็อตของแผนภูมิ. อ่านอย่างเดียว [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**ส่งคืน:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public abstract IRotation3D getRotation3D()
```

คืนค่าการหมุน 3 มิติของแผนภูมิ. อ่านอย่างเดียว [IRotation3D](../../com.aspose.slides/irotation3d).

**ส่งคืน:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public abstract IChartWall getBackWall()
```

คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของผนังด้านหลังของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**ส่งคืน:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public abstract IChartWall getSideWall()
```

คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของผนังด้านข้างของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**ส่งคืน:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public abstract IChartWall getFloor()
```

คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของพื้นของแผนภูมิ 3 มิติ. อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**ส่งคืน:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getUserShapes() {#getUserShapes--}
```
public abstract IGroupShape getUserShapes()
```

ระบุรูปร่างที่วาดบนแผนภูมิ. อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

**ส่งคืน:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public abstract IAxesManager getAxes()
```

ให้การเข้าถึงแกนของแผนภูมิ. อ่านอย่างเดียว [IAxesManager](../../com.aspose.slides/iaxesmanager).

**ส่งคืน:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### validateChartLayout() {#validateChartLayout--}
```
public abstract void validateChartLayout()
```

คำนวณค่าจริงขององค์ประกอบแผนภูมิ. ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ทำการ implement IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public abstract boolean getShowDataLabelsOverMaximum()
```

ระบุว่าป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิจะต้องแสดง. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public abstract void setShowDataLabelsOverMaximum(boolean value)
```

ระบุว่าป้ายข้อมูลเหนือค่าสูงสุดของแผนภูมิจะต้องแสดง. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### hasRoundedCorners() {#hasRoundedCorners--}
```
public abstract boolean hasRoundedCorners()
```

ระบุว่าพื้นที่แผนภูมิมีมุมโค้ง. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public abstract void setRoundedCorners(boolean value)
```

ระบุว่าพื้นที่แผนภูมิมีมุมโค้ง. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |