---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides for Java API Reference
description: คอนเทนเนอร์ของระดับข้อมูลจุด.
type: docs
url: /th/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

คอนเทนเนอร์ของระดับข้อมูลจุด ใช้กับซีรีส์ Treeamp และ Sunburst การจัดทำดัชนีระดับข้อมูลจุดเริ่มต้นจากศูนย์.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataPointLevel object for defined level. |
| [getCount()](#getCount--) | Returns data point levels count. |

### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

คืนค่า IChartDataPointLevel อ็อบเจกต์สำหรับระดับที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| level | int |  |

**ผลลัพธ์:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)

### getCount() {#getCount--}
```
public abstract int getCount()
```

คืนค่าจำนวนระดับข้อมูลจุด.

**ผลลัพธ์:**
int