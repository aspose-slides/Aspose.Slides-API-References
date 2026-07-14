---
title: ChartCategoryLevelsManager
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: คอนเทนเนอร์ที่จัดการค่าของระดับหมวดหมู่ของแผนภูมิ
type: docs
url: /th/com.aspose.slides/chartcategorylevelsmanager/
---
**สืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)  
```
public class ChartCategoryLevelsManager implements IChartCategoryLevelsManager
```

คอนเทนเนอร์ที่จัดการค่าของระดับหมวดหมู่ของแผนภูมิ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int level)](#get-Item-int-) | ส่งคืนอ็อบเจ็กต์ IChartDataCell สำหรับระดับที่กำหนด |
| [setGroupingItem(int level, Object value)](#setGroupingItem-int-java.lang.Object-) | ตั้งค่าไอเท็มการจัดกลุ่มสำหรับระดับที่กำหนด |
| [deleteGroupingItem(int level)](#deleteGroupingItem-int-) | ลบไอเท็มการจัดกลุ่มสำหรับระดับที่กำหนด |
### get_Item(int level) {#get-Item-int-}
```
public final IChartDataCell get_Item(int level)
```

ส่งคืนอ็อบเจ็กต์ IChartDataCell สำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| level | int |  |

**ผลลัพธ์:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setGroupingItem(int level, Object value) {#setGroupingItem-int-java.lang.Object-}
```
public final void setGroupingItem(int level, Object value)
```

ตั้งค่าไอเท็มการจัดกลุ่มสำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| level | int |  |
| value | java.lang.Object |  |

### deleteGroupingItem(int level) {#deleteGroupingItem-int-}
```
public final void deleteGroupingItem(int level)
```

ลบไอเท็มการจัดกลุ่มสำหรับระดับที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| level | int |  |