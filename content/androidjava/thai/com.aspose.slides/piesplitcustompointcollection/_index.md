---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของจุดสำหรับจุดแบ่งในแผนภูมิ bar-of-pie หรือ pie-of-pie ด้วยการแบ่งแบบกำหนดเอง.
type: docs
url: /th/com.aspose.slides/piesplitcustompointcollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

Represents a collection of points for splitting point in a bar-of-pie or pie-of-pie chart with a custom split.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่า chart data point สำหรับดัชนีที่ระบุ. |
| [add(int dataPointIndex)](#add-int-) | เพิ่ม data point โดยดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | เพิ่ม data point ลงในคอลเลกชัน. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | ลบรายการออกจากคอลเลกชัน. |
| [remove(int dataPointIndex)](#remove-int-) | ลบรายการออกจากคอลเลกชันโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่. |
| [clear()](#clear--) | ลบทุกรายการออกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | กำหนดว่าค่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [size()](#size--) | คืนค่าหรือกำหนดจำนวน chart data points. |
| [isReadOnly()](#isReadOnly--) | รับค่าที่บ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนี้ซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากการซิงโครไนซ์. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |

### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

คืนค่า chart data point สำหรับดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนี. |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลแผนภูมิ.

### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

เพิ่ม data point โดยดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dataPointIndex | int | ดัชนีของ data point ในคอลเลกชันจุดของซีรีส์แม่. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

เพิ่ม data point ลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Data point ที่จะเพิ่มเข้ามา. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

ลบรายการออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | Data point ที่จะลบออกจาก. |

**คืนค่า:**
boolean - true หากรายการถูกลบสำเร็จ; ไม่เช่นนั้น, false. วิธีนี้ยังคืนค่า false หากไม่พบรายการใน System.Collections.Generic.List\{T\}.

### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

ลบรายการออกจากคอลเลกชันโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dataPointIndex | int | ดัชนีของ data point ในคอลเลกชันจุดของซีรีส์แม่. |

### clear() {#clear--}
```
public final void clear()
```

ลบทุกรายการออกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

กำหนดว่าค่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | วัตถุที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); ไม่เช่นนั้น, false.

### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | The one-dimensional Array that is the destination of the elements copied from [IGenericCollection](../../com.aspose.slides/igenericcollection). The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### size() {#size--}
```
public final int size()
```

คืนค่าหรือกำหนดจำนวน chart data points. อ่านอย่างเดียว int.

**คืนค่า:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

รับค่าที่บ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว; ไม่เช่นนั้น, false.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนี้ซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iterator()
```

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - An java.util.Iterator for the entire collection.