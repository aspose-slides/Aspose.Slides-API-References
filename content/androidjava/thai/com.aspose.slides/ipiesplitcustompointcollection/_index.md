---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงคอลเลกชันของจุดที่ต้องวาดในพายหรือแท่งที่สองบนแผนภูมิบาร์-ออฟ-พายหรือพาย-ออฟ-พายที่มีการแยกแบบกำหนดเอง.
type: docs
url: /th/com.aspose.slides/ipiesplitcustompointcollection/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

เป็นคอลเลกชันของจุดที่ต้องวาดในพายหรือแท่งที่สองบนแผนภูมิบาร์-ออฟ-พายหรือพาย-ออฟ-พายที่มีการแยกแบบกำหนดเอง
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าจุดข้อมูลแผนภูมิตามดัชนี. |
| [add(int dataPointIndex)](#add-int-) | เพิ่มจุดข้อมูลโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่. |
| [remove(int dataPointIndex)](#remove-int-) | ลบรายการจากคอลเลกชันโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```

คืนค่าจุดข้อมูลแผนภูมิตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของจุดข้อมูล. |

**คืนค่า:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - จุดข้อมูลแผนภูมิ.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```

เพิ่มจุดข้อมูลโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dataPointIndex | int | ดัชนีของจุดข้อมูลในคอลเลกชันจุดของซีรีส์แม่. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```

ลบรายการจากคอลเลกชันโดยใช้ดัชนีของมันในคอลเลกชันจุดของซีรีส์แม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dataPointIndex | int | ดัชนีของจุดข้อมูลในคอลเลกชันจุดของซีรีส์แม่.. |