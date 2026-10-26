---
title: Chart
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นกราฟิกชาร์ตบนสไลด์
type: docs
url: /th/com.aspose.slides/chart/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IChart](../../com.aspose.slides/ichart)
```
public class Chart extends GraphicalObject implements IChart
```

เป็นกราฟิกชาร์ตบนสไลด์
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [validateChartLayout()](#validateChartLayout--) | คำนวณค่าจริงขององค์ประกอบชาร์ต |
| [getPlotVisibleCellsOnly()](#getPlotVisibleCellsOnly--) | กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นหรือไม่ |
| [setPlotVisibleCellsOnly(boolean value)](#setPlotVisibleCellsOnly-boolean-) | กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นหรือไม่ |
| [getDisplayBlanksAs()](#getDisplayBlanksAs--) | คืนค่า หรือ ตั้งค่าวิธีการแสดงเซลล์ว่างในชาร์ต |
| [setDisplayBlanksAs(int value)](#setDisplayBlanksAs-int-) | คืนค่า หรือ ตั้งค่าวิธีการแสดงเซลล์ว่างในชาร์ต |
| [getChartData()](#getChartData--) | คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เกี่ยวข้องกับชาร์ต |
| [hasTitle()](#hasTitle--) | กำหนดว่าชาร์ตมีชื่อเรื่องที่มองเห็นหรือไม่ |
| [setTitle(boolean value)](#setTitle-boolean-) | กำหนดว่าชาร์ตมีชื่อเรื่องที่มองเห็นหรือไม่ |
| [getChartTitle()](#getChartTitle--) | คืนค่า หรือ ตั้งค่าชื่อเรื่องของชาร์ต |
| [hasDataTable()](#hasDataTable--) | กำหนดว่าชาร์ตมีตารางข้อมูลหรือไม่ |
| [setDataTable(boolean value)](#setDataTable-boolean-) | กำหนดว่าชาร์ตมีตารางข้อมูลหรือไม่ |
| [hasLegend()](#hasLegend--) | กำหนดว่าชาร์ตมี legend หรือไม่ |
| [setLegend(boolean value)](#setLegend-boolean-) | กำหนดว่าชาร์ตมี legend หรือไม่ |
| [getLegend()](#getLegend--) | คืนค่า หรือ ตั้งค่า legend สำหรับชาร์ต |
| [getChartDataTable()](#getChartDataTable--) | คืนตารางข้อมูลของชาร์ต |
| [getStyle()](#getStyle--) | คืนค่า หรือ ตั้งค่าสไตล์ของชาร์ต |
| [setStyle(int value)](#setStyle-int-) | คืนค่า หรือ ตั้งค่าสไตล์ของชาร์ต |
| [getType()](#getType--) | คืนค่า หรือ ตั้งประเภทของชาร์ต |
| [setType(int value)](#setType-int-) | คืนค่า หรือ ตั้งประเภทของชาร์ต |
| [getPlotArea()](#getPlotArea--) | เป็นพื้นที่การวาดของชาร์ต |
| [getRotation3D()](#getRotation3D--) | คืนค่าการหมุน 3D ของชาร์ต |
| [getBackWall()](#getBackWall--) | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของกำแพงหลังของชาร์ต 3D |
| [getSideWall()](#getSideWall--) | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของกำแพงด้านของชาร์ต 3D |
| [getFloor()](#getFloor--) | คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของพื้นของชาร์ต 3D |
| [getTextFormat()](#getTextFormat--) | คืนรูปแบบข้อความของชาร์ต |
| [createThemeEffective()](#createThemeEffective--) | คืนธีมที่มีผลสำหรับชาร์ตนี้ |
| [getThemeManager()](#getThemeManager--) | คืนตัวจัดการธีม |
| [getUserShapes()](#getUserShapes--) | ระบุรูปร่างที่วาดบนชาร์ต |
| [getAxes()](#getAxes--) | ให้เข้าถึงแกนของชาร์ต |
| [getShowDataLabelsOverMaximum()](#getShowDataLabelsOverMaximum--) | ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของชาร์ตหรือไม่ |
| [setShowDataLabelsOverMaximum(boolean value)](#setShowDataLabelsOverMaximum-boolean-) | ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของชาร์ตหรือไม่ |
| [hasRoundedCorners()](#hasRoundedCorners--) | ระบุว่าพื้นที่ชาร์ตควรมีมุมโค้ง |
| [setRoundedCorners(boolean value)](#setRoundedCorners-boolean-) | ระบุว่าพื้นที่ชาร์ตควรมีมุมโค้ง |
| [getChart()](#getChart--) |  |

### validateChartLayout() {#validateChartLayout--}
```
public final void validateChartLayout()
```

คำนวณค่าจริงขององค์ประกอบชาร์ต ค่าจริงรวมถึงตำแหน่งขององค์ประกอบที่ใช้ IActualLayout interface (IActualLayout.ActualX, IActualLayout.ActualY, IActualLayout.ActualWidth, IActualLayout.ActualHeight) และค่าจริงของแกน (IAxis.ActualMaxValue, IAxis.ActualMinValue, IAxis.ActualMajorUnit, IAxis.ActualMinorUnit, IAxis.ActualMajorUnitScale, IAxis.ActualMinorUnitScale)

### getPlotVisibleCellsOnly() {#getPlotVisibleCellsOnly--}
```
public final boolean getPlotVisibleCellsOnly()
```

กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นหรือไม่ False เพื่อแสดงทั้งเซลล์ที่มองเห็นและที่ซ่อน อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setPlotVisibleCellsOnly(boolean value) {#setPlotVisibleCellsOnly-boolean-}
```
public final void setPlotVisibleCellsOnly(boolean value)
```

กำหนดว่าจะแสดงเฉพาะเซลล์ที่มองเห็นหรือไม่ False เพื่อแสดงทั้งเซลล์ที่มองเห็นและที่ซ่อน อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDisplayBlanksAs() {#getDisplayBlanksAs--}
```
public final int getDisplayBlanksAs()
```

คืนค่า หรือ ตั้งค่าวิธีการแสดงเซลล์ว่างในชาร์ต อ่าน/เขียน [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**คืนค่า:**
int
### setDisplayBlanksAs(int value) {#setDisplayBlanksAs-int-}
```
public final void setDisplayBlanksAs(int value)
```

คืนค่า หรือ ตั้งค่าวิธีการแสดงเซลล์ว่างในชาร์ต อ่าน/เขียน [DisplayBlanksAsType](../../com.aspose.slides/displayblanksastype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getChartData() {#getChartData--}
```
public final IChartData getChartData()
```

คืนข้อมูลเกี่ยวกับข้อมูลที่เชื่อมโยงหรือฝังที่เกี่ยวข้องกับชาร์ต อ่านอย่างเดียว [IChartData](../../com.aspose.slides/ichartdata).

**คืนค่า:**
[IChartData](../../com.aspose.slides/ichartdata)
### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

กำหนดว่าชาร์ตมีชื่อเรื่องที่มองเห็นหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

กำหนดว่าชาร์ตมีชื่อเรื่องที่มองเห็นหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChartTitle() {#getChartTitle--}
```
public final IChartTitle getChartTitle()
```

คืนค่า หรือ ตั้งค่าชื่อเรื่องของชาร์ต อ่านอย่างเดียว [IChartTitle](../../com.aspose.slides/icharttitle).

**คืนค่า:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### hasDataTable() {#hasDataTable--}
```
public final boolean hasDataTable()
```

กำหนดว่าชาร์ตมีตารางข้อมูลหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setDataTable(boolean value) {#setDataTable-boolean-}
```
public final void setDataTable(boolean value)
```

กำหนดว่าชาร์ตมีตารางข้อมูลหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasLegend() {#hasLegend--}
```
public final boolean hasLegend()
```

กำหนดว่าชาร์ตมี legend หรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setLegend(boolean value) {#setLegend-boolean-}
```
public final void setLegend(boolean value)
```

กำหนดว่าชาร์ตมี legend หรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLegend() {#getLegend--}
```
public final ILegend getLegend()
```

คืนค่า หรือ ตั้งค่า legend สำหรับชาร์ต อ่านอย่างเดียว [ILegend](../../com.aspose.slides/ilegend).

**คืนค่า:**
[ILegend](../../com.aspose.slides/ilegend)
### getChartDataTable() {#getChartDataTable--}
```
public final IDataTable getChartDataTable()
```

คืนตารางข้อมูลของชาร์ต อ่านอย่างเดียว [IDataTable](../../com.aspose.slides/idatatable).

**คืนค่า:**
[IDataTable](../../com.aspose.slides/idatatable)
### getStyle() {#getStyle--}
```
public final int getStyle()
```

คืนค่า หรือ ตั้งค่าสไตล์ของชาร์ต อ่าน/เขียน [StyleType](../../com.aspose.slides/styletype).

**คืนค่า:**
int
### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```

คืนค่า หรือ ตั้งค่าสไตล์ของชาร์ต อ่าน/เขียน [StyleType](../../com.aspose.slides/styletype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getType() {#getType--}
```
public final int getType()
```

คืนค่า หรือ ตั้งประเภทของชาร์ต อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**คืนค่า:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

คืนค่า หรือ ตั้งประเภทของชาร์ต อ่าน/เขียน [ChartType](../../com.aspose.slides/charttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPlotArea() {#getPlotArea--}
```
public final IChartPlotArea getPlotArea()
```

เป็นพื้นที่การวาดของชาร์ต อ่านอย่างเดียว [IChartPlotArea](../../com.aspose.slides/ichartplotarea).

**คืนค่า:**
[IChartPlotArea](../../com.aspose.slides/ichartplotarea)
### getRotation3D() {#getRotation3D--}
```
public final IRotation3D getRotation3D()
```

คืนค่าการหมุน 3D ของชาร์ต อ่านอย่างเดียว [IRotation3D](../../com.aspose.slides/irotation3d).

**คืนค่า:**
[IRotation3D](../../com.aspose.slides/irotation3d)
### getBackWall() {#getBackWall--}
```
public final IChartWall getBackWall()
```

คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของกำแพงหลังของชาร์ต 3D อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**คืนค่า:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getSideWall() {#getSideWall--}
```
public final IChartWall getSideWall()
```

คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของกำแพงด้านของชาร์ต 3D อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**คืนค่า:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getFloor() {#getFloor--}
```
public final IChartWall getFloor()
```

คืนอ็อบเจ็กต์ที่ให้เปลี่ยนรูปแบบของพื้นของชาร์ต 3D อ่านอย่างเดียว [IChartWall](../../com.aspose.slides/ichartwall).

**คืนค่า:**
[IChartWall](../../com.aspose.slides/ichartwall)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

คืนรูปแบบข้อความของชาร์ต คุณสมบัตินี้ไม่สามารถใช้ได้กับประเภทต่อไปนี้: [ChartType.Treemap](../../com.aspose.slides/charttype\#Treemap), [ChartType.Sunburst](../../com.aspose.slides/charttype\#Sunburst), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel),[ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker). อ่านอย่างเดียว [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**คืนค่า:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

คืนธีมที่มีผลสำหรับชาร์ตนี้.

**คืนค่า:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

คืนตัวจัดการธีม อ่านอย่างเดียว [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**คืนค่า:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getUserShapes() {#getUserShapes--}
```
public final IGroupShape getUserShapes()
```

ระบุรูปร่างที่วาดบนชาร์ต อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getAxes() {#getAxes--}
```
public final IAxesManager getAxes()
```

ให้เข้าถึงแกนของชาร์ต อ่านอย่างเดียว [IAxesManager](../../com.aspose.slides/iaxesmanager).

**คืนค่า:**
[IAxesManager](../../com.aspose.slides/iaxesmanager)
### getShowDataLabelsOverMaximum() {#getShowDataLabelsOverMaximum--}
```
public final boolean getShowDataLabelsOverMaximum()
```

ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของชาร์ตหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setShowDataLabelsOverMaximum(boolean value) {#setShowDataLabelsOverMaximum-boolean-}
```
public final void setShowDataLabelsOverMaximum(boolean value)
```

ระบุว่าจะแสดงป้ายข้อมูลเหนือค่าสูงสุดของชาร์ตหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasRoundedCorners() {#hasRoundedCorners--}
```
public final boolean hasRoundedCorners()
```

ระบุว่าพื้นที่ชาร์ตควรมีมุมโค้ง อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setRoundedCorners(boolean value) {#setRoundedCorners-boolean-}
```
public final void setRoundedCorners(boolean value)
```

ระบุว่าพื้นที่ชาร์ตควรมีมุมโค้ง อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนชาร์ต อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)