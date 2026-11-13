---
title: IChartDataPoint
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: เป็นตัวแทนของจุดข้อมูลของซีรีส์.
type: docs
url: /th/com.aspose.slides/ichartdatapoint/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartDataPoint extends IActualLayout
```

เป็นตัวแทนของจุดข้อมูลของซีรีส์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXValue()](#getXValue--) | ดึงค่าพิกัด x ของจุดข้อมูลแผนภูมิ. |
| [getYValue()](#getYValue--) | ดึงค่าพิกัด y ของจุดข้อมูลแผนภูมิ. |
| [getBubbleSize()](#getBubbleSize--) | ดึงค่าขนาดบับเบิลของจุดข้อมูลแผนภูมิ. |
| [getValue()](#getValue--) | ดึงค่าของจุดข้อมูลแผนภูมิ. |
| [getCachedXValue()](#getCachedXValue--) | ดึงค่าพิกัด X ที่แคชของจุดข้อมูลแผนภูมิ. |
| [getCachedYValue()](#getCachedYValue--) | ดึงค่าพิกัด Y ที่แคชของจุดข้อมูลแผนภูมิ. |
| [getCachedValue()](#getCachedValue--) | ดึงค่าที่แคชของจุดข้อมูลแผนภูมิ. |
| [getCachedBubbleSize()](#getCachedBubbleSize--) | ดึงค่าขนาดบับเบิลที่แคชของจุดข้อมูลแผนภูมิ. |
| [getSizeValue()](#getSizeValue--) | ดึงค่าขนาดของจุดข้อมูลแผนภูมิ. |
| [getColorValue()](#getColorValue--) | ดึงค่าสีของจุดข้อมูลแผนภูมิ. |
| [getErrorBarsCustomValues()](#getErrorBarsCustomValues--) | เป็นตัวแทนของค่าขอบความผิดพลาดของซีรีส์ในกรณีที่ประเภทค่าคือ Custom. |
| [getLabel()](#getLabel--) | เป็นตัวแทนของป้ายของจุดข้อมูลแผนภูมิ. |
| [isBubble3D()](#isBubble3D--) | ระบุว่าบับเบิลมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. |
| [setBubble3D(boolean value)](#setBubble3D-boolean-) | ระบุว่าบับเบิลมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. |
| [getExplosion()](#getExplosion--) | ระบุจำนวนที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. |
| [setExplosion(int value)](#setExplosion-int-) | ระบุจำนวนที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. |
| [getFormat()](#getFormat--) | เป็นตัวแทนของคุณสมบัติการจัดรูปแบบ. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | เป็นตัวแทนของคุณสมบัติการจัดรูปแบบ. |
| [getMarker()](#getMarker--) | ระบุตัวบ่งชี้ข้อมูล. |
| [remove()](#remove--) | ลบ DataPoint ออกจากซีรีส์ของแผนภูมิ. |
| [getAutomaticDataPointColor()](#getAutomaticDataPointColor--) | ส่งคืนสีอัตโนมัติของจุดข้อมูลโดยอิงจากดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | คุณสมบัติของรายการสัญลักษณ์ที่สอดคล้องกันในกรณีที่ประเภทแผนภูมิอยู่ในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. |
| [getSetAsTotal()](#getSetAsTotal--) | ตั้งค่าจุดข้อมูลเป็นยอดรวม. |
| [setSetAsTotal(boolean value)](#setSetAsTotal-boolean-) | ตั้งค่าจุดข้อมูลเป็นยอดรวม. |
| [getInvertIfNegative()](#getInvertIfNegative--) | ระบุว่าจุดข้อมูลจะสลับสีของมันหากค่าติดลบ. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | ระบุว่าจุดข้อมูลจะสลับสีของมันหากค่าติดลบ. |
| [getDataPointLevels()](#getDataPointLevels--) | ส่งคืนคอนเทนเนอร์ของระดับจุดข้อมูล. |
| [getIndex()](#getIndex--) | กำหนดว่าจุดข้อมูลนี้ใช้กับคอลเลกชันลูกของพาเรนต์ตัวใด. |

### getXValue() {#getXValue--}
```
public abstract IStringOrDoubleChartValue getXValue()
```


ดึงค่าพิกัด x ของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue).

**คืนค่า:**
[IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
### getYValue() {#getYValue--}
```
public abstract IDoubleChartValue getYValue()
```


ดึงค่าพิกัด y ของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getBubbleSize() {#getBubbleSize--}
```
public abstract IDoubleChartValue getBubbleSize()
```


ดึงค่าขนาดบับเบิลของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getValue() {#getValue--}
```
public abstract IDoubleChartValue getValue()
```


ดึงค่าของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getCachedXValue() {#getCachedXValue--}
```
public abstract ICachedChartValue getCachedXValue()
```


ดึงค่าพิกัด X ที่แคชของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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
public abstract ICachedChartValue getCachedYValue()
```


ดึงค่าพิกัด Y ที่แคชของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

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
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


ดึงค่าที่แคชของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // พิมพ์ค่าที่แคชทั้งหมดของซีรีส์แผนภูมิ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedValue().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getCachedBubbleSize() {#getCachedBubbleSize--}
```
public abstract ICachedChartValue getCachedBubbleSize()
```


