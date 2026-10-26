---
title: Paragraph
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: पाठ के एक अनुच्छेद का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/paragraph/
---
**Inheritance:**  
विरासत:  
java.lang.Object

**All Implemented Interfaces:**  
सभी लागू इंटरफ़ेस:  
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject  
```
public final class Paragraph implements IParagraph, IDOMObject
```

एक अनुच्छेद के पाठ को दर्शाता है।

## Constructors  
## निर्माता

| Constructor | Description |
| --- | --- |
| [Paragraph()](#Paragraph--) | डिफ़ॉल्ट गुणों के साथ Paragraph क्लास का नया इंस्टेंस आरंभ करता है। |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | कॉपी कंस्ट्रक्टर जो Paragraph क्लास का नया इंस्टेंस आरंभ करता है। |

## Methods  
## विधियाँ

| Method | Description |
| --- | --- |
| [getPortions()](#getPortions--) | एक पाठ भागों का संग्रह लौटाता है। |
| [getParagraphFormat()](#getParagraphFormat--) | इस अनुच्छेद के लिए स्वरूपण ऑब्जेक्ट लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | एक ही स्वरूपण वाले रन को जोड़ता है। |
| [getText()](#getText--) | एक अनुच्छेद का साधारण पाठ प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक अनुच्छेद का साधारण पाठ प्राप्त करता है या सेट करता है। |
| [getRect()](#getRect--) | अनुच्छेद को सीमित करने वाले आयत के निर्देशांक प्राप्त करें। |
| [getLinesCount()](#getLinesCount--) | एक अनुच्छेद में पंक्तियों की संख्या प्राप्त करें। |
| [getImage()](#getImage--) | अनुच्छेद की एक छवि लौटाता है। |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | निर्दिष्ट स्केल के साथ अनुच्छेद की एक छवि लौटाता है। |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | यदि अंतिम भाग के बाद दूसरा भाग जोड़ा जाता है तो उपयोग की जाने वाली भाग गुण निर्दिष्ट करता है। |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | यदि अंतिम भाग के बाद दूसरा भाग जोड़ा जाता है तो उपयोग की जाने वाली भाग गुण निर्दिष्ट करता है। |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | एक अनुच्छेद का पैरेंट स्लाइड लौटाता है। |
| [getPresentation()](#getPresentation--) | एक अनुच्छेद की पैरेंट प्रस्तुति लौटाता है। |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

डिफ़ॉल्ट गुणों के साथ Paragraph क्लास का नया इंस्टेंस आरंभ करता है।

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

कॉपी कंस्ट्रक्टर जो Paragraph क्लास का नया इंस्टेंस आरंभ करता है।

**Parameters:**  
**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

एक पाठ भागों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IPortionCollection](../../com.aspose.slides/iportioncollection)।

**Returns:**  
**वापसी:**  
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

इस अनुच्छेद के लिए स्वरूपण ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IParagraphFormat](../../com.aspose.slides/iparagraphformat)।

--------------------

स्वरूपण ऑब्जेक्ट में केवल वर्तमान अनुच्छेद के लिए परिभाषित स्वरूपण पैरामीटर होते हैं, विरासत में मिले डेटा लागू नहीं होते हैं।

विरासत वाले मानों सहित प्रभावी मान प्राप्त करने के लिए [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) विधि का उपयोग करें।

**Returns:**  
**वापसी:**  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

एक ही स्वरूपण वाले रन को जोड़ता है।

### getText() {#getText--}
```
public final String getText()
```

एक अनुच्छेद का साधारण पाठ प्राप्त करता है या सेट करता है। पढ़ना/लिखना स्ट्रिंग।

Value: The text.  
मान: पाठ।

**Returns:**  
**वापसी:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

एक अनुच्छेद का साधारण पाठ प्राप्त करता है या सेट करता है। पढ़ना/लिखना स्ट्रिंग।

Value: The text.  
मान: पाठ।

**Parameters:**  
**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

अनुच्छेद को सीमित करने वाले आयत के निर्देशांक प्राप्त करें। आयत में अनुच्छेद की सभी पाठ पंक्तियाँ शामिल हैं, जिसमें खाली पंक्तियाँ भी शामिल हैं।

**Returns:**  
**वापसी:**  
java.awt.geom.Rectangle2D.Float

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

एक अनुच्छेद में पंक्तियों की संख्या प्राप्त करें।

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

**Returns:**  
**वापसी:**  
int - अनुच्छेद में पंक्तियों की संख्या

### getImage() {#getImage--}
```
public final IImage getImage()
```

अनुच्छेद की एक छवि लौटाता है।

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

**Returns:**  
[IImage](../../com.aspose.slides/iimage) - रेंडर किए गए अनुच्छेद की छवि, या null यदि अनुच्छेद को पैरेंट संग्रह में नहीं पाया गया, वैध रेंडरिंग सीमा नहीं है, या छवि रेंडर करते समय त्रुटि हुई।

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

निर्दिष्ट स्केल के साथ अनुच्छेद की एक छवि लौटाता है।

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

**Parameters:**  
**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | अनुच्छेद की छवि पर लागू किया गया क्षैतिज स्केल कारक। |
| scaleY | float | अनुच्छेद की छवि पर लागू किया गया ऊर्ध्वाधर स्केल कारक। |

**Returns:**  
**वापसी:**  
[IImage](../../com.aspose.slides/iimage) - रेंडर किए गए अनुच्छेद की छवि, या null यदि अनुच्छेद को पैरेंट संग्रह में नहीं पाया गया, वैध रेंडरिंग सीमा नहीं है, या छवि रेंडर करते समय त्रुटि हुई।

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

यदि अंतिम भाग के बाद दूसरा भाग जोड़ा जाता है तो उपयोग की जाने वाली भाग गुण निर्दिष्ट करता है।

**Returns:**  
**वापसी:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

यदि अंतिम भाग के बाद दूसरा भाग जोड़ा जाता है तो उपयोग की जाने वाली भाग गुण निर्दिष्ट करता है।

**Parameters:**  
**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य IDOMObject।

**Returns:**  
**वापसी:**  
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

एक अनुच्छेद का पैरेंट स्लाइड लौटाता है। केवल-पढ़ने योग्य [BaseSlide](../../com.aspose.slides/baseslide)।

**Returns:**  
**वापसी:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

एक अनुच्छेद की पैरेंट प्रस्तुति लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../com.aspose.slides/ipresentation)।

**Returns:**  
**वापसी:**  
[IPresentation](../../com.aspose.slides/ipresentation)