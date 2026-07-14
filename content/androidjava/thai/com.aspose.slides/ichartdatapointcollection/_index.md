---
title: IChartDataPointCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคอลเลกชันของจุดข้อมูลชุดข้อมูล
type: docs
url: /th/com.aspose.slides/ichartdatapointcollection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
com.aspose.slides.IGenericCollection
```
public interface IChartDataPointCollection extends IGenericCollection<IChartDataPoint>
```

แสดงคอลเลกชันของจุดข้อมูลชุดข้อมูลหนึ่ง

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าจุดข้อมูลชุดข้อมูลตามดัชนี (หมายเลขลำดับในคอลเลกชันนี้) |
| [get_Item(IChartDataPoint pt)](#get-Item-com.aspose.slides.IChartDataPoint-) | คืนค่าดัชนี (หมายเลขลำดับในคอลเลกชันนี้) ของจุดข้อมูลในคอลเลกชันนี้ |
| [getDataSourceTypeForXValues()](#getDataSourceTypeForXValues--) | กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property XValue ของจุดข้อมูล |
| [setDataSourceTypeForXValues(int value)](#setDataSourceTypeForXValues-int-) | กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property XValue ของจุดข้อมูล |
| [getDataSourceTypeForYValues()](#getDataSourceTypeForYValues--) | กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property YValue ของจุดข้อมูล |
| [setDataSourceTypeForYValues(int value)](#setDataSourceTypeForYValues-int-) | กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property YValue ของจุดข้อมูล |
| [getDataSourceTypeForBubbleSizes()](#getDataSourceTypeForBubbleSizes--) | กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property BubbleSize ของจุดข้อมูล |
| [setDataSourceTypeForBubbleSizes(int value)](#setDataSourceTypeForBubbleSizes-int-) | กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property BubbleSize ของจุดข้อมูล |
| [getDataSourceTypeForValues()](#getDataSourceTypeForValues--) | กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property Value ของจุดข้อมูล |
| [setDataSourceTypeForValues(int value)](#setDataSourceTypeForValues-int-) | กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property Value ของจุดข้อมูล |
| [getDataSourceTypeForErrorBarsCustomValues()](#getDataSourceTypeForErrorBarsCustomValues--) | กำหนดประเภทของค่าในรายการ properties ChartDataPoint.ErrorBarsCustomValues |
| [getOrCreateDataPointByIdx(long index)](#getOrCreateDataPointByIdx-long-) | หากคอลเลกชันมีจุดข้อมูลที่ดัชนี index แล้วจะคืนค่าจุดข้อมูลนั้น |
| [addDataPointForStockSeries(IChartDataCell value)](#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForStockSeries(double value)](#addDataPointForStockSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForLineSeries(IChartDataCell value)](#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForLineSeries(double value)](#addDataPointForLineSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(double xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(String xValue, IChartDataCell yValue)](#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(IChartDataCell xValue, double yValue)](#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(double xValue, double yValue)](#addDataPointForScatterSeries-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForScatterSeries(String xValue, double yValue)](#addDataPointForScatterSeries-java.lang.String-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForRadarSeries(IChartDataCell value)](#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForRadarSeries(double value)](#addDataPointForRadarSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBarSeries(IChartDataCell value)](#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBarSeries(double value)](#addDataPointForBarSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForAreaSeries(IChartDataCell value)](#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForAreaSeries(double value)](#addDataPointForAreaSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForPieSeries(IChartDataCell value)](#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForPieSeries(double value)](#addDataPointForPieSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForDoughnutSeries(IChartDataCell value)](#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForDoughnutSeries(double value)](#addDataPointForDoughnutSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-double-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)](#addDataPointForBubbleSeries-java.lang.String-double-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForSurfaceSeries(IChartDataCell value)](#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForSurfaceSeries(double value)](#addDataPointForSurfaceSeries-double-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForSunburstSeries(IChartDataCell sizeValue)](#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForWaterfallSeries(IChartDataCell value)](#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForBoxAndWhiskerSeries(IChartDataCell value)](#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForTreemapSeries(IChartDataCell sizeValue)](#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForHistogramSeries(IChartDataCell value)](#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForFunnelSeries(IChartDataCell value)](#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [addDataPointForMapSeries(IChartDataCell value)](#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-) | สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน |
| [clear()](#clear--) | ลบทุกองค์ประกอบออกจากคอลเลกชัน |
| [remove(IChartDataPoint value)](#remove-com.aspose.slides.IChartDataPoint-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งดัชนีที่กำหนด |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

คืนค่าจุดข้อมูลชุดข้อมูลตามดัชนี (หมายเลขลำดับในคอลเลกชันนี้)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
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

**คืนค่า:**
int

### getDataSourceTypeForXValues() {#getDataSourceTypeForXValues--}
```
public abstract int getDataSourceTypeForXValues()
```

กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property XValue ของจุดข้อมูล ในความหมายอื่น ๆ จะกำหนดประเภทของค่าของ property ChartDataPointEx.XValue.Data   อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**คืนค่า:**
int

### setDataSourceTypeForXValues(int value) {#setDataSourceTypeForXValues-int-}
```
public abstract void setDataSourceTypeForXValues(int value)
```

กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property XValue ของจุดข้อมูล ในความหมายอื่น ๆ จะกำหนดประเภทของค่าของ property ChartDataPointEx.XValue.Data   อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForYValues() {#getDataSourceForYValues--}
```
public abstract int getDataSourceTypeForYValues()
```

กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property YValue ของจุดข้อมูล ในความหมายอื่น ๆ จะกำหนดประเภทของค่าของ property ChartDataPointEx.YValue.Data   อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**คืนค่า:**
int

### setDataSourceTypeForYValues(int value) {#setDataSourceTypeForYValues-int-}
```
public abstract void setDataSourceTypeForYValues(int value)
```

กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property YValue ของจุดข้อมูล ในความหมายอื่น ๆ จะกำหนดประเภทของค่าของ property ChartDataPointEx.YValue.Data   อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForBubbleSizes() {#getDataSourceForBubbleSizes--}
```
public abstract int getDataSourceTypeForBubbleSizes()
```

กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property BubbleSize ของจุดข้อมูล ในความหมายอื่น ๆ จะกำหนดประเภทของค่าของ property ChartDataPointEx.BubbleSize.Data   อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**คืนค่า:**
int

### setDataSourceTypeForBubbleSizes(int value) {#setDataSourceTypeForBubbleSizes-int-}
```
public abstract void setDataSourceTypeForBubbleSizes(int value)
```

กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property BubbleSize ของจุดข้อมูล ในความหมายอื่น ๆ จะกำหนดประเภทของค่าของ property ChartDataPointEx.BubbleSize.Data   อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForValues() {#getDataSourceForValues--}
```
public abstract int getDataSourceTypeForValues()
```

กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property Value ของจุดข้อมูล ในความหมายอื่น ๆ จะกำหนดประเภทของค่าของ property ChartDataPoint.Value.Data   อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**คืนค่า:**
int

### setDataSourceTypeForValues(int value) {#setDataSourceTypeForValues-int-}
```
public abstract void setDataSourceTypeForValues(int value)
```

กำหนดว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุ property Value ของจุดข้อมูล ในความหมายอื่น ๆ จะกำหนดประเภทของค่าของ property ChartDataPoint.Value.Data   อ่าน/เขียน [DataSourceType](../../com.aspose.slides/datasourcetype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDataSourceTypeForErrorBarsCustomValues() {#getDataSourceTypeForErrorBarsCustomValues--}
```
public abstract IDataSourceTypeForErrorBarsCustomValues getDataSourceTypeForErrorBarsCustomValues()
```

กำหนดประเภทของค่าที่อยู่ในรายการ properties ChartDataPoint.ErrorBarsCustomValues   อ่านอย่างเดียว [IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

**คืนค่า:**
[IDataSourceTypeForErrorBarsCustomValues](../../com.aspose.slides/idatasourcetypeforerrorbarscustomvalues)

### getOrCreateDataPointByIdx(long index) {#getOrCreateDataPointByIdx-long-}
```
public abstract IChartDataPoint getOrCreateDataPointByIdx(long index)
```

หากคอลเลกชันมีจุดข้อมูลที่ดัชนี index แล้วจะคืนค่าจุดข้อมูลนั้น หากคอลเลกชันไม่มีจุดข้อมูลที่ดัชนี index==N (เมื่อจำนวนจุดข้อมูลในคอลเลกชันน้อยกว่าหรือเท่ากับ N) จะเพิ่มจุดข้อมูลที่ขาดและคืนค่าจุดข้อมูลสุดท้าย (ซึ่งมีดัชนีตามที่ร้องขอ) ตัวอย่างเช่น ดัชนีของคอลเลกชันคือ {0, 1, 2} และดัชนีที่ร้องขอคือ 5 จะเพิ่มจุดข้อมูลที่ขาด: {0, 1, 2, 3, 4, 5} แล้วคืนค่าจุดข้อมูลที่ดัชนี 5

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | long | ดัชนี |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - คืนค่าจุดข้อมูลที่ดัชนีตามที่ร้องขอ

### addDataPointForStockSeries(IChartDataCell value) {#addDataPointForStockSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForStockSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Stock (ดูเมธอด ChartTypeCharacterizer.IsChartTypeStock(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForStockSeries(double value) {#addDataPointForStockSeries-double-}
```
public abstract IChartDataPoint addDataPointForStockSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Stock (ดูเมธอด ChartTypeCharacterizer.IsChartTypeStock(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForLineSeries(IChartDataCell value) {#addDataPointForLineSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForLineSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Line (ดูเมธอด ChartTypeCharacterizer.IsChartTypeLine(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForLineSeries(double value) {#addDataPointForLineSeries-double-}
```
public abstract IChartDataPoint addDataPointForLineSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Line (ดูเมธอด ChartTypeCharacterizer.IsChartTypeLine(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, IChartDataCell yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForScatterSeries(double xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, IChartDataCell yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForScatterSeries(String xValue, IChartDataCell yValue) {#addDataPointForScatterSeries-java.lang.String-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, IChartDataCell yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForScatterSeries(IChartDataCell xValue, double yValue) {#addDataPointForScatterSeries-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(IChartDataCell xValue, double yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForScatterSeries(double xValue, double yValue) {#addDataPointForScatterSeries-double-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(double xValue, double yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForScatterSeries(String xValue, double yValue) {#addDataPointForScatterSeries-java.lang.String-double-}
```
public abstract IChartDataPoint addDataPointForScatterSeries(String xValue, double yValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Scatter (ดูเมธอด ChartTypeCharacterizer.IsChartTypeScatter(ChartType) เพิ่มเติม)

**พารามิ터:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForRadarSeries(IChartDataCell value) {#addDataPointForRadarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Radar (ดูเมธอด ChartTypeCharacterizer.IsChartTypeRadar(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForRadarSeries(double value) {#addDataPointForRadarSeries-double-}
```
public abstract IChartDataPoint addDataPointForRadarSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภทย่อย Radar (ดูเมธอด ChartTypeCharacterizer.IsChartTypeRadar(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBarSeries(IChartDataCell value) {#addDataPointForBarSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBarSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType อยู่ในประเภท Column หรือ Bar (ดูเมธอด ChartTypeCharacterizer.IsChartTypeColumn(ChartType) และ ChartTypeCharacterizer.IsChartTypeBar(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBarSeries(double value) {#addDataPointForBarSeries-double-}
```
public abstract IChartDataPoint addDataPointForBarSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType อยู่ในประเภท Column หรือ Bar (ดูเมธอด ChartTypeCharacterizer.IsChartTypeColumn(ChartType) และ ChartTypeCharacterizer.IsChartTypeBar(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForAreaSeries(IChartDataCell value) {#addDataPointForAreaSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Area (ดูเมธอด ChartTypeCharacterizer.IsChartTypeArea(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForAreaSeries(double value) {#addDataPointForAreaSeries-double-}
```
public abstract IChartDataPoint addDataPointForAreaSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Area (ดูเมธอด ChartTypeCharacterizer.IsChartTypeArea(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForPieSeries(IChartDataCell value) {#addDataPointForPieSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForPieSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Pie (ดูเมธอด ChartTypeCharacterizer.IsChartTypePie(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForPieSeries(double value) {#addDataPointForPieSeries-double-}
```
public abstract IChartDataPoint addDataPointForPieSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Pie (ดูเมธอด ChartTypeCharacterizer.IsChartTypePie(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForDoughnutSeries(IChartDataCell value) {#addDataPointForDoughnutSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Doughnut (ดูเมธอด ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForDoughnutSeries(double value) {#addDataPointForDoughnutSeries-double-}
```
public abstract IChartDataPoint addDataPointForDoughnutSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Doughnut (ดูเมธอด ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-double-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, IChartDataCell bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |
| bubbleSize | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, IChartDataCell yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |
| bubbleSize | double | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, IChartDataCell yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |
| bubbleSize | double | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-com.aspose.slides.IChartDataCell-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, IChartDataCell yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | XValue ของจุดข้อมูล |
| yValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | YValue ของจุดข้อมูล |
| bubbleSize | double | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-com.aspose.slides.IChartDataCell-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(IChartDataCell xValue, double yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |
| bubbleSize | double | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-double-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(double xValue, double yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | double | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |
| bubbleSize | double | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize) {#addDataPointForBubbleSeries-java.lang.String-double-double-}
```
public abstract IChartDataPoint addDataPointForBubbleSeries(String xValue, double yValue, double bubbleSize)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Bubble (ดูเมธอด ChartTypeCharacterizer.IsChartTypeBubble(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xValue | java.lang.String | XValue ของจุดข้อมูล |
| yValue | double | YValue ของจุดข้อมูล |
| bubbleSize | double | BubbleSize ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForSurfaceSeries(IChartDataCell value) {#addDataPointForSurfaceSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Surface (ดูเมธอด ChartTypeCharacterizer.IsChartTypeSurface(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForSurfaceSeries(double value) {#addDataPointForSurfaceSeries-double-}
```
public abstract IChartDataPoint addDataPointForSurfaceSeries(double value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chartType เป็นหนึ่งในประเภท Surface (ดูเมธอด ChartTypeCharacterizer.IsChartTypeSurface(ChartType) เพิ่มเติม)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForSunburstSeries(IChartDataCell sizeValue) {#addDataPointForSunburstSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForSunburstSeries(IChartDataCell sizeValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chart type เป็น Sunburst

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForWaterfallSeries(IChartDataCell value) {#addDataPointForWaterfallSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForWaterfallSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chart type เป็น Waterfall

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForBoxAndWhiskerSeries(IChartDataCell value) {#addDataPointForBoxAndWhiskerSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForBoxAndWhiskerSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chart type เป็น BoxAndWhisker

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForTreemapSeries(IChartDataCell sizeValue) {#addDataPointForTreemapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForTreemapSeries(IChartDataCell sizeValue)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chart type เป็น Treemap

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| sizeValue | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | SizeValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForHistogramSeries(IChartDataCell value) {#addDataPointForHistogramSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForHistogramSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chart type เป็น Histogram

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForFunnelSeries(IChartDataCell value) {#addDataPointForFunnelSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForFunnelSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chart type เป็น Funnel

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ค่าของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### addDataPointForMapSeries(IChartDataCell value) {#addDataPointForMapSeries-com.aspose.slides.IChartDataCell-}
```
public abstract IChartDataPoint addDataPointForMapSeries(IChartDataCell value)
```

สร้างจุดข้อมูลใหม่และเพิ่มเข้าไปที่ตำแหน่งสุดท้ายของคอลเลกชัน ใช้กับชุดข้อมูลที่ chart type เป็น Map

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
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | ColorValue ของจุดข้อมูล |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลใหม่

### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกองค์ประกอบออกจากคอลเลกชัน

### remove(IChartDataPoint value) {#remove-com.aspose.slides.IChartDataPoint-}
```
public abstract void remove(IChartDataPoint value)
```

ลบค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | ค่าที่ระบุ |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งดัชนีที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของจุดข้อมูลที่จะลบ |