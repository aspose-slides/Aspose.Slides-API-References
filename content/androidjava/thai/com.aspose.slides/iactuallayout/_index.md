---
title: IActualLayout
second_title: Aspose.Slides for Android via Java API Reference
description: ระบุตำแหน่งที่แท้จริงขององค์ประกอบแผนภูมิ.
type: docs
url: /th/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

ระบุตำแหน่งที่แท้จริงขององค์ประกอบแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getActualX()](#getActualX--) | ระบุตำแหน่งจริงของแกน X (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualY()](#getActualY--) | ระบุตำแหน่งจริงด้านบนขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. |
| [getActualWidth()](#getActualWidth--) | ระบุตำแหน่งจริงความกว้างขององค์ประกอบแผนภูมิ. |
| [getActualHeight()](#getActualHeight--) | ระบุตำแหน่งจริงความสูงขององค์ประกอบแผนภูมิ. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


ระบุตำแหน่งจริงของแกน X (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าที่แท้จริง. อ่านค่า float.

**คืนค่า:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


ระบุตำแหน่งจริงด้านบนขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าที่แท้จริง. อ่านค่า float.

**คืนค่า:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


ระบุตำแหน่งจริงความกว้างขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าที่แท้จริง. อ่านค่า float.

**คืนค่า:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


ระบุตำแหน่งจริงความสูงขององค์ประกอบแผนภูมิ. เรียกเมธอด IChart.ValidateChartLayout() ก่อนเพื่อรับค่าที่แท้จริง. อ่านค่า float.

**คืนค่า:**
float