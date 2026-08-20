---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Java API Reference
description: Managed container of the values of the chart category levels.
type: docs
url: /th/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

คอนเทนเนอร์ที่จัดการค่าของระดับหมวดหมู่แผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | คืนค่าอ็อบเจกต์ IChartDataCell สำหรับระดับที่กำหนด |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | ตั้งค่ารายการจัดกลุ่มสำหรับระดับที่กำหนด |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | ลบรายการจัดกลุ่มสำหรับระดับที่กำหนด |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

คืนค่าอ็อบเจกต์ IChartDataCell สำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| level | int |  |

**ผลลัพธ์:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

ตั้งค่ารายการจัดกลุ่มสำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| level | int | ระดับประเภท int |
| value | java.lang.Object | อ็อบเจกต์รายการจัดกลุ่ม |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

ลบรายการจัดกลุ่มสำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| level | int | ระดับประเภท int |