---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a cached chart value e.g. X Y bubble size or the main value.
type: docs
url: /th/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

แสดงค่าชาร์ตที่แคชไว้ (เช่น X, Y, ขนาดบับเบิล หรือค่าหลัก).
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getData()](#getData--) | รับวัตถุข้อมูลที่แคชไว้ |
| [toDouble()](#toDouble--) | แปลงค่าที่แคชเป็นประเภท double |
### getData() {#getData--}
```
public abstract Object getData()
```


รับวัตถุข้อมูลที่แคชไว้. อ่านอย่างเดียว  Object .

**คืนค่า:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


แปลงค่าที่แคชเป็นประเภท double.

**คืนค่า:**
double - การแสดงผลเชิงตัวเลข, หรือ Double.NaN หาก Data (\#getData.getData) เป็น null หรือไม่สามารถแปลงเป็น double ได้.