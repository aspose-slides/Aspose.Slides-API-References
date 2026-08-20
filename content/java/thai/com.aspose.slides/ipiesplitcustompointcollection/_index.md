---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: เป็นตัวแทนของคอลเลกชันของจุดที่ต้องวาดในพายหรือแท่งที่สองบนแผนภูมิ bar-of-pie หรือ pie-of-pie ที่มีการแยกแบบกำหนดเอง
type: docs
url: /th/com.aspose.slides/ipiesplitcustompointcollection/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

แทนที่คอลเลกชันของจุดที่ควรวาดในไพสองหรือแท่งที่สองบนแผนภูมิ bar-of-pie หรือ pie-of-pie ที่มีการแยกแบบกำหนดเอง
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนจุดข้อมูลแผนภูมิตามดัชนี. |
| [add(int dataPointIndex)](#add-int-) | เพิ่มจุดข้อมูลโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่. |
| [remove(int dataPointIndex)](#remove-int-) | ลบรายการจากคอลเลกชันโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

ส่งคืนจุดข้อมูลแผนภูมิตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของจุดข้อมูล. |

**ผลลัพธ์:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลแผนภูมิ.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

เพิ่มจุดข้อมูลโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dataPointIndex | int | ดัชนีของจุดข้อมูลในคอลเลกชันจุดของซีรีส์แม่. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

ลบรายการจากคอลเลกชันโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dataPointIndex | int | ดัชนีของจุดข้อมูลในคอลเลกชันจุดของซีรีส์แม่.. |