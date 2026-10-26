---
title: IChartSeriesCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของ
type: docs
url: /th/com.aspose.slides/ichartseriescollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

เป็นตัวแทนของคอลเลกชันของ [IChartSeries](../../com.aspose.slides/ichartseries)
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ |
| [add(int type)](#add-int-) | สร้างซีรีส์แผนภูมิใหม่และเพิ่มเข้าไปในคอลเลกชัน |
| [insert(int index, int type)](#insert-int-int-) | สร้างซีรีส์แผนภูมิใหม่และแทรกเข้าไปในคอลเลกชัน |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | สร้างซีรีส์แผนภูมิใหม่จาก [IChartDataCell](../../com.aspose.slides/ichartdatacell) และเพิ่มเข้าไปในคอลเลกชัน |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | สร้างซีรีส์แผนภูมิใหม่จาก [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) และเพิ่มเข้าไปในคอลเลกชัน |
| [add(String name, int type)](#add-java.lang.String-int-) | สร้างซีรีส์แผนภูมิใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | ค้นหา [IChartSeries](../../com.aspose.slides/ichartseries) ที่ระบุและคืนค่าดัชนีเริ่มจากศูนย์ของการพบครั้งแรกในคอลเลกชันทั้งหมด |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบทุกองค์ประกอบ (รวมถึงสไตล์ของแผนภูมิ) จากคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - องค์ประกอบที่ตำแหน่งที่ระบุ
### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

สร้างซีรีส์แผนภูมิใหม่และเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของซีรีส์ |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิใหม่
### insert(int index, int type) {#insert-int-int-}
```
public abstract IChartSeries insert(int index, int type)
```

สร้างซีรีส์แผนภูมิใหม่และแทรกเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีสำหรับแทรก (int) |
| type | int | ประเภทแผนภูมิ [ChartType](../../com.aspose.slides/charttype) |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิใหม่ [IChartSeries](../../com.aspose.slides/ichartseries)
### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

สร้างซีรีส์แผนภูมิใหม่จาก [IChartDataCell](../../com.aspose.slides/ichartdatacell) และเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ที่มีชื่อซีรีส์ |
| type | int | ประเภทตั้งค่าของซีรีส์ |

--------------------

หากซีรีส์แผนภูมิที่สร้างจากเซลล์เดียวกันมีอยู่ในคอลเลกชันแล้วเมธอดจะไม่เพิ่มอะไรและคืนค่าดัชนีของมัน. |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิที่เพิ่มหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน
### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

สร้างซีรีส์แผนภูมิใหม่จาก [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) และเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | เซลล์ที่มีชื่อซีรีส์ |
| type | int | ประเภทตั้งค่าของซีรีส์ |

--------------------

หากซีรีส์แผนภูมิที่สร้างจากเซลล์เดียวกันมีอยู่ในคอลเลกชันแล้วเมธอดจะไม่เพิ่มอะไรและคืนค่าดัชนีของมัน. |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิที่เพิ่มหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน
### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

สร้างซีรีส์แผนภูมิใหม่จากค่าและเพิ่มเข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อซีรีส์ |
| type | int | ประเภทตั้งค่าของซีรีส์ |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิที่เพิ่ม
### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

ค้นหา [IChartSeries](../../com.aspose.slides/ichartseries) ที่ระบุและคืนค่าดัชนีเริ่มจากศูนย์ของการพบครั้งแรกในคอลเลกชันทั้งหมด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | ค่าเซียรีส์แผนภูมิ |

**ผลลัพธ์:**
int - ดัชนีเริ่มจากศูนย์ของการพบครั้งแรกของค่าใน CollectionBase ทั้งหมด, หากพบ; มิฉะนั้น, -1.
### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

ลบค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | ค่าที่ระบุ |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนี (int) |
### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกองค์ประกอบ (รวมถึงสไตล์ของแผนภูมิ) จากคอลเลกชัน