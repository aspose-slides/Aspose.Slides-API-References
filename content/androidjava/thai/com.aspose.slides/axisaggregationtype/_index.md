---
title: AxisAggregationType
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: แสดงประเภทการรวมข้อมูลของแกนหมวดหมู่.
type: docs
url: /th/com.aspose.slides/axisaggregationtype/
---
**การสืบทอด:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AxisAggregationType extends System.Enum
```

แสดงประเภทการรวมข้อมูลของแกนหมวดหมู่ ใช้เฉพาะกับชุดข้อมูล Histogram หรือ HistogramPareto เท่านั้น.
## ฟิลด์

| ฟิลด์ | รายละเอียด |
| --- | --- |
| [ByCategory](#ByCategory) | รวมตามหมวดหมู่ |
| [Automatic](#Automatic) | รวมหมวดหมู่โดยอัตโนมัติ. |
| [ByBinWidth](#ByBinWidth) | รวมหมวดหมู่โดยใช้ความกว้างของ bin. |
| [ByNumberOfBins](#ByNumberOfBins) | รวมหมวดหมู่โดยใช้จำนวน bin. |
### ตามหมวดหมู่ {#ByCategory}
```
public static final int ByCategory
```

รวมตามหมวดหมู่

### อัตโนมัติ {#Automatic}
```
public static final int Automatic
```

รวมหมวดหมู่โดยอัตโนมัติ.

### ตามความกว้างของ Bin {#ByBinWidth}
```
public static final int ByBinWidth
```

รวมหมวดหมู่โดยใช้ความกว้างของ Bin. ต้องตั้งค่า Property IAxis.BinWidth.

### ตามจำนวน Bin {#ByNumberOfBins}
```
public static final int ByNumberOfBins
```

รวมหมวดหมู่โดยใช้จำนวนของ Bin. ต้องตั้งค่า Property IAxis.NumberOfBins.