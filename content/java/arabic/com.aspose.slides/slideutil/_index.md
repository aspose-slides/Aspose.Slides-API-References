---
title: SlideUtil
second_title: مرجع API لـ Aspose.Slides للغة جافا
description: توفر طرقًا تساعد في البحث عن الأشكال والنص في العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/slideutil/
---
**الوراثة:**
java.lang.Object
```
public class SlideUtil
```

توفر طرقًا تساعد في البحث عن الأشكال والنص في العرض التقديمي.

## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | العثور على الشكل عبر النص البديل في عرض تقديمي PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | العثور على الشكل عبر النص البديل على شريحة في عرض تقديمي PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | يبحث عن جميع الأشكال على الشريحة المحددة التي تطابق نوع العنصر النائب المحدد. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | يغيّر موضع جميع الأشكال على الشريحة. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | يغيّر موضع الأشكال المحددة على الشريحة. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | يغيّر موضع جميع الأشكال داخل مجموعة الأشكال. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | يغيّر موضع الأشكال المحددة داخل مجموعة الأشكال. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | يجد ويستبدل النص في العرض التقديمي بالتنسيق المحدد |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | يجد ويستبدل النص في العرض التقديمي بالتنسيق المحدد |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | يُرجع جميع إطارات النص على شريحة في عرض تقديمي PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | يُرجع جميع إطارات النص على الشريحة المحددة التي تحتوي على النص المعطى. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | يُرجع جميع إطارات النص في عرض تقديمي PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | يُحوِّل تنسيق ملف المصدر إلى [SaveFormat](../../com.aspose.slides/saveformat) المقابل. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

العثور على الشكل عبر النص البديل في عرض تقديمي PPTX.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | العرض الممسوح. |
| altText | java.lang.String | النص البديل للشكل. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - Shape أو null.

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

العثور على الشكل عبر النص البديل على شريحة في عرض تقديمي PPTX.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | الشريحة الممسوحة. |
| altText | java.lang.String | النص البديل للشكل. |

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape) - Shape أو null.

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

يبحث عن جميع الأشكال على الشريحة المحددة التي تطابق نوع العنصر النائب المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | الشريحة التي تُبحث فيها الأشكال. |
| placeholderType | byte | نوع العنصر النائب لتصفية الأشكال حسبه. |

**الإرجاع:**
com.aspose.slides.IShape[] - مصفوفة من كائنات [IShape](../../com.aspose.slides/ishape) التي تطابق نوع العنصر النائب المحدد.

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

يغيّر موضع جميع الأشكال على الشريحة. يصفّ الأشكال إلى الهوامش أو حافة الشريحة أو يصفّها بالنسبة لبعضها البعض.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| alignmentType | int | يحدّد أي نوع من المحاذاة سيتم تطبيقه. |
| alignToSlide | boolean | إذا كان true، سيتم محاذاة الأشكال بالنسبة إلى حواف الشريحة. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | الشريحة الأصلية. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

يغيّر موضع الأشكال المحددة على الشريحة. يصفّ الأشكال إلى الهوامش أو حافة الشريحة أو يصفّها بالنسبة لبعضها البعض.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| alignmentType | int | يحدّد أي نوع من المحاذاة سيتم تطبيقه. |
| alignToSlide | boolean | إذا كان true، سيتم محاذاة الأشكال بالنسبة إلى حواف الشريحة. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | الشريحة الأصلية. |
| shapeIndexes | int[] | فهارس الأشكال التي سيتم محاذاتها. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

يغيّر موضع جميع الأشكال داخل مجموعة الأشكال. يصفّ الأشكال إلى الهوامش أو حافة الشريحة أو يصفّها بالنسبة لبعضها البعض.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| alignmentType | int | يحدّد أي نوع من المحاذاة سيتم تطبيقه. |
| alignToSlide | boolean | إذا كان true، سيتم محاذاة الأشكال بالنسبة إلى حواف الشريحة. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | مجموعة الأشكال الأصلية. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

يغيّر موضع الأشكال المحددة داخل مجموعة الأشكال. يصفّ الأشكال إلى الهوامش أو حافة الشريحة أو يصفّها بالنسبة لبعضها البعض.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| alignmentType | int | يحدّد أي نوع من المحاذاة سيتم تطبيقه. |
| alignToSlide | boolean | إذا كان true، سيتم محاذاة الأشكال بالنسبة إلى حواف الشريحة. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | مجموعة الأشكال الأصلية. |
| shapeIndexes | int[] | فهارس الأشكال التي سيتم محاذاتها. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

يجد ويستبدل النص في العرض التقديمي بالتنسيق المحدد

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض الممسوح. |
| withMasters | boolean | يحدّد ما إذا كان يجب مسح الشرائح الرئيسية. |
| find | java.lang.String | قيمة النص للبحث عنها. |
| replace | java.lang.String | قيمة النص لاستبدالها. حرف من السلسلة التي تم العثور عليها |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

يجد ويستبدل النص في العرض التقديمي بالتنسيق المحدد

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | العرض الممسوح. |
| withMasters | boolean | يحدّد ما إذا كان يجب مسح الشرائح الرئيسية. |
| find | java.lang.String | قيمة النص للبحث عنها. |
| replace | java.lang.String | قيمة النص لاستبداله. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | تنسيق الجزء النصي المستبدل. إذا كان null فسيُستخدم تنسيق الحرف الأول من السلسلة التي تم العثور عليها |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

يُرجع جميع إطارات النص على شريحة في عرض تقديمي PPTX.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | الشريحة الممسوحة. |

**الإرجاع:**
com.aspose.slides.ITextFrame[] - مصفوفة من كائنات [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

يُرجع جميع إطارات النص على الشريحة المحددة التي تحتوي على النص المعطى.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | الشريحة للبحث. |
| text | java.lang.String | النص المراد البحث عنه داخل إطارات النص. |
| checkPlaceholderText | boolean | يحدد ما إذا كان يجب تضمين إطارات النص الفارغة التي يحتوي نص العنصر النائب فيها على النص البحث. |

**الإرجاع:**
com.aspose.slides.ITextFrame[] - مصفوفة من كائنات [ITextFrame](../../com.aspose.slides/itextframe) التي تحتوي على النص المحدد.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

يُرجع جميع إطارات النص في عرض تقديمي PPTX.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | العرض الممسوح. |
| withMasters | boolean | يحدّد ما إذا كان يجب مسح الشرائح الرئيسية. |

**الإرجاع:**
com.aspose.slides.ITextFrame[] - مصفوفة من كائنات [TextFrame](../../com.aspose.slides/textframe).

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

يحوِّل تنسيق ملف المصدر إلى [SaveFormat](../../com.aspose.slides/saveformat) المقابل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| format | int | تنسيق ملف المصدر. |

**الإرجاع:**
int - القيمة المقابلة لـ [SaveFormat](../../com.aspose.slides/saveformat).