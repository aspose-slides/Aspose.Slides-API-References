---
title: IParagraph
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: एक टेक्स्ट पैराग्राफ का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iparagraph/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

एक टेक्स्ट पैराग्राफ का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPortions()](#getPortions--) | टेक्स्ट भागों का संग्रह लौटाता है। |
| [getParagraphFormat()](#getParagraphFormat--) | इस पैराग्राफ के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [getText()](#getText--) | पैराग्राफ का सादा टेक्स्ट प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | पैराग्राफ का सादा टेक्स्ट प्राप्त करता है या सेट करता है। |
| [getRect()](#getRect--) | पैराग्राफ को सीमित करने वाले आयत के निर्देशांक प्राप्त करें। |
| [getLinesCount()](#getLinesCount--) | पैराग्राफ में लाइनों की संख्या प्राप्त करें। |
| [getImage()](#getImage--) | पैराग्राफ की छवि लौटाता है। |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | निर्दिष्ट स्केल के साथ पैराग्राफ की छवि लौटाता है। |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | यदि अंतिम भाग के बाद कोई अन्य भाग डाला जाता है तो उपयोग की जाने वाली भाग गुणधर्म निर्दिष्ट करता है। |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | यदि अंतिम भाग के बाद कोई अन्य भाग डाला जाता है तो उपयोग की जाने वाली भाग गुणधर्म निर्दिष्ट करता है। |

### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

टेक्स्ट भागों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IPortionCollection](../../com.aspose.slides/iportioncollection)।

**वापसी:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

इस पैराग्राफ के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IParagraphFormat](../../com.aspose.slides/iparagraphformat)।

**वापसी:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

समान फ़ॉर्मेटिंग वाले रन को जोड़ता है।

### getText() {#getText--}
```
public abstract String getText()
```

पैराग्राफ का सादा टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

मान: टेक्स्ट।

**वापसी:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

पैराग्राफ का सादा टेक्स्ट प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

मान: टेक्स्ट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

पैराग्राफ को सीमित करने वाले आयत के निर्देशांक प्राप्त करें। आयत में पैराग्राफ की सभी टेक्स्ट लाइनों को शामिल किया गया है, जिसमें खाली लाइनों भी शामिल हैं।

**वापसी:**
java.awt.geom.Rectangle2D.Float - पैराग्राफ को सीमित करने वाला आयत java.awt.geom.Rectangle2D.Float

### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

पैराग्राफ में लाइनों की संख्या प्राप्त करें।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**वापसी:**
int - पैराग्राफ में लाइनों की संख्या

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

पैराग्राफ की छवि लौटाता है।

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - रेंडर किया गया पैराग्राफ सम्मिलित करने वाली छवि, या null यदि पैराग्राफ को उसके पैरेंट संग्रह में नहीं पाया जा सकता, कोई वैध रेंडरिंग सीमा नहीं है, या छवि रेंडर करने के दौरान त्रुटि होती है।

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

निर्दिष्ट स्केल के साथ पैराग्राफ की छवि लौटाता है।

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleX | float | पैराग्राफ छवि पर लागू किया गया क्षैतिज स्केल कारक। |
| scaleY | float | पैराग्राफ छवि पर लागू किया गया लम्बवत स्केल कारक। |

**वापसी:**
[IImage](../../com.aspose.slides/iimage) - रेंडर किया गया पैराग्राफ सम्मिलित करने वाली छवि, या null यदि पैराग्राफ को उसके पैरेंट संग्रह में नहीं पाया जा सकता, कोई वैध रेंडरिंग सीमा नहीं है, या छवि रेंडर करने के दौरान त्रुटि होती है।

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

यदि अंतिम भाग के बाद कोई अन्य भाग डाला जाता है तो उपयोग की जाने वाली भाग गुणधर्म निर्दिष्ट करता है।

**वापसी:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

यदि अंतिम भाग के बाद कोई अन्य भाग डाला जाता है तो उपयोग की जाने वाली भाग गुणधर्म निर्दिष्ट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |