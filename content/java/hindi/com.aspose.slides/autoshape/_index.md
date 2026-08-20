---
title: AutoShape
second_title: Aspose.Slides for Java API संदर्भ
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
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | शेप की लॉक लौटाता है। |
| [getAutoShapeLock()](#getAutoShapeLock--) | ऑटोशेप की लॉक लौटाता है। |
| [getTextFrame()](#getTextFrame--) | AutoShape के लिए TextFrame ऑब्जेक्ट लौटाता है। |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | निर्धारित करता है कि यह ऑटोशेप स्लाइड की पृष्ठभूमि भराव से भरना चाहिए या शैली या भराव स्वरूप द्वारा निर्दिष्ट होना चाहिए। |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | निर्धारित करता है कि यह ऑटोशेप स्लाइड की पृष्ठभूमि भराव से भरना चाहिए या शैली या भराव स्वरूप द्वारा निर्दिष्ट होना चाहिए। |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | शेप में एक नया TextFrame जोड़ता है। |
| [isTextBox()](#isTextBox--) | निर्दिष्ट करता है कि शेप टेक्स्ट बॉक्स है या नहीं। |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

शेप की लॉक लौटाता है। केवल-पढ़ने-योग्य [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)।

**रिटर्न:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

ऑटोशेप की लॉक लौटाता है। केवल-पढ़ने-योग्य [IAutoShapeLock](../../com.aspose.slides/iautoshapelock)।

**रिटर्न:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

AutoShape के लिए TextFrame ऑब्जेक्ट लौटाता है। केवल-पढ़ने-योग्य [ITextFrame](../../com.aspose.slides/itextframe)।

**रिटर्न:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

निर्धारित करता है कि यह ऑटोशेप स्लाइड की पृष्ठभूमि भराव से भरना चाहिए या शैली या भराव स्वरूप द्वारा निर्दिष्ट होना चाहिए। रीड/राइट बूलियन।

**रिटर्न:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

निर्धारित करता है कि यह ऑटोशेप स्लाइड की पृष्ठभूमि भराव से भरना चाहिए या शैली या भराव स्वरूप द्वारा निर्दिष्ट होना चाहिए। रीड/राइट बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

शेप में एक नया TextFrame जोड़ता है। यदि शेप में पहले से TextFrame है तो केवल उसका टेक्स्ट बदल देता है।

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
>  // Instantiates Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Adds an AutoShape with type set as Rectangle
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // Adds TextFrame to the Rectangle
>      ashp.addTextFrame(" ");
>      // Accesses the text frame
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // Creates the Paragraph object for text frame
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // Creates a Portion object for the paragraph
>      IPortion portion = para.getPortions().get_Item(0);
>      // Sets the text
>      portion.setText("Aspose TextBox");
>      // Saves the presentation to disk
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Gets the first slide in the presentation
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Add an AutoShape with type set as Rectangle
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // Add TextFrame to the Rectangle
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // Gets the text format of TextFrame
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // Specifies the number of columns in TextFrame
>      format.setColumnCount(3);
>      // Specifies the spacing between columns
>      format.setColumnSpacing(10);
>      // Saves the presentation
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

निर्दिष्ट करता है कि शेप टेक्स्ट बॉक्स है या नहीं।

--------------------

यदि शेप को टेक्स्ट बॉक्स के रूप में निर्दिष्ट नहीं किया गया है, तो इसका अर्थ यह नहीं है कि वह टेक्स्ट नहीं रख सकता। एक टेक्स्ट बॉक्स केवल विशिष्ट गुणों वाला विशेष शेप है।

**रिटर्न:**
boolean