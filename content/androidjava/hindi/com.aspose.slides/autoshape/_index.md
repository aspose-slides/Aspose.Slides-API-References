---
title: AutoShape
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक AutoShape का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/autoshape/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)  
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

एक AutoShape का प्रतिनिधित्व करता है।

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | shape के लॉक को लौटाता है। |
| [getAutoShapeLock()](#getAutoShapeLock--) | autoshape के लॉक को लौटाता है। |
| [getTextFrame()](#getTextFrame--) | AutoShape के लिए TextFrame ऑब्जेक्ट को लौटाता है। |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | निर्धारित करता है कि यह autoshape स्लाइड की पृष्ठभूमि भराव के साथ भरा जाना चाहिए या शैली या भराव स्वरूप द्वारा निर्दिष्ट। |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | निर्धारित करता है कि यह autoshape स्लाइड की पृष्ठभूमि भराव के साथ भरा जाना चाहिए या शैली या भराव स्वरूप द्वारा निर्दिष्ट। |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | एक shape में नया TextFrame जोड़ता है। |
| [isTextBox()](#isTextBox--) | निर्दिष्ट करता है कि shape एक टेक्स्ट बॉक्स है। |

### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

shape के लॉक को लौटाता है। केवल-पढ़ने योग्य [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**रिटर्न:**  
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)

### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

autoshape के लॉक को लौटाता है। केवल-पढ़ने योग्य [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**रिटर्न:**  
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

AutoShape के लिए TextFrame ऑब्जेक्ट को लौटाता है। केवल-पढ़ने योग्य [ITextFrame](../../com.aspose.slides/itextframe).

**रिटर्न:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

निर्धारित करता है कि यह autoshape स्लाइड की पृष्ठभूमि भराव के साथ भरा जाना चाहिए या शैली या भराव स्वरूप द्वारा निर्दिष्ट। पढ़ने/लिखने योग्य boolean.

**रिटर्न:**  
boolean

### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

निर्धारित करता है कि यह autoshape स्लाइड की पृष्ठभूमि भराव के साथ भरा जाना चाहिए या शैली या भराव स्वरूप द्वारा निर्दिष्ट। पढ़ने/लिखने योग्य boolean.

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

एक shape में नया TextFrame जोड़ता है। यदि shape में पहले से TextFrame है तो बस उसका टेक्स्ट बदल देता है।

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  //  प्रेजेंटेशन का उदाहरण बनाता है
>  Presentation pres = new Presentation();
>  try {
>      //  प्रेजेंटेशन में पहली स्लाइड प्राप्त करता है
>      ISlide sld = pres.getSlides().get_Item(0);
>      //  टाइप को Rectangle सेट करके एक AutoShape जोड़ता है
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      //  Rectangle में TextFrame जोड़ता है
>      ashp.addTextFrame(" ");
>      //  टेक्स्ट फ़्रेम तक पहुँचता है
>      ITextFrame txtFrame = ashp.getTextFrame();
>      //  टेक्स्ट फ़्रेम के लिए Paragraph ऑब्जेक्ट बनाता है
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      //  Paragraph के लिए Portion ऑब्जेक्ट बनाता है
>      IPortion portion = para.getPortions().get_Item(0);
>      //  टेक्स्ट सेट करता है
>      portion.setText("Aspose TextBox");
>      //  प्रेजेंटेशन को डिस्क पर सहेजता है
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      //  प्रेजेंटेशन में पहली स्लाइड प्राप्त करता है
>      ISlide slide = pres.getSlides().get_Item(0);
>      //  टाइप को Rectangle सेट करके एक AutoShape जोड़ता है
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      //  Rectangle में TextFrame जोड़ता है
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      //  TextFrame का टेक्स्ट फॉर्मेट प्राप्त करता है
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      //  TextFrame में कॉलम की संख्या निर्धारित करता है
>      format.setColumnCount(3);
>      //  कॉलम के बीच की दूरी निर्धारित करता है
>      format.setColumnSpacing(10);
>      //  प्रेजेंटेशन सहेजता है
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| text | java.lang.String | नए TextFrame के लिए डिफ़ॉल्ट टेक्स्ट। |

**रिटर्न:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

निर्दिष्ट करता है कि shape एक टेक्स्ट बॉक्स है।

--------------------

यदि shape को टेक्स्ट बॉक्स के रूप में निर्दिष्ट नहीं किया गया है, इसका मतलब यह नहीं है कि इसमें टेक्स्ट संलग्न नहीं हो सकता। एक टेक्स्ट बॉक्स केवल विशिष्ट गुणों वाले एक विशेषीकृत shape है।

**रिटर्न:**  
boolean