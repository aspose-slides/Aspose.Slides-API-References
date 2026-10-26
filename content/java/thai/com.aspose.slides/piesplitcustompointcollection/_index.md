---
title: PieSplitCustomPointCollection
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของจุดสำหรับจุดการแยกในแผนภูมิบาร์-ของ-พายหรือพาย-ของ-พายพร้อมการแยกที่กำหนดเอง.
type: docs
url: /th/com.aspose.slides/piesplitcustompointcollection/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
```
public class PieSplitCustomPointCollection implements IPieSplitCustomPointCollection
```

เป็นชุดของจุดสำหรับจุดการแยกในแผนภูมิบาร์-ของ-พายหรือพาย-ของ-พายพร้อมการแยกที่กำหนดเอง.
## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าจุดข้อมูลแผนภูมิตามดัชนีที่ระบุ. |
| [add(int dataPointIndex)](#add-int-) | เพิ่มจุดข้อมูลโดยดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่. |
| [addItem(IChartDataPoint dataPoint)](#addItem-com.aspose.slides.IChartDataPoint-) | เพิ่มจุดข้อมูลลงในคอลเลกชัน. |
| [removeItem(IChartDataPoint dataPoint)](#removeItem-com.aspose.slides.IChartDataPoint-) | ลบรายการออกจากคอลเลกชัน. |
| [remove(int dataPointIndex)](#remove-int-) | ลบรายการออกจากคอลเลกชันโดยดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่. |
| [clear()](#clear--) | ลบรายการทั้งหมดจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [containsItem(IChartDataPoint item)](#containsItem-com.aspose.slides.IChartDataPoint-) | กำหนดว่าปริมาณ [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่. |
| [copyToTArray(IChartDataPoint[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IChartDataPoint---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาเรย์ เริ่มจากดัชนีอาเรย์ที่กำหนด. |
| [size()](#size--) | คืนค่าหรือกำหนดจำนวนจุดข้อมูลแผนภูมิ. |
| [isReadOnly()](#isReadOnly--) | รับค่าที่บ่งชี้ว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นอ่านอย่างเดียวหรือไม่. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่. |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartDataPoint get_Item(int index)
```

คืนค่าจุดข้อมูลแผนภูมิตามดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนี. |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลแผนภูมิ.
### add(int dataPointIndex) {#add-int-}
```
public final void add(int dataPointIndex)
```

เพิ่มจุดข้อมูลโดยดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dataPointIndex | int | ดัชนีของจุดข้อมูลในคอลเลกชันจุดของซีรีส์แม่. |

### addItem(IChartDataPoint dataPoint) {#addItem-com.aspose.slides.IChartDataPoint-}
```
public void addItem(IChartDataPoint dataPoint)
```

เพิ่มจุดข้อมูลลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | จุดข้อมูลที่จะเพิ่มให้. |

### removeItem(IChartDataPoint dataPoint) {#removeItem-com.aspose.slides.IChartDataPoint-}
```
public boolean removeItem(IChartDataPoint dataPoint)
```

ลบรายการออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dataPoint | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | จุดข้อมูลที่จะลบ. |

**คืนค่า:**
boolean - true หากรายการถูกลบสำเร็จ; มิฉะนั้น false. วิธีการนี้ยังคืนค่า false หากไม่พบรายการใน System.Collections.Generic.List{T}.
### remove(int dataPointIndex) {#remove-int-}
```
public final void remove(int dataPointIndex)
```

ลบรายการออกจากคอลเลกชันโดยดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dataPointIndex | int | ดัชนีของจุดข้อมูลในคอลเลกชันจุดของซีรีส์แม่. |

### clear() {#clear--}
```
public final void clear()
```

ลบรายการทั้งหมดจาก [IGenericCollection](../../com.aspose.slides/igenericcollection).

### containsItem(IChartDataPoint item) {#containsItem-com.aspose.slides.IChartDataPoint-}
```
public boolean containsItem(IChartDataPoint item)
```

กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IChartDataPoint](../../com.aspose.slides/ichartdatapoint) | วัตถุเพื่อค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**
boolean - true หากพบรายการใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false.
### copyToTArray(IChartDataPoint[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IChartDataPoint---int-}
```
public void copyToTArray(IChartDataPoint[] array, int arrayIndex)
```

คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาเรย์ เริ่มจากดัชนีอาเรย์ที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IChartDataPoint\[\]](../../com.aspose.slides/ichartdatapoint) | อาเรย์หนึ่งมิติที่เป็นปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). อาเรย์ต้องมีการจัดทำดัชนีเริ่มที่ศูนย์. |
| arrayIndex | int | ดัชนีเริ่มต้นที่ศูนย์ในอาเรย์ที่การคัดลอกเริ่มต้น. |

### size() {#size--}
```
public final int size()
```

คืนค่าหรือกำหนดจำนวนจุดข้อมูลแผนภูมิ. อ่านอย่างเดียว int.

**คืนค่า:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

รับค่าที่บ่งชี้ว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นอ่านอย่างเดียว. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นอ่านอย่างเดียว; มิฉะนั้น false.
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

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

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartDataPoint> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartDataPoint> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.