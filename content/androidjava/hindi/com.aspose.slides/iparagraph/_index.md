---
title: IParagraph
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक पाठ के अनुच्छेद का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iparagraph/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

एक टेक्स्ट अनुच्छेद का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getPortions()](#getPortions--) | टेक्स्ट भागों का संग्रह लौटाता है। |
| [getParagraphFormat()](#getParagraphFormat--) | इस अनुच्छेद के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | समान फ़ॉर्मेटिंग वाले रन को जोड़ता है। |
| [getText()](#getText--) | एक अनुच्छेद का साधारण पाठ प्राप्त करता है या सेट करता है। |
| [setText(String value)](#setText-java.lang.String-) | एक अनुच्छेद का साधारण पाठ प्राप्त करता है या सेट करता है। |
| [getRect()](#getRect--) | अनुच्छेद को सीमित करने वाले आयत के निर्देशांक प्राप्त करता है। |
| [getLinesCount()](#getLinesCount--) | एक अनुच्छेद में लाइनों की संख्या प्राप्त करता है। |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | यदि अंतिम भाग के बाद एक अन्य भाग डाला जाता है तो उपयोग किए जाने वाले भाग गुणों को निर्दिष्ट करता है। |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | यदि अंतिम भाग के बाद एक अन्य भाग डाला जाता है तो उपयोग किए जाने वाले भाग गुणों को निर्दिष्ट करता है। |

### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

टेक्स्ट भागों का संग्रह लौटाता है। केवल-पढ़ने योग्य [IPortionCollection](../../com.aspose.slides/iportioncollection).

**रिटर्न:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

इस अनुच्छेद के लिए फ़ॉर्मेटिंग ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**रिटर्न:**
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

एक अनुच्छेद का साधारण पाठ प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

मूल्य: टेक्स्ट।

**रिटर्न:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

एक अनुच्छेद का साधारण पाठ प्राप्त करता है या सेट करता है। पढ़ें/लिखें String.

मूल्य: टेक्स्ट।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract RectF getRect()
```

अनुच्छेद को सीमित करने वाले आयत के निर्देशांक प्राप्त करता है। आयत में अनुच्छेद की सभी टेक्स्ट लाइनों को शामिल किया गया है, खाली लाइनों सहित।

**रिटर्न:**
android.graphics.RectF - अनुच्छेद को सीमित करने वाला आयत android.graphics.RectF

### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

एक अनुच्छेद में लाइनों की संख्या प्राप्त करता है।

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

**रिटर्न:**
int - अनुच्छेद में लाइनों की संख्या

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

यदि अंतिम भाग के बाद एक अन्य भाग डाला जाता है तो उपयोग किए जाने वाले भाग गुणों को निर्दिष्ट करता है।

**रिटर्न:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

यदि अंतिम भाग के बाद एक अन्य भाग डाला जाता है तो उपयोग किए जाने वाले भाग गुणों को निर्दिष्ट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |