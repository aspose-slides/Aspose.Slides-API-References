---
title: ChartSeriesCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นคอลเลกชันของ
type: docs
url: /th/com.aspose.slides/chartseriescollection/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**Interfaces ที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)  
```
public class ChartSeriesCollection extends DomObject<ChartData> implements IChartSeriesCollection
```

แสดงถึงคอลเลกชันของ [ChartSeries](../../com.aspose.slides/chartseries)

## วิธีการ

| เมธอด | รายละเอียด |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ได้รับอีลีเมนต์ที่ตำแหน่งที่ระบุ |
| [size()](#size--) | คืนจำนวนอ็อบเจกต์ในคอลเลกชัน |
| [add(int type)](#add-int-) | สร้างซีรีส์แผนภูมิใหม่และเพิ่มลงในคอลเลกชัน |
| [insert(int index, int type)](#insert-int-int-) | สร้างซีรีส์แผนภูมิใหม่และแทรกลงในคอลเลกชัน |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | สร้างซีรีส์แผนภูมิใหม่จาก [ChartDataCell](../../com.aspose.slides/chartdatacell) และเพิ่มลงในคอลเลกชัน |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | สร้างซีรีส์แผนภูมิใหม่จาก [ChartCellCollection](../../com.aspose.slides/chartcellcollection) และเพิ่มลงในคอลเลกชัน |
| [add(String name, int type)](#add-java.lang.String-int-) | สร้างซีรีส์แผนภูมิใหม่จากค่าและเพิ่มลงในคอลเลกชัน |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | ค้นหา [ChartSeries](../../com.aspose.slides/chartseries) ที่ระบุและคืนดัชนีฐานศูนย์ของการพบครั้งแรกใน Collection ทั้งหมด |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบ ActiveX control ที่จัดเก็บไว้ที่ตำแหน่งที่ระบุจากคอลเลกชัน |
| [clear()](#clear--) | ลบคอนโทรลทั้งหมดจากคอลเลกชัน |
| [iterator()](#iterator--) | คืน enumerator ที่วนรอบคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้ซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ |
| [getSyncRoot()](#getSyncRoot--) | คืน synchronization root |

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

ได้รับอีลีเมนต์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) – อีลีเมนต์ที่ตำแหน่งที่ระบุ

### size() {#size--}
```
public final int size()
```

คืนจำนวนอ็อบเจกต์ในคอลเลกชัน แบบอ่านอย่างเดียว int

**คืนค่า:**
int

### add(int type) {#add-int-}
```
public final IChartSeries add(int type)
```

สร้างซีรีส์แผนภูมิใหม่และเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของซีรีส์ |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) – ซีรีส์แผนภูมิใหม่

### insert(int index, int type) {#insert-int-int-}
```
public final IChartSeries insert(int index, int type)
```

สร้างซีรีส์แผนภูมิใหม่และแทรกลงในคอลเลกชัน

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

สร้างซีรีส์แผนภูมิใหม่จาก [ChartDataCell](../../com.aspose.slides/chartdatacell) และเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ที่มีชื่อซีรีส์ |
| type | int | ประเภทของซีรีส์ |

--------------------

หากซีรีส์แผนภูมิที่สร้างจากเซลล์เดียวกันมีอยู่แล้วในคอลเลกชัน เมธอดจะไม่ทำการเพิ่มและจะคืนค่าเป็นดัชนีของมัน |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) – ซีรีส์แผนภูมิที่เพิ่มหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public final IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

สร้างซีรีส์แผนภูมิใหม่จาก [ChartCellCollection](../../com.aspose.slides/chartcellcollection) และเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | เซลล์ที่มีชื่อซีรีส์ |
| type | int | ประเภทของซีรีส์ |

--------------------

หากซีรีส์แผนภูมิที่สร้างจากเซลล์เดียวกันมีอยู่แล้วในคอลเลกชัน เมธอดจะไม่ทำการเพิ่มและจะคืนค่าเป็นดัชนีของมัน |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) – ซีรีส์แผนภูมิที่เพิ่มหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน

### add(String name, int type) {#add-java.lang.String-int-}
```
public final IChartSeries add(String name, int type)
```

สร้างซีรีส์แผนภูมิใหม่จากค่าและเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อซีรีส์ |
| type | int | ประเภทของซีรีส์ |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries) – ซีรีส์แผนภูมิที่เพิ่ม

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public final int indexOf(IChartSeries value)
```

ค้นหา [ChartSeries](../../com.aspose.slides/chartseries) ที่ระบุและคืนดัชนีฐานศูนย์ของการพบครั้งแรกใน Collection ทั้งหมด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | ค่าซีรีส์แผนภูมิ |

**คืนค่า:**
int – ดัชนีฐานศูนย์ของการพบครั้งแรกของค่าใน CollectionBase ทั้งหมด ถ้าพบ; มิฉะนั้น -1

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public final void remove(IChartSeries value)
```

ลบค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | ค่าที่จะลบ |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบ ActiveX control ที่จัดเก็บไว้ที่ตำแหน่งที่ระบุจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอนโทรลที่จะลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบคอนโทรลทั้งหมดจากคอลเลกชัน

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iterator()
```

คืน enumerator ที่วนรอบคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> – IGenericEnumerator ที่ใช้วนรอบคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartSeries> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartSeries> – java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนี้ซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่. boolean ที่อ่านอย่างเดียว

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืน synchronization root. Object ที่อ่านอย่างเดียว

**คืนค่า:**
java.lang.Object