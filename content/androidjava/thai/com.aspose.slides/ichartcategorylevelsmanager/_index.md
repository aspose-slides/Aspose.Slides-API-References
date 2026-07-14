---
title: IChartCategoryLevelsManager
second_title: Aspose.Slides for Android via Java API Reference
description: คอนเทนเนอร์ที่จัดการค่าของระดับหมวดหมู่แผนภูมิ
type: docs
url: /th/com.aspose.slides/ichartcategorylevelsmanager/
---```
public interface IChartCategoryLevelsManager
```

คอนเทนเนอร์ที่จัดการค่าของระดับหมวดหมู่แผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | ส่งคืนอ็อบเจ็กต์ IChartDataCell สำหรับระดับที่กำหนด |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | กำหนดรายการการจัดกลุ่มสำหรับระดับที่กำหนด |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | ลบรายการการจัดกลุ่มสำหรับระดับที่กำหนด |
### get_Item(int level) {#get-Item-int-}
```
public abstract IChartDataCell get_Item(int level)
```

ส่งคืนอ็อบเจ็กต์ IChartDataCell สำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| level | int |  |

**ผลลัพธ์:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public abstract void setGroupingItem(int level, Object value)
```

กำหนดรายการการจัดกลุ่มสำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| level | int | ระดับหมวดหมู่แบบ int |
| value | java.lang.Object | อ็อบเจ็กต์รายการจัดกลุ่ม |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public abstract void deleteGroupingItem(int level)
```

ลบรายการการจัดกลุ่มสำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| level | int | ระดับหมวดหมู่แบบ int |