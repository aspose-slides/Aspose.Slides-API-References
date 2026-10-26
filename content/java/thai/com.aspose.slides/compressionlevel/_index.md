---
title: CompressionLevel
second_title: Aspose.Slides สำหรับ Java API Reference
description: ระบุระดับการบีบอัด ZIP สำหรับไฟล์ OpenXML
type: docs
url: /th/com.aspose.slides/compressionlevel/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionLevel extends System.Enum
```

ระบุระดับการบีบอัด ZIP สำหรับไฟล์ OpenXML ระดับที่สูงให้การบีบอัดที่ดีขึ้นแต่มีค่าใช้จ่ายคือการประมวลผลที่ช้าลง

## Fields

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| [None](#None) | ไม่มีการบีบอัดใด ๆ ถูกนำมาใช้ |
| [Level1](#Level1) | การบีบอัดที่เร็วที่สุดพร้อมอัตราการบีบอัดที่ต่ำที่สุด |
| [Level2](#Level2) | การบีบอัดที่เร็วกว่าโดยมีอัตราการบีบอัดที่ดีกว่าเล็กน้อยเมื่อเทียบกับ [Level1](../../com.aspose.slides/compressionlevel\#Level1) |
| [Level3](#Level3) | ให้การบีบอัดที่ดีกว่า [Level2](../../com.aspose.slides/compressionlevel\#Level2) โดยมีผลกระทบต่อประสิทธิภาพในระดับปานกลาง |
| [Level4](#Level4) | ให้การบีบอัดที่ดีกว่า [Level3](../../com.aspose.slides/compressionlevel\#Level3) |
| [Level5](#Level5) | ให้การบีบอัดที่พัฒนาขึ้นเมื่อเทียบกับ [Level4](../../com.aspose.slides/compressionlevel\#Level4) โดยใช้เวลาประมวลผลเพิ่มเติม |
| [Level6](#Level6) | การบีบอัดมาตรฐานที่ให้สมดุลที่ดีระหว่างความเร็วในการบีบอัดและขนาดไฟล์ |
| [Level7](#Level7) | ให้การบีบอัดที่สูงกว่า [Level6](../../com.aspose.slides/compressionlevel\#Level6) โดยมีการประมวลผลที่ช้าลง |
| [Level8](#Level8) | ให้การบีบอัดที่สูงกว่า [Level7](../../com.aspose.slides/compressionlevel\#Level7) |
| [Level9](#Level9) | การบีบอัดสูงสุด |

### None {#None}
```
public static final int None
```

ไม่มีการบีบอัดใด ๆ ถูกนำมาใช้ ไฟล์จะถูกเก็บไว้ตามเดิม

### Level1 {#Level1}
```
public static final int Level1
```

การบีบอัดที่เร็วที่สุดพร้อมอัตราการบีบอัดที่ต่ำที่สุด

### Level2 {#Level2}
```
public static final int Level2
```

การบีบอัดที่เร็วกว่าโดยมีอัตราการบีบอัดที่ดีกว่าเล็กน้อยเมื่อเทียบกับ [Level1](../../com.aspose.slides/compressionlevel\#Level1)

### Level3 {#Level3}
```
public static final int Level3
```

ให้การบีบอัดที่ดีกว่า [Level2](../../com.aspose.slides/compressionlevel\#Level2) โดยมีผลกระทบต่อประสิทธิภาพในระดับปานกลาง

### Level4 {#Level4}
```
public static final int Level4
```

ให้การบีบอัดที่ดีกว่า [Level3](../../com.aspose.slides/compressionlevel\#Level3)

### Level5 {#Level5}
```
public static final int Level5
```

ให้การบีบอัดที่พัฒนาขึ้นเมื่อเทียบกับ [Level4](../../com.aspose.slides/compressionlevel\#Level4) โดยใช้เวลาประมวลผลเพิ่มเติม

### Level6 {#Level6}
```
public static final int Level6
```

การบีบอัดมาตรฐานที่ให้สมดุลที่ดีระหว่างความเร็วในการบีบอัดและขนาดไฟล์ ระดับการบีบอัดเริ่มต้น

### Level7 {#Level7}
```
public static final int Level7
```

ให้การบีบอัดที่สูงกว่า [Level6](../../com.aspose.slides/compressionlevel\#Level6) โดยมีการประมวลผลที่ช้าลง

### Level8 {#Level8}
```
public static final int Level8
```

ให้การบีบอัดที่สูงกว่า [Level7](../../com.aspose.slides/compressionlevel\#Level7)

### Level9 {#Level9}
```
public static final int Level9
```

การบีบอัดสูงสุด ผลิตไฟล์ที่มีขนาดเล็กที่สุดด้วยความเร็วการประมวลผลที่ช้าลงที่สุด