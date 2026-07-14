---
title: ChartSeriesCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคอลเลกชันของ
type: docs
url: /th/com.aspose.slides/chartseriescollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**ทุกอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

แสดงคอลเลกชันของ [ChartSeries](../../com.aspose.slides/chartseries)
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [size()](#size--) | คืนค่าจำนวนอ็อบเจ็กต์ในคอลเลกชัน. |
| [add(int type)](#add-int-) | สร้างชุดข้อมูลแผนภูมิใหม่และเพิ่มลงในคอลเลกชัน. |
| [insert(int index, int type)](#insert-int-int-) | สร้างชุดข้อมูลแผนภูมิใหม่และแทรกลงในคอลเลกชัน. |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | สร้างชุดข้อมูลแผนภูมิใหม่จาก [ChartDataCell](../../com.aspose.slides/chartdatacell) และเพิ่มลงในคอลเลกชัน. |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | สร้างชุดข้อมูลแผนภูมิใหม่จาก [ChartCellCollection](../../com.aspose.slides/chartcellcollection) และเพิ่มลงในคอลเลกชัน. |
| [add(String name, int type)](#add-java.lang.String-int-) | สร้างชุดข้อมูลแผนภูมิใหม่จากค่าและเพิ่มลงในคอลเลกชัน. |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | ค้นหา [ChartSeries](../../com.aspose.slides/chartseries) ที่ระบุและคืนค่าอินเด็กซ์โดยเริ่มจากศูนย์ของการพบครั้งแรกในคอลเลกชันทั้งหมด |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | ลบค่าที่ระบุ. |
| [removeAt(int index)](#removeAt-int-) | ลบคอนโทรล ActiveX ที่เก็บไว้ในตำแหน่งที่ระบุจากคอลเลกชัน. |
| [clear()](#clear--) | ลบคอนโทรลทั้งหมดจากคอลเลกชัน. |
| [iterator()](#iterator--) | คืนตัววนซ้ำที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนตัว iterator ของ Java สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```


รับองค์ประกอบที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) - องค์ประกอบที่ตำแหน่งที่ระบุ.
### size() {#size--}
```
public final int size()
```


คืนค่าจำนวนอ็อบเจ็กต์ในคอลเลกชัน. int แบบอ่านอย่างเดียว.

**คืนค่า:**
int
### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```


สร้างชุดข้อมูลแผนภูมิใหม่และเพิ่มลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของซีรีส์ |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ชุดข้อมูลแผนภูมิใหม่.
### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```


สร้างชุดข้อมูลแผนภูมิใหม่และแทรกลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |
| type | int |  |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public final IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```


สร้างชุดข้อมูลแผนภูมิใหม่จาก [ChartDataCell](../../com.aspose.slides/chartdatacell) และเพิ่มลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ที่มีชื่อซีรีส์ |
| type | int | ประเภทของซีรีส์

--------------------

หากชุดข้อมูลแผนภูมิสร้างจากเซลล์เดียวกันที่มีอยู่แล้วในคอลเลกชัน วิธีนี้จะไม่เพิ่มอะไรและจะคืนค่าอินเด็กซ์ของมัน. |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ชุดข้อมูลแผนภูมิที่เพิ่มหรือชุดข้อมูลที่มีอยู่แล้วในคอลเลกชัน.
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```


สร้างชุดข้อมูลแผนภูมิใหม่จาก [ChartCellCollection](../../com.aspose.slides/chartcellcollection) และเพิ่มลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | เซลล์ที่มีชื่อซีรีส์ |
| type | int | ประเภทของซีรีส์

--------------------

หากชุดข้อมูลแผนภูมิสร้างจากเซลล์เดียวกันที่มีอยู่แล้วในคอลเลกชัน วิธีนี้จะไม่เพิ่มอะไรและจะคืนค่าอินเด็กซ์ของมัน. |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ชุดข้อมูลแผนภูมิที่เพิ่มหรือชุดข้อมูลที่มีอยู่แล้วในคอลเลกชัน.
### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```


สร้างชุดข้อมูลแผนภูมิใหม่จากค่าและเพิ่มลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อซีรีส์ |
| type | int | ประเภทของซีรีส์ |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ชุดข้อมูลแผนภูมิที่เพิ่ม.
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```


ค้นหา [ChartSeries](../../com.aspose.slides/chartseries) ที่ระบุและคืนค่าอินเด็กซ์โดยเริ่มจากศูนย์ของการพบครั้งแรกในคอลเลกชันทั้งหมด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | ค่าชุดข้อมูลแผนภูมิ |

**คืนค่า:**
int - อินเด็กซ์ที่เริ่มจากศูนย์ของการพบครั้งแรกของค่าใน CollectionBase ทั้งหมด, หากพบ; มิฉะนั้น, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```


ลบค่าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | ค่าดังกล่าว |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบคอนโทรล ActiveX ที่เก็บไว้ในตำแหน่งที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอนโทรลที่ต้องการลบ |
### clear() {#clear--}
```
public final void clear()
```


ลบคอนโทรลทั้งหมดจากคอลเลกชัน.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```


คืนตัววนซ้ำที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```


คืนตัว iterator ของ Java สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกคอลเลกชันทั้งหมดไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีในอาเรย์เป้าหมาย |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). boolean แบบอ่านอย่างเดียว.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่า synchronization root. java.lang.Object แบบอ่านอย่างเดียว.

**คืนค่า:**
java.lang.Object