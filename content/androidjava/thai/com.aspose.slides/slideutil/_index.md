---
title: SlideUtil
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้เมธอดที่ช่วยค้นหารูปและข้อความในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/slideutil/
---
**การสืบทอด:**
java.lang.Object
```
public class SlideUtil
```

ให้เมธอดที่ช่วยค้นหารูปและข้อความในงานนำเสนอ

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | ค้นหารูปโดยข้อความแทนที่ในงานนำเสนอ PPTX |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | ค้นหารูปโดยข้อความแทนที่บนสไลด์ในงานนำเสนอ PPTX |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | ค้นหารูปทั้งหมดบนสไลด์ที่ระบุที่ตรงกับประเภท placeholder ที่กำหนด |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | เปลี่ยนตำแหน่งของรูปทั้งหมดบนสไลด์ |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | เปลี่ยนตำแหน่งของรูปที่เลือกบนสไลด์ |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | เปลี่ยนตำแหน่งของรูปทั้งหมดภายใน group shape |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | เปลี่ยนตำแหน่งของรูปที่เลือกภายใน group shape |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | ค้นหาและแทนที่ข้อความในงานนำเสนอด้วยรูปแบบที่กำหนด |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | ค้นหาและแทนที่ข้อความในงานนำเสนอด้วยรูปแบบที่กำหนด |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | ส่งคืน text frames ทั้งหมดบนสไลด์ในงานนำเสนอ PPTX |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | ส่งคืน text frames ทั้งหมดบนสไลด์ที่ระบุที่มีข้อความที่กำหนด |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | ส่งคืน text frames ทั้งหมดในงานนำเสนอ PPTX |
| [toSaveFormat(int format)](#toSaveFormat-int-) | แปลงรูปแบบไฟล์ต้นฉบับเป็น [SaveFormat](../../com.aspose.slides/saveformat) ที่สอดคล้อง |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

ค้นหารูปโดยข้อความแทนที่ในงานนำเสนอ PPTX

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่สแกน |
| altText | java.lang.String | ข้อความแทนที่ของรูป |

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape) - Shape or null.

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

ค้นหารูปโดยข้อความแทนที่บนสไลด์ในงานนำเสนอ PPTX

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | สไลด์ที่สแกน |
| altText | java.lang.String | ข้อความแทนที่ของรูป |

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape) - Shape or null.

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

ค้นหารูปทั้งหมดบนสไลด์ที่ระบุที่ตรงกับประเภท placeholder ที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | สไลด์ที่ใช้ค้นหารูป |
| placeholderType | byte | ประเภท placeholder ที่ใช้กรองรูป |

**คืนค่า:**
com.aspose.slides.IShape[] - อาเรย์ของวัตถุ [IShape](../../com.aspose.slides/ishape) ที่ตรงกับประเภท placeholder ที่ระบุ

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

เปลี่ยนตำแหน่งของรูปทั้งหมดบนสไลด์ จัดแนวรูปไปยังขอบหรือระยะของสไลด์หรือจัดแนวสัมพันธ์กัน

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alignmentType | int | กำหนดว่าประเภทการจัดแนวใดจะถูกใช้ |
| alignToSlide | boolean | หากเป็น true รูปจะถูกจัดแนวสัมพันธ์กับขอบสไลด์ |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | สไลด์แม่ |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

เปลี่ยนตำแหน่งของรูปที่เลือกบนสไลด์ จัดแนวรูปไปยังขอบหรือระยะของสไลด์หรือจัดแนวสัมพันธ์กัน

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alignmentType | int | กำหนดว่าประเภทการจัดแนวใดจะถูกใช้ |
| alignToSlide | boolean | หากเป็น true รูปจะถูกจัดแนวสัมพันธ์กับขอบสไลด์ |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | สไลด์แม่ |
| shapeIndexes | int[] | ดัชนีของรูปที่ต้องการจัดแนว |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

เปลี่ยนตำแหน่งของรูปทั้งหมดภายใน group shape จัดแนวรูปไปยังขอบหรือระยะของสไลด์หรือจัดแนวสัมพันธ์กัน

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alignmentType | int | กำหนดว่าประเภทการจัดแนวใดจะถูกใช้ |
| alignToSlide | boolean | หากเป็น true รูปจะถูกจัดแนวสัมพันธ์กับขอบสไลด์ |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | group shape แม่ |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

เปลี่ยนตำแหน่งของรูปที่เลือกภายใน group shape จัดแนวรูปไปยังขอบหรือระยะของสไลด์หรือจัดแนวสัมพันธ์กัน

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alignmentType | int | กำหนดว่าประเภทการจัดแนวใดจะถูกใช้ |
| alignToSlide | boolean | หากเป็น true รูปจะถูกจัดแนวสัมพันธ์กับขอบสไลด์ |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | group shape แม่ |
| shapeIndexes | int[] | ดัชนีของรูปที่ต้องการจัดแนว |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

ค้นหาและแทนที่ข้อความในงานนำเสนอด้วยรูปแบบที่กำหนด

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่สแกน |
| withMasters | boolean | กำหนดว่าจะสแกนสไลด์แม่หรือไม่ |
| find | java.lang.String | ค่าข้อความที่จะค้นหา |
| replace | java.lang.String | ค่าข้อความที่จะแทนที่ ตัวอักษรของสตริงที่พบ |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

ค้นหาและแทนที่ข้อความในงานนำเสนอด้วยรูปแบบที่กำหนด

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่สแกน |
| withMasters | boolean | กำหนดว่าจะสแกนสไลด์แม่หรือไม่ |
| find | java.lang.String | ค่าข้อความที่จะค้นหา |
| replace | java.lang.String | ค่าข้อความที่จะแทนที่ |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | รูปแบบสำหรับแทนที่ส่วนข้อความ หากเป็น null จะใช้รูปแบบของอักขระแรกของสตริงที่พบ |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

ส่งคืน text frames ทั้งหมดบนสไลด์ในงานนำเสนอ PPTX

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | สไลด์ที่สแกน |

**คืนค่า:**
com.aspose.slides.ITextFrame[] - อาเรย์ของวัตถุ [TextFrame](../../com.aspose.slides/textframe)

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

ส่งคืน text frames ทั้งหมดบนสไลด์ที่ระบุที่มีข้อความที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | สไลด์ที่ใช้ค้นหา |
| text | java.lang.String | ข้อความที่ต้องการค้นหาใน text frames |
| checkPlaceholderText | boolean | ระบุว่าจะรวม text frames ที่ว่างเปล่าแต่ข้อความ placeholder มีข้อความที่ค้นหาหรือไม่ |

**คืนค่า:**
com.aspose.slides.ITextFrame[] - อาเรย์ของวัตถุ [ITextFrame](../../com.aspose.slides/itextframe) ที่มีข้อความที่ระบุ

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

ส่งคืน text frames ทั้งหมดในงานนำเสนอ PPTX

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | งานนำเสนอที่สแกน |
| withMasters | boolean | กำหนดว่าจะสแกนสไลด์แม่หรือไม่ |

**คืนค่า:**
com.aspose.slides.ITextFrame[] - อาเรย์ของวัตถุ [TextFrame](../../com.aspose.slides/textframe)

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

แปลงรูปแบบไฟล์ต้นฉบับเป็น [SaveFormat](../../com.aspose.slides/saveformat)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| format | int | รูปแบบไฟล์ต้นฉบับ |

**คืนค่า:**
int - ค่าที่สอดคล้องกับ [SaveFormat](../../com.aspose.slides/saveformat)