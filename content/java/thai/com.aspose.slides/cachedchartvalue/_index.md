---
title: CachedChartValue
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นค่ากราฟที่แคชไว้ เช่น X Y ขนาดฟองหรือค่าหลัก
type: docs
url: /th/com.aspose.slides/cachedchartvalue/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

เป็นค่ากราฟที่แคชไว้ (เช่น X, Y, ขนาดฟองหรือค่าหลัก).
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [toString()](#toString--) | Returns a string representation of the cached value. |
| [toDouble()](#toDouble--) | Converts the cached value to a double. |
| [getData()](#getData--) | Gets the cached data object. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


ส่งกลับการแสดงผลเป็นสตริงของค่าที่แคชไว้.

**คืนค่า:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


แปลงค่าที่แคชไว้เป็น double.

**คืนค่า:**
double - การแสดงผลเชิงตัวเลข, หรือ Double.NaN หาก Data (\#getData.getData/\#setData(Object).setData(Object)) เป็น null หรือไม่สามารถแปลงเป็น double ได้.
### getData() {#getData--}
```
public final Object getData()
```


ดึงออบเจกต์ข้อมูลที่แคชไว้. อ่านอย่างเดียว  Object .

**คืนค่า:**
java.lang.Object