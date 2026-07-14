---
title: IMathArrayFactory
second_title: Aspose.Slides for Android via Java API Reference
description: อนุญาตให้สร้างอาเรย์คณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

อนุญาตให้สร้างอาเรย์คณิตศาสตร์

--------------------

เพื่อความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | สร้างอาเรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุลงในอาเรย์ |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | สร้างอาเรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุหลายรายการลงในอาเรย์ |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```

สร้างอาเรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุลงในอาเรย์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะวางในอาเรย์ |

**ค่าที่ส่งกลับ:**
[IMathArray](../../com.aspose.slides/imatharray) - อาเรย์คณิตศาสตร์ใหม่
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```

สร้างอาเรย์คณิตศาสตร์และวางองค์ประกอบที่ระบุหลายรายการลงในอาเรย์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | องค์ประกอบคณิตศาสตร์ที่จะวางในอาเรย์ |

**ค่าที่ส่งกลับ:**
[IMathArray](../../com.aspose.slides/imatharray) - อาเรย์คณิตศาสตร์ใหม่