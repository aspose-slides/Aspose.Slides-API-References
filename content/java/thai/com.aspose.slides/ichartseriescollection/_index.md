---
title: IChartSeriesCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคอลเลกชันของ
type: docs
url: /th/com.aspose.slides/ichartseriescollection/
---
**ส่วนติดต่อที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IChartSeriesCollection extends IGenericCollection<IChartSeries>
```

เป็นตัวแทนของคอลเลกชันของ [IChartSeries](../../com.aspose.slides/ichartseries)
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ |
| [add(int type)](#add-int-) | สร้างซีรีส์แผนภูมิใหม่และเพิ่มลงในคอลเลกชัน |
| [insert(int index, int type)](#insert-int-int-) | สร้างซีรีส์แผนภูมิใหม่และแทรกลงในคอลเลกชัน |
| [add(IChartDataCell cellWithSeriesName, int type)](#add-com.aspose.slides.IChartDataCell-int-) | สร้างซีรีส์แผนภูมิใหม่จาก [IChartDataCell](../../com.aspose.slides/ichartdatacell) แล้วเพิ่มลงในคอลเลกชัน |
| [add(IChartCellCollection cellsWithSeriesName, int type)](#add-com.aspose.slides.IChartCellCollection-int-) | สร้างซีรีส์แผนภูมิใหม่จาก [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) แล้วเพิ่มลงในคอลเลกชัน |
| [add(String name, int type)](#add-java.lang.String-int-) | สร้างซีรีส์แผนภูมิใหม่จากค่าแล้วเพิ่มลงในคอลเลกชัน |
| [indexOf(IChartSeries value)](#indexOf-com.aspose.slides.IChartSeries-) | ค้นหา [IChartSeries](../../com.aspose.slides/ichartseries) ที่ระบุและคืนค่าดัชนีฐานศูนย์ของการพบครั้งแรกในคอลเลกชันทั้งหมด |
| [remove(IChartSeries value)](#remove-com.aspose.slides.IChartSeries-) | ลบค่าที่ระบุ |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ |
| [clear()](#clear--) | ลบทุกองค์ประกอบ (รวมถึงสไตล์แผนภูมิ) จากคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

ดึงเอาองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - องค์ประกอบที่ตำแหน่งดัชนีที่ระบุ

### add(int type) {#add-int-}
```
public abstract IChartSeries add(int type)
```

สร้างซีรีส์แผนภูมิใหม่และเพิ่มลงในคอลเลกชัน

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

สร้างซีรีส์แผนภูมิใหม่และแทรกลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีสำหรับการแทรก |
| type | int | ประเภทแผนภูมิ [ChartType](../../com.aspose.slides/charttype) |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิใหม่ [IChartSeries](../../com.aspose.slides/ichartseries)

### add(IChartDataCell cellWithSeriesName, int type) {#add-com.aspose.slides.IChartDataCell-int-}
```
public abstract IChartSeries add(IChartDataCell cellWithSeriesName, int type)
```

สร้างซีรีส์แผนภูมิใหม่จาก [IChartDataCell](../../com.aspose.slides/ichartdatacell) แล้วเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellWithSeriesName | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | เซลล์ที่บรรจุชื่อซีรีส์ |
| type | int | ประเภทที่ตั้งค่าชนิดของซีรีส์ |

--------------------

หากซีรีส์แผนภูมิที่สร้างจากเซลล์เดียวกันมีอยู่แล้วในคอลเลกชัน เมธอดจะไม่ทำการเพิ่มใด ๆ และคืนค่าดัชนีของมัน

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิที่เพิ่มหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน

### add(IChartCellCollection cellsWithSeriesName, int type) {#add-com.aspose.slides.IChartCellCollection-int-}
```
public abstract IChartSeries add(IChartCellCollection cellsWithSeriesName, int type)
```

สร้างซีรีส์แผนภูมิใหม่จาก [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) แล้วเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cellsWithSeriesName | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) | เซลล์ที่บรรจุชื่อซีรีส์ |
| type | int | ประเภทที่ตั้งค่าชนิดของซีรีส์ |

--------------------

หากซีรีส์แผนภูมิที่สร้างจากเซลล์เดียวกันมีอยู่แล้วในคอลเลกชัน เมธอดจะไม่ทำการเพิ่มใด ๆ และคืนค่าดัชนีของมัน

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิที่เพิ่มหรือซีรีส์ที่มีอยู่แล้วในคอลเลกชัน

### add(String name, int type) {#add-java.lang.String-int-}
```
public abstract IChartSeries add(String name, int type)
```

สร้างซีรีส์แผนภูมิใหม่จากค่าแล้วเพิ่มลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อซีรีส์ |
| type | int | ประเภทที่ตั้งค่าชนิดของซีรีส์ |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries) - ซีรีส์แผนภูมิที่เพิ่ม

### indexOf(IChartSeries value) {#indexOf-com.aspose.slides.IChartSeries-}
```
public abstract int indexOf(IChartSeries value)
```

ค้นหา [IChartSeries](../../com.aspose.slides/ichartseries) ที่ระบุและคืนค่าดัชนีฐานศูนย์ของการพบครั้งแรกในคอลเลกชันทั้งหมด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | ค่าซีรีส์แผนภูมิ |

**ผลลัพธ์:**
int - ดัชนีฐานศูนย์ของการพบครั้งแรกของค่าใน CollectionBase ทั้งหมด หากพบ; มิฉะนั้น, -1

### remove(IChartSeries value) {#remove-com.aspose.slides.IChartSeries-}
```
public abstract void remove(IChartSeries value)
```

ลบค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartSeries](../../com.aspose.slides/ichartseries) | ค่าที่ระบุ

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนี

### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกองค์ประกอบ (รวมถึงสไตล์แผนภูมิ) จากคอลเลกชัน