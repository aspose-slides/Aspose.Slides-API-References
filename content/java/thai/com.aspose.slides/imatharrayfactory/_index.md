---
title: IMathArrayFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้างอาร์เรย์คณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

อนุญาตให้สร้างอาร์เรย์คณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | สร้างอาร์เรย์คณิตศาสตร์และใส่องค์ประกอบที่ระบุลงในอาร์เรย์ |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | สร้างอาร์เรย์คณิตศาสตร์และใส่องค์ประกอบที่ระบุหลายรายการลงในอาร์เรย์ |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```

สร้างอาร์เรย์คณิตศาสตร์และใส่องค์ประกอบที่ระบุลงในอาร์เรย์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่ใส่ลงในอาร์เรย์ |

**คืนค่า:**
[IMathArray](../../com.aspose.slides/imatharray) - อาร์เรย์คณิตศาสตร์ใหม่
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```

สร้างอาร์เรย์คณิตศาสตร์และใส่องค์ประกอบที่ระบุหลายรายการลงในอาร์เรย์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | องค์ประกอบคณิตศาสตร์หลายรายการที่ใส่ลงในอาร์เรย์ |

**คืนค่า:**
[IMathArray](../../com.aspose.slides/imatharray) - อาร์เรย์คณิตศาสตร์ใหม่