ดึงค่าขนาดบับเบิลที่แคชของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for(IChartSeries series : chart.getChartData().getSeries())
>      {
>          // พิมพ์ค่าขนาดบับเบิลที่แคชทั้งหมดของซีรีส์แผนภูมิ.
>          for (IChartDataPoint point : series.getDataPoints())
>              System.out.println(point.getCachedBubbleSize().toDouble());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getSizeValue() {#getSizeValue--}
```
public abstract IDoubleChartValue getSizeValue()
```


ดึงค่าขนาดของจุดข้อมูลแผนภูมิ. ใช้กับแผนภูมิ Treemap และ Sunburst. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getColorValue() {#getColorValue--}
```
public abstract IDoubleChartValue getColorValue()
```


ดึงค่าสีของจุดข้อมูลแผนภูมิ. ใช้กับแผนภูมิ Map. อ่านอย่างเดียว [IDoubleChartValue](../../com.aspose.slides/idoublechartvalue).

**คืนค่า:**
[IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
### getErrorBarsCustomValues() {#getErrorBarsCustomValues--}
```
public abstract IErrorBarsCustomValues getErrorBarsCustomValues()
```


เป็นตัวแทนของค่าขอบความผิดพลาดของซีรีส์ในกรณีที่ประเภทค่าคือ Custom. อ่านอย่างเดียว [IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues).

**คืนค่า:**
[IErrorBarsCustomValues](../../com.aspose.slides/ierrorbarscustomvalues)
### getLabel() {#getLabel--}
```
public abstract IDataLabel getLabel()
```


เป็นตัวแทนของป้ายของจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IDataLabel](../../com.aspose.slides/idatalabel).

**คืนค่า:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### isBubble3D() {#isBubble3D--}
```
public abstract boolean isBubble3D()
```


ระบุว่าบับเบิลมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setBubble3D(boolean value) {#setBubble3D-boolean-}
```
public abstract void setBubble3D(boolean value)
```


ระบุว่าบับเบิลมีเอฟเฟกต์ 3 มิติที่ใช้กับพวกมัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```


ระบุจำนวนที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**คืนค่า:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```


ระบุจำนวนที่จุดข้อมูลจะถูกย้ายออกจากศูนย์กลางของพาย. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


เป็นตัวแทนของคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```


เป็นตัวแทนของคุณสมบัติการจัดรูปแบบ. อ่าน/เขียน [IFormat](../../com.aspose.slides/iformat).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```


ระบุตัวบ่งชี้ข้อมูล. อ่านอย่างเดียว [IMarker](../../com.aspose.slides/imarker).

**คืนค่า:**
[IMarker](../../com.aspose.slides/imarker)
### remove() {#remove--}
```
public abstract void remove()
```


ลบ DataPoint ออกจากซีรีส์ของแผนภูมิ.

### getAutomaticDataPointColor() {#getAutomaticDataPointColor--}
```
public abstract Color getAutomaticDataPointColor()
```


ส่งคืนสีอัตโนมัติของจุดข้อมูลโดยอิงจากดัชนีซีรีส์, ดัชนีจุดข้อมูล, คุณสมบัติ ParentSeriesGroup.IsColorVaried และสไตล์แผนภูมิ. สีนี้จะใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined.

**คืนค่า:**
java.awt.Color - Automatic color of data point java.awt.Color
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```


คุณสมบัติของรายการสัญลักษณ์ที่สอดคล้องกันในกรณีที่ประเภทแผนภูมิอยู่ในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie. อ่านอย่างเดียว [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getSetAsTotal() {#getSetAsTotal--}
```
public abstract boolean getSetAsTotal()
```


ตั้งค่าจุดข้อมูลเป็นยอดรวม. ใช้ได้เฉพาะประเภทซีรีส์ Waterfall.

**คืนค่า:**
boolean
### setSetAsTotal(boolean value) {#setSetAsTotal-boolean-}
```
public abstract void setSetAsTotal(boolean value)
```


ตั้งค่าจุดข้อมูลเป็นยอดรวม. ใช้ได้เฉพาะประเภทซีรีส์ Waterfall.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```


ระบุว่าจุดข้อมูลจะสลับสีของมันหากค่าติดลบ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```


ระบุว่าจุดข้อมูลจะสลับสีของมันหากค่าติดลบ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getDataPointLevels() {#getDataPointLevels--}
```
public abstract IChartDataPointLevelsManager getDataPointLevels()
```


ส่งคืนคอนเทนเนอร์ของระดับจุดข้อมูล. ใช้ได้กับซีรีส์ Treeamp และ Sunburst. การจัดอันดับระดับจุดข้อมูลเริ่มจากศูนย์.

**คืนค่า:**
[IChartDataPointLevelsManager](../../com.aspose.slides/ichartdatapointlevelsmanager)
### getIndex() {#getIndex--}
```
public abstract long getIndex()
```


กำหนดว่าจุดข้อมูลนี้ใช้กับคอลเลกชันลูกของพาเรนต์ตัวใด. อ่าน long.

**คืนค่า:**
long