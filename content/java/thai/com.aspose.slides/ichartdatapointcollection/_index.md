---
title: IChartDataPointCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคอลเลกชันของจุดข้อมูลซีรีส์
type: docs
url: /th/com.aspose.slides/ichartdatapointcollection/
---
**ทั้งหมดของอินเทอร์เฟซที่ใช้งาน:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

แสดงคอลเลกชันของจุดข้อมูลซีรีส์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าจุดข้อมูลซีรีส์ตามดัชนี (หมายเลขลำดับในคอลเลกชันนี้) |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | คืนค่าดัชนี (หมายเลขลำดับในคอลเลกชันนี้) ของจุดข้อมูลในคอลเลกชันนี้ |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property XValue ของจุดข้อมูล |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property XValue ของจุดข้อมูล |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property YValue ของจุดข้อมูล |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property YValue ของจุดข้อมูล |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property BubbleSize ของจุดข้อมูล |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property BubbleSize ของจุดข้อมูล |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property Value ของจุดข้อมูล |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property Value ของจุดข้อมูล |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | ระบุประเภทของค่าในรายการ properties ของ ChartDataPoint.ErrorBarsCustomValues |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | หากคอลเลกชันมีจุดข้อมูลที่ดัชนี index อยู่แล้วจะคืนค่านั้น |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน |
| [clear()](#clear--) | ลบทุกองค์ประกอบออกจากคอลเลกชัน |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งดัชนีที่กำหนด |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

คืนค่าจุดข้อมูลซีรีส์ตามดัชนี (หมายเลขลำดับในคอลเลกชันนี้)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint)
### get_Item(IChartDataPoint pt) {#get-Item-com.aspose.slides.IChartDataPoint-}
```
public abstract int get_Item(IChartDataPoint pt)
```

คืนค่าดัชนี (หมายเลขลำดับในคอลเลกชันนี้) ของจุดข้อมูลในคอลเลกชันนี้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pt | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) |  |

