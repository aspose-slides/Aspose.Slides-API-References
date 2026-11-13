---
title: ChartDataPoint
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงจุดข้อมูลของซีรีส์.
type: docs
url: /th/com.aspose.slides/chartdatapoint/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IChartDataPoint](../../com.aspose.slides/ichartdatapoint), com.aspose.slides.IDOMObject
```
public class ChartDataPoint implements IChartDataPoint, IDOMObject
```

แสดงจุดข้อมูลของซีรีส์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXValue()](#getXValue--) | XValue. |
| [getYValue()](#getYValue--) | YValue. |
| [getBubbleSize()](#getBubbleSize--) | BubbleSize. |
| [getValue()](#getValue--) | Value. |
| [getSizeValue()](#getSizeValue--) | คืนค่าขนาดของจุดข้อมูลแผนภูมิ. |
| [getColorValue()](#getColorValue--) | คืนค่ารหัสสีของจุดข้อมูลแผนภูมิ. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | แสดงค่าคล่องแท่งข้อผิดพลาดของซีรีส์ในกรณีที่ประเภทค่าเป็น Custom. |
| [getLabel()](#getLabel--) | Label. |
| [isBubble3D()](#isBubble3D--) | ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. |
| [getExplosion()](#getExplosion--) | ระบุปริมาณที่จุดข้อมูลจะถูกย้ายจากศูนย์กลางของกราฟวงกลม. |
| [setExplosion(int value)](#setExplosion-int-) | ระบุปริมาณที่จุดข้อมูลจะถูกย้ายจากศูนย์กลางของกราฟวงกลม. |
| [getFormat()](#getFormat--) | แสดงคุณสมบัติการจัดรูปแบบ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | แสดงคุณสมบัติการจัดรูปแบบ. |
| [getMarker()](#getMarker--) | ระบุตัวบ่งชี้ข้อมูล. |
| [getSetAsTotal()](#getSetAsTotal--) | ตั้งค่าจุดข้อมูลเป็นยอดรวม. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | ตั้งค่าจุดข้อมูลเป็นยอดรวม. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | คุณสมบัติของรายการตำนานที่สอดคล้องกันในกรณีของประเภทแผนภูมิจากรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [remove()](#remove--) | ลบ DataPoint จากชุดข้อมูลแผนภูมิ. |
| [getDataPointLevels()](#getDataPointLevels--) | คืนค่าตัวคอนเทนเนอร์ของระดับจุดข้อมูล. |
| [getIndex()](#getIndex--) |    |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | คืนค่าสีอัตโนมัติของจุดข้อมูลตามดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าจุดข้อมูลจะสลับสีของมันหากค่าเป็นลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าจุดข้อมูลจะสลับสีของมันหากค่าเป็นลบ. |
| [getCachedValue()](#getCachedValue--) | ดึงค่าที่เก็บไว้ของจุดข้อมูลแผนภูมิ. |
| [getCachedXValue()](#getCachedXValue--) | ดึงค่าที่เก็บไว้ของ X ของจุดข้อมูลแผนภูมิ. |
| [getCachedYValue()](#getCachedYValue--) | ดึงค่าที่เก็บไว้ของ Y ของจุดข้อมูลแผนภูมิ. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | ดึงค่าขนาดฟองที่เก็บไว้ของจุดข้อมูลแผนภูมิ. |
| [getActualX()](#getActualX--) | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualY()](#getActualY--) | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualWidth()](#getActualWidth--) | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. |
| [getActualHeight()](#getActualHeight--) | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. |

### getXValue() {#getXValue--}
```
public final IStringOrDoubleChartValue getXValue()
```

XValue. อ่านอย่างเดียว [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**คืนค่า:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)

### getYValue() {#getYValue--}
```
public final IDoubleChartValue getYValue()
```

YValue. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getBubbleSize() {#getBubbleSize--}
```
public final IDoubleChartValue getBubbleSize()
```

BubbleSize. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getValue() {#getValue--}
```
public final IDoubleChartValue getValue()
```

Value. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getSizeValue() {#getSizeValue--}
```
public final IDoubleChartValue getSizeValue()
```

คืนค่าขนาดของจุดข้อมูลแผนภูมิ ใช้กับแผนภูมิ Treemap และ Sunburst. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getColorValue() {#getColorValue--}
```
public final IDoubleChartValue getColorValue()
```

คืนค่ารหัสสีของจุดข้อมูลแผนภูมิ ใช้กับแผนภูมิ Map. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)

### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public final IErrorBarsCustomValues getErrorBarsCustomValues()
```

แสดงค่าคล่องแท่งข้อผิดพลาดของซีรีส์ในกรณีที่ประเภทค่าเป็น Custom. อ่านอย่างเดียว [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**คืนค่า:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)

### getLabel() {#getLabel--}
```
public final IDataLabel getLabel()
```

Label. อ่านอย่างเดียว [IDataLabel](../../com.aspose.slides/idatalabel).

**คืนค่า:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### isBubble3D() {#isBubble3D--}
```
public final boolean isBubble3D()
```

ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public final void setBubble3D(boolean value)
```

ระบุว่าฟองมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

ระบุปริมาณที่จุดข้อมูลจะถูกย้ายจากศูนย์กลางของกราฟวงกลม. อ่าน/เขียน int.

**คืนค่า:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

ระบุปริมาณที่จุดข้อมูลจะถูกย้ายจากศูนย์กลางของกราฟวงกลม. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

แสดงคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

แสดงคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

ระบุตัวบ่งชี้ข้อมูล. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**คืนค่า:**
[IMarker](../../com.aspose.slides/imarker)

### getSetAsTotal() {#getSetAsTotal--}
```
public final boolean getSetAsTotal()
```

ตั้งค่าจุดข้อมูลเป็นยอดรวม. ใช้กับประเภทซีรีส์ Waterfall เท่านั้น.

**คืนค่า:**
boolean

### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public final void setSetAsTotal(boolean value)
```

ตั้งค่าจุดข้อมูลเป็นยอดรวม. ใช้กับประเภทซีรีส์ Waterfall เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

คุณสมบัติของรายการตำนานที่สอดคล้องกันในกรณีของประเภทแผนภูมิจากรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### remove() {#remove--}
```
public final void remove()
```

ลบ DataPoint จากชุดข้อมูลแผนภูมิ.

### getDataPointLevels() {#getDataPointLevels--}
```
public final IChartDataPointLevelsManager getDataPointLevels()
```

คืนค่าตัวคอนเทนเนอร์ของระดับจุดข้อมูล. ใช้กับซีรีส์ Treeamp และ Sunburst. การจัดทำหมายเลขระดับจุดข้อมูลเริ่มจากศูนย์.

**คืนค่า:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)

### getIndex() {#getIndex--}
```
public final long getIndex()
```

**คืนค่า:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public final Color getAutomaticDataPointColor()
```

คืนค่าสีอัตโนมัติของจุดข้อมูลตามดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. สีนี้จะถูกใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined.

**คืนค่า:**
java.awt.Color

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

ระบุว่าจุดข้อมูลจะสลับสีของมันหากค่าเป็นลบ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

ระบุว่าจุดข้อมูลจะสลับสีของมันหากค่าเป็นลบ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCachedValue() {#getCachedValue--}
```
public final ICachedChartValue getCachedValue()
```

ดึงค่าที่เก็บไว้ของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // พิมพ์ค่าที่แคชทั้งหมดของซีรีส์แผนภูมิ
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedXValue() {#getCachedXValue--}
```
public final ICachedChartValue getCachedXValue()
```

ดึงค่าที่เก็บไว้ของ X ของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // พิมพ์ค่าที่แคช X ทั้งหมดของซีรีส์แผนภูมิ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedXValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedYValue() {#getCachedYValue--}
```
public final ICachedChartValue getCachedYValue()
```

ดึงค่าที่เก็บไว้ของ Y ของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // พิมพ์ค่าที่แคช Y ทั้งหมดของซีรีส์แผนภูมิ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedYValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public final ICachedChartValue getCachedBubbleSize()
```

ดึงค่าขนาดฟองที่เก็บไว้ของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // พิมพ์ค่าขนาดฟองที่แคชทั้งหมดของซีรีส์แผนภูมิ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)

### getActualX() {#getActualX--}
```
public final float getActualX()
```

ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float

### getActualY() {#getActualY--}
```
public final float getActualY()
```

ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float

### getActualWidth() {#getActualWidth--}
```
public final float getActualWidth()
```

ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float

### getActualHeight() {#getActualHeight--}
```
public final float getActualHeight()
```

ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าจริง. อ่าน float.

**คืนค่า:**
float