---
title: IChartDataPointLevelsManager
second_title: Aspose.Slides สำหรับ Android via Java API Reference
description: คอนเทนเนอร์ของระดับจุดข้อมูล.
type: docs
url: /th/com.aspose.slides/ichartdatapointlevelsmanager/
---```
public interface IChartDataPointLevelsManager
```

คอนเทนเนอร์ของระดับจุดข้อมูล ใช้สำหรับ Treeamp และ Sunburst การจัดทำดัชนีระดับจุดข้อมูลเริ่มที่ศูนย์
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | Returns IChartDataPointLevel object for defined level. |
| [getCount()](#getCount--) | Returns data point levels count. |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataPointLevel get_Item(int level)
```

ส่งคืนอ็อบเจ็กต์ IChartDataPointLevel สำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| level | int |  |

**คืนค่า:**
[IChartDataPointLevel](../../com.aspose.slides/ichartdatapointlevel)
### getCount() {#getCount--}
```
public abstract int getCount()
```

ส่งคืนจำนวนระดับของจุดข้อมูล

**คืนค่า:**
int