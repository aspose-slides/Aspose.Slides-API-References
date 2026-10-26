---
title: ChartDataPointCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคอลเลกชันของจุดข้อมูลซีรีส์หนึ่ง.
type: docs
url: /th/com.aspose.slides/chartdatapointcollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
```
public class ChartDataPointCollection extends DomObject<ChartSeries> implements IChartDataPointCollection
```

เป็นตัวแทนของคอลเลกชันของข้อมูลจุดซีรีส์หนึ่งรายการ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าจุดข้อมูลซีรีส์ตามดัชนี (หมายเลขลำดับในคอลเลกชันนี้). |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | คืนค่าดัชนี (หมายเลขลำดับ) ของจุดข้อมูลในคอลเลกชันนี้. |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property XValue ของจุดข้อมูล. |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property XValue ของจุดข้อมูล. |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property YValue ของจุดข้อมูล. |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property YValue ของจุดข้อมูล. |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property BubbleSize ของจุดข้อมูล. |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property BubbleSize ของจุดข้อมูล. |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property Value ของจุดข้อมูล. |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property Value ของจุดข้อมูล. |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ระบุประเภทของค่าต่าง ๆ ในรายการ properties ของ ChartDataPoint.ErrorBarsCustomValues. |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | หากคอลเลกชันมีจุดข้อมูลที่มีดัชนี index อยู่แล้วจะคืนค่าจุดข้อมูลนี้. |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่จริง ๆ ถูกบรรจุอยู่ในคอลเลกชัน. |
| [copyTo(System.Array array, int arrayIndex)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนี้มีการซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. |
| [clear()](#clear--) | ลบทุกองค์ประกอบออกจากคอลเลกชัน. |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | ลบค่าที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งดัชนีที่กำหนด. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```


คืนค่าจุดข้อมูลซีรีส์ตามดัชนี (หมายเลขลำดับในคอลเลกชันนี้).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public final int get_Item(IChartDataPoint pt)
```


คืนค่าดัชนี (หมายเลขลำดับ) ของจุดข้อมูลในคอลเลกชันนี้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**คืนค่า:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public final int getDataSourceTypeForXValues()
```


ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property XValue ของจุดข้อมูล. ในอีกแง่หนึ่งมันระบุประเภทของค่าของ ChartDataPoint.XValue.Data property. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

**คืนค่า:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public final void setDataSourceTypeForXValues(int value)
```


ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property XValue ของจุดข้อมูล. ในอีกแง่หนึ่งมันระบุประเภทของค่าของ ChartDataPoint.XValue.Data property. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public final int getDataSourceTypeForYValues()
```


ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property YValue ของจุดข้อมูล. ในอีกแง่หนึ่งมันระบุประเภทของค่าของ ChartDataPoint.YValue.Data property. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

**คืนค่า:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public final void setDataSourceTypeForYValues(int value)
```


ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property YValue ของจุดข้อมูล. ในอีกแง่หนึ่งมันระบุประเภทของค่าของ ChartDataPoint.YValue.Data property. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public final int getDataSourceTypeForBubbleSizes()
```


ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property BubbleSize ของจุดข้อมูล. ในอีกแง่หนึ่งมันระบุประเภทของค่าของ ChartDataPoint.BubbleSize.Data property. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

**คืนค่า:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public final void setDataSourceTypeForBubbleSizes(int value)
```


ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property BubbleSize ของจุดข้อมูล. ในอีกแง่หนึ่งมันระบุประเภทของค่าของ ChartDataPoint.BubbleSize.Data property. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public final int getDataSourceTypeForValues()
```


ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property Value ของจุดข้อมูล. ในอีกแง่หนึ่งมันระบุประเภทของค่าของ ChartDataPoint.Value.Data property. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

**คืนค่า:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public final void setDataSourceTypeForValues(int value)
```


ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงใน object property Value ของจุดข้อมูล. ในอีกแง่หนึ่งมันระบุประเภทของค่าของ ChartDataPoint.Value.Data property. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public final IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```


ระบุประเภทของค่าต่าง ๆ ในรายการ properties ของ ChartDataPoint.ErrorBarsCustomValues. อ่านอย่างเดียว [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues).

**คืนค่า:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public final IChartDataPoint getOrCreateDataPointByIdx(long index)
```


หากคอลเลกชันมีจุดข้อมูลที่มีดัชนี index อยู่แล้วจะคืนค่าจุดข้อมูลนี้. หากคอลเลกชันไม่มีจุดข้อมูลที่ดัชนี index==N (เมื่อจำนวนจุดข้อมูลในคอลเลกชันนี้น้อยกว่าหรือเท่ากับ N) จะเพิ่มจุดข้อมูลที่ขาดและคืนค่าจุดข้อมูลสุดท้าย (ที่มีดัชนีที่ร้องขอ). ตัวอย่างเช่น ดัชนีของคอลเลกชันคือ \{0, 1, 2\} และดัชนีที่ร้องขอคือ 5. แล้วเมธอดจะเพิ่มจุดข้อมูลที่ขาด: \{0, 1, 2, 3, 4, 5\}. และคืนค่าจุดข้อมูลที่ดัชนี 5.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | long | ดัชนี. |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - คืนค่าจุดข้อมูลที่ดัชนีที่ร้องขอ.
### size() {#size--}
```
public final int size()
```


รับจำนวนขององค์ประกอบที่จริง ๆ ถูกบรรจุอยู่ในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### copyTo(System.Array array, int arrayIndex) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int arrayIndex)
```


คัดลอกไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์ที่ต้องการคัดลอกไป. |
| arrayIndex | int | ดัชนีเริ่มต้นการคัดลอก. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนี้มีการซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่ารากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```


คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในตำแหน่งสุดท้ายของคอลเลกชัน. ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Stock (ดูเพิ่มเติมเมธอด [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล. |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public final IChartDataPoint addDataPointForStockSeries(double value)
```
Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Stock subtypes (see also [ChartTypeCharacterizer.isChartTypeStock(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeStock-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล. |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าจุดข้อมูล. |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public final IChartDataPoint addDataPointForLineSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Line subtypes (see also [ChartTypeCharacterizer.isChartTypeLine(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeLine-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล. |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า X ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า Y ของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | ค่า X ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า Y ของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | ค่า X ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า Y ของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า X ของจุดข้อมูล |
| yValue | double | ค่า Y ของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | ค่า X ของจุดข้อมูล |
| yValue | double | ค่า Y ของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public final IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Scatter subtypes (see also [ChartTypeCharacterizer.isChartTypeScatter(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeScatter-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | ค่า X ของจุดข้อมูล |
| yValue | double | ค่า Y ของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public final IChartDataPoint addDataPointForRadarSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Radar subtypes (see also [ChartTypeCharacterizer.isChartTypeRadar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeRadar-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) and [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public final IChartDataPoint addDataPointForBarSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Column or Bar subtypes (see also [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) and [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public final IChartDataPoint addDataPointForAreaSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Area subtypes (see also [ChartTypeCharacterizer.isChartTypeArea(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeArea-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) method).

**พารามิ터:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public final IChartDataPoint addDataPointForPieSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Pie subtypes (see also [ChartTypeCharacterizer.isChartTypePie(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypePie-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public final IChartDataPoint addDataPointForDoughnutSeries(double value)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Doughnut subtypes (see also [ChartTypeCharacterizer.isChartTypeDoughnut(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeDoughnut-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า X ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า Y ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ขนาดฟองของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | ค่า X ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า Y ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ขนาดฟองของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | ค่า X ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า Y ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ขนาดฟองของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่า X ของจุดข้อมูล |
| yValue | double | ค่า Y ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ขนาดฟองของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | ค่า X ของจุดข้อมูล |
| yValue | double | ค่า Y ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ขนาดฟองของจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

Creates the new data point and adds it to the end of collection. Applicable for series which chartType is one of Bubble subtypes (see also [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-) method).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล BubbleSize |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในชนิดย่อย Bubble (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในชนิดย่อย Bubble (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในชนิดย่อย Bubble (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในชนิดย่อย Bubble (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในชนิดย่อย Bubble (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public final IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในชนิดย่อย Bubble (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeBubble(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBubble-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในชนิดย่อย Surface (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public final IChartDataPoint addDataPointForSurfaceSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในชนิดย่อย Surface (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeSurface(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeSurface-int-)).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chart type เป็น Sunburst.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล SizeValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chart type เป็น Treemap.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล SizeValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chart type เป็น BoxAndWhisker.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chart type เป็น Waterfall.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chart type เป็น Histogram.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chart type เป็น Funnel.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public final IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chart type เป็น Map.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Map, 50, 50, 500, 400, false);
>      IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>      IChartSeries series = chart.getChartData().getSeries().add(ChartType.Map);
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B2", 5));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B3", 1));
>      series.getDataPoints().addDataPointForMapSeries(wb.getCell(0, "B4", 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล ColorValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### clear() {#clear--}
```
public final void clear()
```

ลบองค์ประกอบทั้งหมดออกจากคอลเลกชัน.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public final void remove(IChartDataPoint value)
```

ลบค่าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ค่า |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของจุดข้อมูลที่จะลบ. |