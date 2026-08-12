---
title: Flatten()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ทำให้เส้นโค้งแต่ละเส้นในพาธแบนโดยแปลงเป็นชุดของเส้นตรงต่อเนื่อง ค่า flatness ที่ใช้คือ 0.25
type: docs
weight: 391
url: /th/system.drawing.drawing2d/graphicspath/flatten/
---
## GraphicsPath::Flatten() เมธอด

ทำให้เส้นโค้งแต่ละเส้นในพาธแบนโดยแปลงเป็นชุดของเส้นตรงต่อเนื่อง ค่า flatness ที่ใช้คือ 0.25

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten()
```

## GraphicsPath::Flatten(const MatrixPtr\&) เมธอด

ทำให้เส้นโค้งแต่ละเส้นในพาธแบนโดยแปลงเป็นชุดของเส้นตรงต่อเนื่อง ค่า flatness ที่ใช้คือ 0.25

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | เมทริกซ์การแปลงที่จะใช้กับเส้นทางก่อนทำให้แบน |

## GraphicsPath::Flatten(const MatrixPtr\&, float) เมธอด

ทำให้เส้นโค้งแต่ละเส้นในพาธแบนโดยแปลงเป็นชุดของเส้นตรงต่อเนื่อง

```cpp
void System::Drawing::Drawing2D::GraphicsPath::Flatten(const MatrixPtr &matrix, float flatness)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| matrix | const [MatrixPtr](../../matrixptr/)\& | เมทริกซ์การแปลงที่จะใช้กับเส้นทางก่อนทำให้แบน |
| flatness | **float** | ระบุค่าความคลาดเคลื่อนสูงสุดที่อนุญาตระหว่างเส้นโค้งและการประมาณค่าให้แบน |

## ดูเพิ่มเติม

* Typedef [MatrixPtr](../../matrixptr/)
* คลาส [GraphicsPath](../)
* เนมสเปซ [System::Drawing::Drawing2D](../../)
* ไลบรารี [Aspose.Slides](../../../)