**ผลลัพธ์:**
int
### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property XValue ของจุดข้อมูล ในอีกมุมหนึ่งระบุประเภทของค่าของ property ChartDataPointEx.XValue.Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**ผลลัพธ์:**
int
### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceForXValues(int value)
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property XValue ของจุดข้อมูล ในอีกมุมหนึ่งระบุประเภทของค่าของ property ChartDataPointEx.XValue.Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForYValues() {#getDataSourceTypeForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property YValue ของจุดข้อมูล ในอีกมุมหนึ่งระบุประเภทของค่าของ property ChartDataPointEx.YValue.Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**ผลลัพธ์:**
int
### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property YValue ของจุดข้อมูล ในอีกมุมหนึ่งระบุประเภทของค่าของ property ChartDataPointEx.YValue.Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForBubbleSizes() {#getDataSourceTypeForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property BubbleSize ของจุดข้อมูล ในอีกมุมหนึ่งระบุประเภทของค่าของ property ChartDataPointEx.BubbleSize.Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**ผลลัพธ์:**
int
### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property BubbleSize ของจุดข้อมูล ในอีกมุมหนึ่งระบุประเภทของค่าของ property ChartDataPointEx.BubbleSize.Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForValues() {#getDataSourceTypeForValues--}
```
public abstract int getDataSourceTypeForValues()
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property Value ของจุดข้อมูล ในอีกมุมหนึ่งระบุประเภทของค่าของ property ChartDataPoint.Value.Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**ผลลัพธ์:**
int
### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property Value ของจุดข้อมูล ในอีกมุมหนึ่งระบุประเภทของค่าของ property ChartDataPoint.Value.Data. อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

ระบุประเภทของค่าที่อยู่ในรายการ properties ของ ChartDataPoint.ErrorBarsCustomValues. อ่านอย่างเดียว [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

**ผลลัพธ์:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)
### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

หากคอลเลกชันมีจุดข้อมูลที่ดัชนี index อยู่แล้วจะคืนค่านั้น หากคอลเลกชันไม่มีจุดข้อมูลที่ดัชนี index==N (เมื่อจำนวนจุดข้อมูลในคอลเลกชันน้อยกว่าหรือเท่ากับ N) จะเพิ่มจุดข้อมูลที่ขาดและคืนค่าจุดสุดท้าย (ที่มีดัชนีตามที่ร้องขอ) ตัวอย่างเช่น ดัชนีของคอลเลกชันคือ {0, 1, 2} และดัชนีที่ร้องขอคือ 5 จากนั้นเมธอดจะเพิ่มจุดข้อมูลที่ขาด: {0, 1, 2, 3, 4, 5} และคืนค่าจุดข้อมูลที่ดัชนี 5

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | long | Index. |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - คืนค่าจุดข้อมูลที่มีดัชนีตามที่ร้องขอ
### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อยของ Stock (ดูเพิ่มเติมในเมธอด ChartTypeCharacterizer.IsChartTypeStock(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่
### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อยของ Stock (ดูเพิ่มเติมในเมธอด ChartTypeCharacterizer.IsChartTypeStock(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่
### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อยของ Line (ดูเพิ่มเติมในเมธอด ChartTypeCharacterizer.IsChartTypeLine(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่
### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อยของ Line (ดูเพิ่มเติมในเมธอด ChartTypeCharacterizer.IsChartTypeLine(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าจุดข้อมูล |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่
### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อยของ Scatter (ดูเพิ่มเติมในเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |

| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Radar (ดูเมธอด ChartTypeCharacterizer.IsChartTypeRadar(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Radar (ดูเมธอด ChartTypeCharacterizer.IsChartTypeRadar(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Column หรือ Bar (ดูเมธอด ChartTypeCharacterizer.IsChartTypeColumn(ChartType) และ ChartTypeCharacterizer.IsChartTypeBar(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Column หรือ Bar (ดูเมธอด ChartTypeCharacterizer.IsChartTypeColumn(ChartType) และ ChartTypeCharacterizer.IsChartTypeBar(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Area (ดูเมธอด ChartTypeCharacterizer.IsChartTypeArea(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Area (ดูเมธอด ChartTypeCharacterizer.IsChartTypeArea(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Pie (ดูเมธอด ChartTypeCharacterizer.IsChartTypePie(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Pie (ดูเมธอด ChartTypeCharacterizer.IsChartTypePie(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Doughnut (ดูเมธอด ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Doughnut (ดูเมธอด ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | จุดข้อมูล Value |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มไปยังส่วนท้ายของคอลเลกชัน ใช้ได้กับซีรีส์ที่ chartType เป็นหนึ่งในประเภทย่อย Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) ด้วย)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```
สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chartType เป็นหนึ่งในประเภท Bubble ย่อย (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chartType เป็นหนึ่งในประเภท Bubble ย่อย (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chartType เป็นหนึ่งในประเภท Bubble ย่อย (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chartType เป็นหนึ่งในประเภท Bubble ย่อย (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chartType เป็นหนึ่งในประเภท Bubble ย่อย (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chartType เป็นหนึ่งในประเภท Bubble ย่อย (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | จุดข้อมูล XValue |
| yValue | double | จุดข้อมูล YValue |
| bubbleSize | double | จุดข้อมูล BubbleSize |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chartType เป็นหนึ่งในประเภท Surface ย่อย (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer.IsChartTypeSurface(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chartType เป็นหนึ่งในประเภท Surface ย่อย (ดูเพิ่มเติมที่เมธอด ChartTypeCharacterizer.IsChartTypeSurface(ChartType))

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | จุดข้อมูล Value |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chart type เป็น Sunburst

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล SizeValue |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chart type เป็น Waterfall

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล value |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chart type เป็น BoxAndWhisker

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล Value |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chart type เป็น Treemap

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล SizeValue |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chart type เป็น Histogram

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล value |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chart type เป็น Funnel

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | จุดข้อมูล value |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```


สร้างจุดข้อมูลใหม่และเพิ่มลงในส่วนท้ายของคอลเลกชัน ใช้สำหรับซีรีส์ที่ chart type เป็น Map

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

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่.
### clear() {#clear--}
```
public abstract void clear()
```


ลบทุกองค์ประกอบจากคอลเลกชัน.

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```


ลบค่าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ค่าที่ระบุ. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของจุดข้อมูลที่ต้องลบ. |