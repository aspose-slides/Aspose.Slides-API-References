---
title: SlideUtil
second_title: Aspose.Slides जावा के लिए API संदर्भ
description: ऐसे मेथड प्रदान करता है जो प्रस्तुति में आकार और पाठ को खोजने में मदद करते हैं।
type: docs
url: /hi/com.aspose.slides/slideutil/
---
**विरासत:**
java.lang.Object
```
public class SlideUtil
```

ऐसे मेथड प्रदान करता है जो प्रस्तुति में आकार और पाठ को खोजने में मदद करते हैं।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## मेथड

| मेथड | विवरण |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | PPTX प्रस्तुति में वैकल्पिक टेक्स्ट द्वारा आकार खोजें। |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | PPTX प्रस्तुति में स्लाइड पर वैकल्पिक टेक्स्ट द्वारा आकार खोजें। |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | निर्दिष्ट स्लाइड पर सभी आकारों को खोजता है जो दिए गए प्लेसहोल्डर प्रकार से मेल खाते हैं। |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | स्लाइड पर सभी आकारों की स्थिति बदलता है। |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | स्लाइड पर चयनित आकारों की स्थिति बदलता है। |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | समूह आकार के भीतर सभी आकारों की स्थिति बदलता है। |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | समूह आकार के भीतर चयनित आकारों की स्थिति बदलता है। |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | प्रस्तुति में दिए गए स्वरूप के साथ पाठ को खोजता और बदलता है। |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | प्रस्तुति में दिए गए स्वरूप के साथ पाठ को खोजता और बदलता है। |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | PPTX प्रस्तुति में स्लाइड पर सभी टेक्स्ट फ़्रेम लौटाता है। |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | निर्दिष्ट स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है जो दिए गए पाठ को शामिल करते हैं। |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | PPTX प्रस्तुति में सभी टेक्स्ट फ्रेम लौटाता है। |
| [toSaveFormat(int format)](#toSaveFormat-int-) | स्रोत फ़ाइल फ़ॉर्मेट को संबंधित [SaveFormat](../../com.aspose.slides/saveformat) में बदलता है। |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

PPTX प्रस्तुति में वैकल्पिक टेक्स्ट द्वारा आकार खोजें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | स्कैन की गई प्रस्तुति। |
| altText | java.lang.String | आकार का वैकल्पिक पाठ। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - आकार या null।

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

PPTX प्रस्तुति में स्लाइड पर वैकल्पिक पाठ द्वारा आकार खोजें।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | स्कैन किया हुआ स्लाइड। |
| altText | java.lang.String | आकार का वैकल्पिक पाठ। |

**रिटर्न:**
[IShape](../../com.aspose.slides/ishape) - आकार या null।

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

निर्दिष्ट स्लाइड पर सभी आकारों को खोजता है जो दिए गए प्लेसहोल्डर प्रकार से मेल खाते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | आकारों की खोज के लिए स्लाइड। |
| placeholderType | byte | आकारों को फ़िल्टर करने के लिए प्लेसहोल्डर का प्रकार। |

**रिटर्न:**
com.aspose.slides.IShape[] - निर्दिष्ट प्लेसहोल्डर प्रकार से मेल खाने वाले [IShape](../../com.aspose.slides/ishape) वस्तुओं की एक सरणी।

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

स्लाइड पर सभी आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड की किनारे के अनुसार संरेखित करता है या एक दूसरे के सापेक्ष संरेखित करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | int | निर्धारित करता है कि किस प्रकार का संरेखण लागू किया जाएगा। |
| alignToSlide | boolean | यदि true है, तो आकार स्लाइड किनारों के सापेक्ष संरेखित होंगे। |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | पैरेंट स्लाइड। |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

स्लाइड पर चयनित आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या एक दूसरे के सापेक्ष संरेखित करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | int | निर्धारित करता है कि किस प्रकार का संरेखण लागू किया जाएगा। |
| alignToSlide | boolean | यदि true है, तो आकार स्लाइड किनारों के सापेक्ष संरेखित होंगे। |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | पैरेंट स्लाइड। |
| shapeIndexes | int[] | संरेखित करने के लिए आकारों के अनुक्रमणिका। |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

समूह आकार के भीतर सभी आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या एक दूसरे के सापेक्ष संरेखित करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | int | निर्धारित करता है कि किस प्रकार का संरेखण लागू किया जाएगा। |
| alignToSlide | boolean | यदि true है, तो आकार स्लाइड किनारों के सापेक्ष संरेखित होंगे। |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | पैरेंट समूह आकार। |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

समूह आकार के भीतर चयनित आकारों की स्थिति बदलता है। आकारों को मार्जिन या स्लाइड के किनारे के अनुसार संरेखित करता है या एक दूसरे के सापेक्ष संरेखित करता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alignmentType | int | निर्धारित करता है कि किस प्रकार का संरेखण लागू किया जाएगा। |
| alignToSlide | boolean | यदि true है, तो आकार स्लाइड किनारों के सापेक्ष संरेखित होंगे। |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | पैरेंट समूह आकार। |
| shapeIndexes | int[] | संरेखित करने के लिए आकारों के अनुक्रमणिका। |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

प्रस्तुति में दिए गए स्वरूप के साथ पाठ को खोजता और बदलता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | स्कैन की गई प्रस्तुति। |
| withMasters | boolean | निर्धारित करता है कि मास्टर स्लाइड्स को स्कैन किया जाना चाहिए या नहीं। |
| find | java.lang.String | खोजने के लिए स्ट्रिंग मान। |
| replace | java.lang.String | बदलने के लिए स्ट्रिंग मान। खोजे गए स्ट्रिंग का वर्ण। |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

प्रस्तुति में दिए गए स्वरूप के साथ पाठ को खोजता और बदलता है।

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

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | स्कैन की गई प्रस्तुति। |
| withMasters | boolean | निर्धारित करता है कि मास्टर स्लाइड्स को स्कैन किया जाना चाहिए या नहीं। |
| find | java.lang.String | खोजने के लिए स्ट्रिंग मान। |
| replace | java.lang.String | बदलने के लिए स्ट्रिंग मान। |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | पाठ भाग को बदलने के लिए स्वरूप। यदि null है तो खोजे गए स्ट्रिंग के पहले अक्षर का स्वरूप उपयोग किया जाएगा। |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

PPTX प्रस्तुति में स्लाइड पर सभी टेक्स्ट फ़्रेम लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | स्कैन किया हुआ स्लाइड। |

**रिटर्न:**
com.aspose.slides.ITextFrame[] - एक एरे जो [TextFrame](../../com.aspose.slides/textframe) वस्तुओं का है।

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

निर्दिष्ट स्लाइड पर सभी टेक्स्ट फ्रेम लौटाता है जो दिए गए पाठ को शामिल करते हैं।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | खोजने के लिए स्लाइड। |
| text | java.lang.String | टेक्स्ट फ्रेम में खोजे जाने वाले पाठ। |
| checkPlaceholderText | boolean | निर्धारित करता है कि क्या खाली टेक्स्ट फ्रेम शामिल किए जाएँ, लेकिन जिनका प्लेसहोल्डर पाठ खोजे गए पाठ को शामिल करता है। |

**रिटर्न:**
com.aspose.slides.ITextFrame[] - एक एरे जो [ITextFrame](../../com.aspose.slides/itextframe) वस्तुओं का है जो निर्दिष्ट पाठ को शामिल करती हैं।

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

PPTX प्रस्तुति में सभी टेक्स्ट फ्रेम लौटाता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | स्कैन की गई प्रस्तुति। |
| withMasters | boolean | निर्धारित करता है कि मास्टर स्लाइड्स को स्कैन किया जाना चाहिए या नहीं। |

**रिटर्न:**
com.aspose.slides.ITextFrame[] - एक एरे जो [TextFrame](../../com.aspose.slides/textframe) वस्तुओं का है।

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

स्रोत फ़ाइल फ़ॉर्मेट को संबंधित [SaveFormat](../../com.aspose.slides/saveformat) में बदलता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| format | int | स्रोत फ़ाइल फ़ॉर्मेट। |

**रिटर्न:**
int - संबंधित [SaveFormat](../../com.aspose.slides/saveformat) मान।